---
title: "SoK: The Impact of Unlabelled Data in Cyberthreat Detection"
collection: publications
permalink: /publications/eurosp22
excerpt: 'How to properly evaluate semisupervised learning methods.'
date: 2022-06-09
code: '[EuroSP22]'
venue: 'IEEE European Symposium on Security and Privacy [OUTSTANDING PRESENTATION AWARD]'
badge: <span class='badge badge-primary'> <i class="fa fa-award"></i> Conference</span>
type: Conference
authors: '<u>Apruzzese, G.</u>, Laskov, P., & Tastemirova, A.'
citation: 'Apruzzese, G., Laskov, P., & Tastemirova, A. (2022). "SoK: The Impact of Unlabelled Data in Cyberthreat Detection." In <i>IEEE European Symposium on Security and Privacy (EuroS&P)</i> [OUTSTANDING PRESENTATION AWARD]).'
---
{% include base_path %}
<b>Abstract.</b> Machine learning (ML) has become an important paradigm for cyberthreat detection (CTD) in the recent years. A substantial research effort has been invested in the development of specialized algorithms for CTD tasks. From the operational perspective, however, the progress of ML-based CTD is hindered by the difficulty in obtaining the large sets of labelled data to train ML detectors. A potential solution to this problem are semisupervised learning (SsL) methods, which combine small labelled datasets with large amounts of unlabelled data.
This paper is aimed at systematization of existing work on SsL for CTD and, in particular, on understanding the utility of unlabelled data in such systems. To this end, we analyze the cost of labelling in various CTD tasks and develop a formal cost model for SsL in this context. Building on this foundation, we formalize a set of requirements for evaluation of SsL methods, which elucidates the contribution of unlabelled data. We review the state-of-the-art and observe that no previous work meets such requirements. To address this problem, we propose a framework for assessing the benefits of unlabelled data in SsL. We showcase an application of this framework by performing the first benchmark evaluation that highlights the tradeoffs of 9 existing SsL methods on 9 public datasets. Our findings verify that, in some cases, unlabelled data provides a small, but statistically significant, performance gain. This paper highlights that SsL in CTD has a lot of room for improvement, which should stimulate future research in this field.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/eurosp22/eurosp22.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/eurosp22/eurosp22_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://ieeexplore.ieee.org/document/9797356" target="_blank" rel="noopener">IEEE Xplore</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/eurosp22/eurosp22_slides.pdf" target="_blank" rel="noopener">Slides</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/hihey54/CEF-SsL" target="_blank" rel="noopener">Code</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/talks/eurosp22" target="_blank" rel="noopener">Talk</a> 