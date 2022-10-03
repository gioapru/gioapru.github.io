---
title: "Mitigating Adversarial Gray-Box Attacks against Phishing Detectors"
collection: publications
permalink: /publications/tdsc22
code: '[TDSC22]'
excerpt: "A new phishing dataset, and a new defensive mechanism based on feature randomization."
date: 2022-12-09
venue: 'IEEE Transactions on Dependable and Secure Computing'
badge: <span class='badge badge-success'>Journal</span>
type: Journal
authors: '<u>Apruzzese, G.</u>, & V.S. Subrahmanian'
citation: 'Apruzzese, G., & V.S. Subrahmanian. (2022, September). "Mitigating Adversarial Gray-Box Attacks against Phishing Website Detectors." In <i>IEEE Transactions on Dependable and Secure Computing (TDSC)</i>.'
---
{% include base_path %}
<b>Abstract.</b> Although machine learning based algorithms have been extensively used for detecting phishing websites, there has been relatively little work on how adversaries may attack such "phishing detectors" (PDs for short). In this paper, we propose a set of Gray-Box attacks on PDs that an adversary may use which vary depending on the knowledge that he has about the PD. We show that these attacks severely degrade the effectiveness of several existing PDs. We then propose the concept of _operation chains_ that iteratively map an original set of features to a new set of features and develop the _Protective Operation Chain_ (POC for short) algorithm. POC leverages the combination of random feature selection and feature mappings in order to increase the attacker's uncertainty about the target PD. Using 3 existing publicly available datasets plus a fourth that we have created and will release upon the publication of this paper, we show that POC is more robust to these attacks than past competing work, while preserving predictive performance when no adversarial attacks are present. Moreover, POC is robust to attacks on 13 different classifiers, not just one. These results are shown to be statistically significant at the _p_ < 0.001 level.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/tdsc22/tdsc22.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/tdsc22/tdsc22_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://doi.org/10.1109/TDSC.2022.3210029" target="_blank" rel="noopener">IEEE Xplore</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.lnu-phish.github.io" target="_blank" rel="noopener">Website</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/tdsc22/tdsc22_slides.html" target="_blank" rel="noopener">Slides (preliminary)</a>