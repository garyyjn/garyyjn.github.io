---
layout: page
title: Deep Neural Network Compression
description: Use of dynamic programming to better quantize deep neural networks
img: assets/img/compression2.png
importance: 1
category: work
related_publications: false
---

Exact optimal clustering in 1-dimension can be done in polynomial time. As such, during the training of a deep neural network, an additional loss term that incentivizes parameters to be quantization and compression friendly can be calculated to exact value. In experiment, out method to quantize well known imaging classifcation models broke several compression record at the time, without harming model accuracy. 


{% include figure.liquid loading="eager" path="assets/img/compression1.png" title="toss demo" class="img-fluid rounded z-depth-1" %}

{% include figure.liquid loading="eager" path="assets/img/compression2.png" title="toss demo" class="img-fluid rounded z-depth-1" %}