---
layout: page
title: Adversarial Attack in AI Pathology
description: Quite easy to 
img: assets/img/defense.png
importance: 1
category: work
related_publications: false
---

Attention based weakly-supervised learning is a premier method for classifying whole-slide imaging. I explored some adversarial attack strategies againest histopathology AI. I discovered that leveraging the attention mechanism, attack the top-few attention tiles is sufficient at massively damaging accuracy.

{% include figure.liquid loading="eager" path="assets/img/attack.png" title="toss demo" class="img-fluid rounded z-depth-1" %}

I also propose computationally-cheap methods for training againest such an attack.

{% include figure.liquid loading="eager" path="assets/img/defense.png" title="toss demo" class="img-fluid rounded z-depth-1" %}

Paper/poster presented at ICML BioComp Workshop
