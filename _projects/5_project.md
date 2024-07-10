---
layout: page
title: Adversarial Attack in AI Pathology
description: Modify a very small portion of slide imaging very slightly to trick Pathology AI, and how to defend.
img: assets/img/defense.png
importance: 1
category: work
related_publications: false
---

Attention based weakly-supervised learning is a premier method for classifying whole-slide imaging. I explored some adversarial attack strategies againest such kind of histopathology AI. I discovered that by leveraging the attention mechanism, attacking the top-few important tiles is sufficient at massively damaging model accuracy. If drug seeking behavior is a common abuse againest human doctors, will there exist economic incentive to preform adversarial attacks to trick AI-based diagnosis pipelines in the future?

{% include figure.liquid loading="eager" path="assets/img/attack.png" title="toss demo" class="img-fluid rounded z-depth-1" %}

I also propose computationally-cheap methods for training againest such an attack.

{% include figure.liquid loading="eager" path="assets/img/defense.png" title="toss demo" class="img-fluid rounded z-depth-1" %}

Paper/poster presented at ICML BioComp Workshop
