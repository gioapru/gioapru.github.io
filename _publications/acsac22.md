---
title: "SpacePhish: The Evasion-space of Adversarial Attacks against Phishing Website Detectors using Machine Learning"
collection: publications
permalink: /publications/acsac22
excerpt: "What's the point of minimal perturbations if we want to fool humans?"
code: '[ACSAC22]'
date: 2022-12-07
venue: 'Annual Computer Security Applications Conference'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Schneider, J., & <u>Apruzzese, G.</u>'
citation: 'Schneider, J., & Apruzzese, G. (2022). "Concept-based Adversarial Attacks: Tricking Humans and Classifiers Alike." In <i>IEEE Symposium on Security and Privacy Workshops</i>.'
---
{% include base_path %}
<b>Abstract.</b> Existing literature on adversarial Machine Learning (ML) focuses either on showing attacks that break every ML model, or defenses that withstand most attacks. Unfortunately, little consideration is given to the actual _cost_ of the attack or the defense.
Moreover, adversarial samples are often crafted in the "feature-space", making the corresponding evaluations of questionable value. 
Simply put, the current situation does not allow to estimate the actual threat posed by adversarial attacks, leading to a lack of secure ML systems.

We aim to clarify such confusion in this paper. By considering the application of ML for Phishing Website Detection (PWD), we formalize the "evasion-space" in which an adversarial perturbation can be introduced to fool a ML-PWD---demonstrating that even perturbations in the "feature-space" are useful. Then, we propose a realistic threat model describing evasion attacks against ML-PWD that are cheap to stage, and hence intrinsically more attractive for real phishers. Finally, we perform the first statistically validated assessment of state-of-the-art ML-PWD against 12 evasion attacks. Our evaluation shows (i) the true efficacy of evasion attempts that are more likely to occur; and (ii) the impact of perturbations crafted in different evasion-spaces. Our realistic evasion attempts induce a statistically significant degradation (3--10% at _p_<0.05), and their cheap cost makes them a subtle threat. Notably, however, some ML-PWD are immune to our most realistic attacks (_p_=0.22).
Our contribution paves the way for a much needed re-assessment of adversarial attacks against ML systems for cybersecurity.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/acsac22/acsac22.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/acsac22/acsac22_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://dl.acm.org/doi/abs/" target="_blank" rel="noopener">ACM Digital Library</a>  
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://spacephish.github.io" target="_blank" rel="noopener">Website</a>