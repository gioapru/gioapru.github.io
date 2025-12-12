---
title: 'ConCap: Practical Network Traffic Generation for (ML- and) Flow-based Intrusion Detection Systems'
collection: publications
permalink: /publications/satml26a
excerpt: ''
code: '[SaTML26a]'
date: 2025-12-12
venue: 'IEEE Conference on Secure and Trustworthy Machine Learning'
badge: <span class='badge badge-primary'> Conference</span>
type: Conference
authors: "Verkerken, M., D'hooge, L., Volckaert, B., De Turck, F., <u>Apruzzese, G.</u>"
citation: "Verkerken, M., D'hooge, L., Volckaert, B., De Turck, F., & Apruzzese, G. (2026, March).  “ConCap: Practical Network Traffic Generation for (ML- and) Flow-based Intrusion Detection Systems” In <i>2026 International Conference on Secure and Trustworthy Machine Learning (SaTML)</i>."
---
{% include base_path %}
<b>Abstract.</b> Network Intrusion Detection Systems (NIDS) have been studied in research for almost four decades. Yet, despite thousands of papers claiming scientific advances, a non-negligible number of recent works suggest that the findings of prior literature may be questionable. At the root of such a disagreement is the well-known challenge of obtaining data representative of a real-world network—and, hence, usable for security assessments. 

We tackle such a challenge in this paper. We propose ConCap, a practical tool meant to facilitate experimental research on NIDS. Through ConCap, a researcher can set up an isolated and lightweight network environment and configure it to produce network-related data, such as packets or NetFlows, that are automatically labeled—hence ready for fine-grained experiments.ConCap is rooted on open-source software and is designed to foster experimental reproducibility across the scientific community by sharing just one configuration file. Through comprehensive experiments on 10 different network activities, further expanded via in-depth analyses of 21 variants of two specific activities and of 100 repetitions of four other ones, we empirically verify that ConCap produces network data resembling that of a realworld network. We also carry out experiments on well-known benchmark datasets as well as on a real “smart-home” network, showing that, from a cyber-detection viewpoint, ConCap’s automatically-labeled NetFlows are functionally equivalent to those collected in other environments. Finally, we show that ConCap enables to safely reproduce sophisticated attack chains (e.g., to test/enhance existing NIDS). Altogether, ConCap is a solution to the “data problem” that is plaguing NIDS research.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/satml26a/satml26a.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/satml26a/satml26a_cite.html" target="_blank" rel="noopener">Cite</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="" target="_blank" rel="noopener">IEEE Xplore</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="" target="_blank" rel="noopener">Repository</a>


