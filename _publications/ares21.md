---
title: "On the Evaluation of Sequential Machine Learning for Network Intrusion Detection"
collection: publications
permalink: /publications/ares21
code: '[ARES21]'
excerpt: "Are temporal patterns useful for ML-NIDS? Let's test this out with a fair comparison between LSTM and traditional FNN."
date: 2021-08-17
venue: 'International Conference on Availability, Reliability and Security'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Corsini, A., Yang, S. J., & <u>Apruzzese, G.</u>'
citation: 'Corsini, A., Yang, S. J., & Apruzzese, G. (2021, August). "On the Evaluation of Sequential Machine Learning for Network Intrusion Detection." In <i>The 16th International Conference on Availability, Reliability and Security (ARES)</i> (pp. 1-10).'
---
<b>Abstract.</b> Recent advances in deep learning renewed the research interests in machine learning for Network Intrusion Detection Systems (NIDS). Specifically, attention has been given to sequential learning models, due to their ability to extract the temporal characteristics of network traffic flows (NetFlows), and use them for NIDS tasks. However, the applications of these sequential models often consist of transferring and adapting methodologies directly from other fields, without an in-depth investigation on how to leverage the specific circumstances of cybersecurity scenarios; moreover, there is a lack of comprehensive studies on sequential models that rely on NetFlow data, which presents significant advantages over traditional full packet captures. We tackle this problem in this paper. We propose a detailed methodology to extract temporal sequences of NetFlows that denote patterns of malicious activities. Then, we apply this methodology to compare the efficacy of sequential learning models against traditional static learning models. In particular, we perform a fair comparison of a ‘sequential’ Long Short-Term Memory (LSTM) against a ‘static’ Feedforward Neural Networks (FNN) in distinct environments represented by two well-known datasets for NIDS: the CICIDS2017 and the CTU13. Our results highlight that LSTM achieves comparable performance to FNN in the CICIDS2017 with over 99.5% F1-score; while obtaining superior performance in the CTU13, with 95.7% F1-score against 91.5%. This paper thus paves the way to future applications of sequential learning models for NIDS.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://gioapru.github.io/files/papers/ares21/ares21.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://gioapru.github.io/files/papers/ares21/ares21_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://dl.acm.org/doi/abs/10.1145/3465481.3470065" target="_blank" rel="noopener">ACM Digital Library</a> 