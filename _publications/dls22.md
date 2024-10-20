---
title: "Concept-based Adversarial Attacks: Tricking Humans and Classifiers Alike"
collection: publications
permalink: /publications/dls22
excerpt: "What's the point of minimal perturbations if we want to fool humans?"
date: 2022-05-26
code: '[DLS22]'
venue: 'IEEE Symposium on Security and Privacy – Deep Learning and Security Workshop'
badge: <span class='badge badge-danger'>Workshop</span>
type: Workshop
authors: 'Schneider, J., & <u>Apruzzese, G.</u>'
citation: 'Schneider, J., & Apruzzese, G. (2022). "Concept-based Adversarial Attacks: Tricking Humans and Classifiers Alike." In <i>IEEE Symposium on Security and Privacy Workshops</i>.'
---
{% include base_path %}
<b>Abstract.</b> We propose to generate adversarial samples by modifying activations of upper layers encoding semantically meaningful concepts. The original sample is shifted towards a target sample, yielding an adversarial sample, by using the modified activations to reconstruct the original sample. A human might (and possibly should) notice differences between the original and the adversarial sample. Depending on the attacker-provided constraints, an adversarial sample can exhibit subtle differences or appear like a "forged" sample from another class. Our approach and goal are in stark contrast to common attacks involving perturbations of single pixels that are not recognizable by humans. Our approach is relevant in, e.g., multi-stage processing of inputs, where both humans and machines are involved in decision-making because invisible perturbations will not fool a human. Our evaluation focuses on deep neural networks. We also show the transferability of our adversarial examples among networks.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/dls22/dls22.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/dls22/dls22_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://ieeexplore.ieee.org/document/9833874" target="_blank" rel="noopener">IEEE Xplore</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/dls22/dls22_slides.pdf" target="_blank" rel="noopener">Slides</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/talks/dls22" target="_blank" rel="noopener">Talk</a> 