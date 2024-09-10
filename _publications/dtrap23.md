---
title: "Multi-SpacePhish: Extending the Evasion-space of Adversarial Attacks against Phishing Website Detectors using Machine Learning"
collection: publications
permalink: /publications/dtrap23
excerpt: "We extend the [ACSAC'22] paper with new experiments by _mixing_ the perturbation spaces!"
date: 2023-12-08
code: '[DTRAP23]'
venue: 'ACM Digital Threats: Research and Practice'
badge: <span class='badge badge-success'>Journal</span>
type: Journal
authors: 'Yuan, Y. and <u>Apruzzese, G.</u>, and Conti. M.'
citation: 'Yuan, Y., Apruzzese, G., & Conti, M. (2023). "Multi-SpacePhish: Extending the Evasion-space of Adversarial Attacks against Phishing Website Detectors using Machine Learning." <i>ACM Digital Threats: Research and Practice</i>.'
---
{% include base_path %}
<b>Abstract.</b> Existing literature on adversarial Machine Learning (ML) focuses either on showing attacks that break every ML model, or defenses that withstand most attacks. Unfortunately, little consideration is given to the actual _feasibility_ of the attack or the defense.
Moreover, adversarial samples are often crafted in the ``feature-space'', making the corresponding evaluations of questionable value. 
Simply put, the current situation does not allow to estimate the actual threat posed by adversarial attacks, leading to a lack of secure ML systems.

We aim to clarify such confusion in this paper. By considering the application of ML for Phishing Website Detection (PWD), we formalize the "evasion-space" in which an adversarial perturbation can be introduced to fool a ML-PWD---demonstrating that even perturbations in the "feature-space" are useful. Then, we propose a realistic threat model describing evasion attacks against ML-PWD that are cheap to stage, and hence intrinsically more attractive for real phishers. After that, we perform the first statistically validated assessment of state-of-the-art ML-PWD against 12 evasion attacks. Our evaluation shows (i) the true efficacy of evasion attempts that are more likely to occur; and (ii) the impact of perturbations crafted in different evasion-spaces; 
Our realistic evasion attempts induce a statistically significant degradation (3--10% at _p_<0.05), and their cheap cost makes them a subtle threat. Notably, however, some ML-PWD are immune to our most realistic attacks (_p_=0.22). 

Finally, as an additional contribution of this journal publication, we are the first to propose and empirically evaluate the intriguing case wherein an attacker introduces perturbations in multiple evasion-spaces _at the same time}_. These new results show that simultaneously applying perturbations in the problem- and feature-space can cause a drop in the detection rate from 0.95 to 0.

Our contribution paves the way for a much needed re-assessment of adversarial attacks against ML systems for cybersecurity. 

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/dtrap23/dtrap23.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/dtrap23/dtrap23_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://dl.acm.org/doi/10.1145/3638253" target="_blank" rel="noopener">ACM Digital Library</a> 
