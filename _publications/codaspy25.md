---
title: "The Ephemeral Threat: Assessing the Security of Algorithmic Trading Systems powered by Deep Learning"
collection: publications
permalink: /publications/codaspy25
excerpt: 'Did you know that very little has been done in the adversarial ML domain w.r.t. ML applications in computational finance?'
code: '[CODASPY25]'
date: 2025-06-05
venue: 'ACM Conference on Data and Application Security and Privacy'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Rizvani, A., <u>Apruzzese, G.</u>, & Laskov, P.'
citation: 'Rizvani, A., Apruzzese, G., & Laskov, P. (2025, June). "The Ephemeral Threat: Assessing the Security of Algorithmic Trading Systems powered by Deep Learning." In <i>2025 15th ACM Conference on Data and Application Security and Privacy (CODASPY)</i>.'
---
{% include base_path %}
<b>Abstract.</b> We study the security of stock price forecasting using Deep Learning (DL) in computational finance. Despite abundant prior research on vulnerability of DL to adversarial perturbations, such work has hitherto hardly addressed practical adversarial threat models in the context of DL-powered algorithmic trading systems (ATS).

Specifically, we investigate the vulnerability of ATS to adversarial perturbations launched by a realistically constrained attacker. We first show that existing literature has paid limited attention to DL security in the financial domain---which is naturally attractive for adversaries. Then, we formalize the concept of ephemeral perturbations (EP), which can be used to stage a novel type of attack tailored for DL-based ATS. Finally, we carry out an end-to-end evaluation of our EP against a profitable ATS. Our results reveal that the introduction of small changes to the input stock-prices not only (i) induces the DL model to behave incorrectly but also (ii) leads to the whole ATS to make suboptimal buy/sell decisions, resulting in a worse financial performance of the targeted ATS.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/codaspy25/codaspy25.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/codaspy25/codaspy25_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://doi.org/10.1145/3714393.3726490" target="_blank" rel="noopener">ACM Digital Library</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/AdvijeR/ep-ats/" target="_blank" rel="noopener">Code</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/codaspy25/codaspy25_slides.pdf" target="_blank" rel="noopener">Slides</a> 