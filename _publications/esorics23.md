---
title: "Attacking Logo-based Phishing Website Detectors with Adversarial Perturbations"
collection: publications
permalink: /publications/esorics23
excerpt: "A novel attack against state-of-the-art DL methods for logo identification, validated via two user-studies."
date: 2023-08-14
code: '[ESORICS23]'
venue: 'European Symposium on Research In Computer Security'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Lee, J., Xin, Z., Ng. M. P. S., Sabharwal, K., <u>Apruzzese, G.</u>, Divakaran. D. M.'
citation: 'Lee, J., Xin, Z., Ng. M. P. S., Sabharwal, K., Apruzzese, G., Divakaran. D. M. (2023, Sept.). "Attacking logo-based Phishing Website Detectors with Adversarial Perturbations." In <i>European Symposium on Research in Computer Security (ESORICS)</i>.'
---
{% include base_path %}
<b>Abstract.</b> Recent times have witnessed the rise of anti-phishing schemes powered by deep learning (DL). In particular, logo-based phishing detectors rely on DL models from Computer Vision to identify logos of well-known brands on webpages, to detect malicious webpages that imitate a given brand. For instance, Siamese networks have demonstrated notable performance for these tasks, enabling the corresponding anti-phishing solutions to detect even "zero-day" phishing webpages.
In this work, we take the next step of studying the robustness of logo-based phishing detectors against adversarial ML attacks. We propose a novel attack exploiting generative adversarial perturbations to craft "adversarial logos" that evade phishing detectors. We evaluate our attacks through: (i) experiments on datasets containing real logos, to evaluate the robustness of state-of-the-art phishing detectors; and (ii) user studies to gauge whether our adversarial logos can deceive human eyes. The results show that our proposed attack is capable of crafting perturbed logos subtle enough to evade various DL models---achieving an evasion rate of up to 95%. Moreover, users are not able to spot significant differences between generated adversarial logos and original ones.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/esorics23/esorics23.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/esorics23/esorics23_cite.html" target="_blank" rel="noopener">Cite</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://link.springer.com/chapter/10.1007/978-3-031-51479-1_9" target="_blank" rel="noopener">SpringerLink</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/JehLeeKR/Adversarial-phishing-logos" target="_blank" rel="noopener">Artifact (Code)</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/talks/esorics23" target="_blank" rel="noopener">Talk</a> 
