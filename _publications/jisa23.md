---
title: "Dual Adversarial Attacks: Fooling Humans and Classifiers"
collection: publications
permalink: /publications/jisa23
excerpt: "We extend the [DLS22] paper and we also carry out a user-study!"
date: 2023-04-13
code: '[JISA23]'
venue: 'Journal of Information Security and Applications'
badge: <span class='badge badge-success'>Journal</span>
type: Journal
authors: 'Schneider, J., & <u>Apruzzese, G.</u>'
citation: 'Schneider, J., & Apruzzese, G. (2023). "Dual Adversarial Attacks: Fooling Humans and Classifiers." In <i>Journal of Information Security and Applications</i>.'
---
{% include base_path %}
<b>Abstract.</b>
Adversarial samples mostly aim at fooling machine
learning (ML) models. They often involve minor pixel-based perturbations that are imperceptible to human observers. In this work, adversarial samples should fool both humans and ML models, which is important in two-stage decision processes. We perform changes on a higher abstraction level so that a target sample exhibits properties of a desired sample. Technically, we contribute by deriving a regularization scheme for autoencoders incorporating a classifier loss for smoothly interpolating between wildly different samples. The realism and effectiveness of generated samples are confirmed with a user study and other evaluations. Our experiments consider neural networks of four architectures, assessed on MNIST, FashionMNIST, QuickDraw and CIFAR-10. Results show that our scheme leads to superior performance compared to existing interpolation techniques: on average, other methods have an 11% higher failure rate when producing
a sample that is of any of two interpolated classes. Furthermore, our attacks work in both white- and black-box settings. Finally, humans are very confused by the samples generated with our method (_p<0.0001_).

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/jisa23/jisa23.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/jisa23/jisa23_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.sciencedirect.com/science/article/pii/S2214212623000868" target="_blank" rel="noopener">ScienceDirect</a>  