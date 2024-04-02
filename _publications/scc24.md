---
title: "Machine Learning in Space: Reviewing and Analysing the Robustness of on-board ML models to Radiation"
collection: publications
permalink: /publications/scc24
excerpt: 'A joint work with space-industry practitioners.'
code: '[SCC24]'
date: 2024-02-04
venue: 'IEEE Space Computing Conference'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Lange, K., Fontana, F., Rossi, F., Varile, M., <u>Apruzzese, G.</u>'
citation: 'Lange, K., Fontana, F., Rossi, F., Varile, M., & Apruzzese, G. (2024, July). "Machine Learning in Space: Reviewing and Analysing the Robustness of on-board ML models to Radiation." In <i>2024 IEEE Space Computing Conference (SCC)</i>.'
---
{% include base_path %}
<b>Abstract.</b> Modern spacecraft are increasingly relying on machine learning (ML). However, physical equipment in space is subject to various natural hazards, such as radiation, which may inhibit the correct operation of computing devices. Despite plenty of evidence showing the damage that naturally-induced faults can cause to ML-related hardware, we observe that the effects of radiation on ML models for space applications are not well-studied. This is a problem: without understanding how ML models are affected by these natural phenomena, it is uncertain “where to start from” to develop radiation-tolerant ML software.

As ML researchers, we attempt to tackle this dilemma. By partnering up with space-industry practitioners specialized in ML, we perform a reflective analysis of the state of the art. We provide factual evidence that prior research did not thoroughly examine the impact of natural hazards on ML models meant for spacecraft. Then, through a “negative result,” we show that some existing open-source technologies can hardly be used by researchers to study the effects of radiation for some typical applications of ML in satellites. As a constructive step forward, we perform simple experiments showcasing how to leverage current frameworks to assess the robustness of practical ML models for cloud detection against radiation-induced faults. Our evaluation reveals that not all faults are as devastating as claimed by some prior work. By publicly releasing our resources, we provide a foothold—usable by researchers without access to spacecraft—for spearheading development of space-tolerant ML models.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/scc24/scc24.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/scc24/scc24_cite.html" target="_blank" rel="noopener">Cite</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/langekevin/mlspace_robustness/" target="_blank" rel="noopener">Repository</a>