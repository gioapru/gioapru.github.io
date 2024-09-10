---
title: "Multi-SpacePhish: Extending the Evasion-space of Adversarial Attacks against Phishing Website Detectors using Machine Learning"
collection: publications
permalink: /publications/cose24
excerpt: "Apparently, most research on phishing website detection only focused on the Western side of the world..."
date: 2024-09-09
code: '[COSE24]'
venue: 'Computers & Security'
badge: <span class='badge badge-success'>Journal</span>
type: Journal
authors: 'Yuan, Y. and <u>Apruzzese, G.</u>, and Conti. M.'
citation: 'Yuan, Y., Apruzzese, G., & Conti, M. (2023). "Beyond the West: Revealing and Bridging the Gap between Western and Chinese Phishing Website Detection ." <i>Computers & Security</i>.'
---
{% include base_path %}
<b>Abstract.</b> Phishing attacks are on the rise, and phishing _websites_ are everywhere, denoting the brittleness of security mechanisms reliant on blocklists. To cope with this threat, many works proposed to enhance Phishing Website Detectors (PWD) with data-driven techniques powered by Machine Learning (ML). Despite achieving promising results both in research and practice, existing solutions mostly focus "on the West", e.g., they consider websites in English, German, or Italian. In contrast, phishing websites targeting "Eastern" countries, such as China, have been mostly neglected---despite phishing being rampant also in this side of the world.

In this paper, we scrutinize whether current PWD can simultaneously work against Western and Chinese phishing websites. First, after highlighting the difficulties of practically testing PWD on Chinese phishing websites, we create _ChiPhish_---a dataset which enables assessment of PWD on Chinese websites. Then, we evaluate 72 PWD developed by industry practitioners and 10 ML-based PWD proposed in recent research on Western and Chinese websites: our results highlight that existing solutions, despite achieving low false positive rates, exhibit unacceptably low detection rates (sometimes inferior to 1%) on phishing websites of different regions. Next, to bridge the gap we brought to light, we elucidate the differences between Western and Chinese websites, and devise an enhanced feature set that accounts for the unique characteristics of Chinese websites. We empirically demonstrate the effectiveness of our proposed feature set by replicating (and testing) state-of-the-art ML-PWD: our results show a small but statistically significant improvement over the baselines. Finally, we review all our previous contributions and combine them to develop practical PWD that simultaneously work on Chinese and Western websites, achieving over 0.98 detection rate while maintaining only 0.01 false positive rate in a cross-regional setting. We openly release all our tools, disclose all our benchmark results, and also perform proof-of-concept experiments revealing that the problem tackled by our paper extends to other "Eastern" countries that have been overlooked by prior research on PWD.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/cose24/cose24.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/cose24/cose24_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://" target="_blank" rel="noopener">ScienceDirect</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/" target="_blank" rel="noopener">Repository</a>