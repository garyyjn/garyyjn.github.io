---
layout: page
title: Disentangling Evidence Modality in Video Classification
description: More human-understandable interpretation for 3d CNN video classifiers
img: assets/img/fusion.png
importance: 1
category: work
related_publications: false
---

A universally applicable injection to 3d CNN video classifier that allows for explainability tools such as grad-cam to distinguish between static (single frame) evidence and moving evidence (motion) that contributed to model decision. Easy fine-tuning and no effect on accuracy in experiment. 

{% include figure.liquid loading="eager" path="assets/img/attack.png" title="toss demo" class="img-fluid rounded z-depth-1" %}

I also propose computationally-cheap methods for training againest such an attack.

{% include figure.liquid loading="eager" path="assets/img/defense.png" title="toss demo" class="img-fluid rounded z-depth-1" %}

Paper/poster presented at ICML BioComp Workshop
