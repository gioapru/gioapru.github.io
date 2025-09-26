---
title: "It’s not Easy: Applying Supervised Machine Learning to Detect Malicious Extensions in the Chrome Web Store"
collection: publications
permalink: /publications/tweb25
excerpt: 'Nobody really _tried_ to use supervised ML to detect browser extensions. So, we tried. Results were...'
date: 2025-09-53
code: '[TWEB25]'
venue: 'ACM Transactions on the Web'
badge: <span class='badge badge-success'>Journal</span>
type: Journal
authors: 'Rosenzweig, B., Dalla Valle, V., <u>Apruzzese, G.</u>, Fass, A.'
citation: 'Rosenzweig, B., Dalla Valle, V., Apruzzese, G.,  & Fass, A. (2025). It’s not Easy: Applying Supervised Machine Learning to Detect Malicious Extensions in the Chrome Web Store. <i>ACM Transactions on the Web</i>.'
---
{% include base_path %}
<b>Abstract.</b> Google Chrome is the most popular Web browser.
Users can customize it with extensions that enhance their browsing experience. The most well-known marketplace of such extensions is the Chrome Web Store (CWS). Developers can upload their extensions on the CWS, but such extensions are made available to users only after a vetting process carried out by Google itself. Unfortunately, some malicious extensions bypass such checks, putting the security and privacy of downstream browser extension users at risk. 

In this paper, we carry out a comprehensive real-world security analysis of malicious extensions in the CWS.
Specifically, we scrutinize the extent to which automated mechanisms reliant on supervised machine learning (ML) can be used to detect malicious extensions on the CWS.
To this end, we first collect 7,140 malicious extensions published in 2017--2023 and which have been flagged as malicious by Google.
We combine this dataset with 63,598 benign extensions published or updated on the CWS before 2023, and we develop three supervised-ML-based classifiers---leveraging both original features as well as techniques inspired by prior work.
We show that, in a "lab setting", our classifiers work well (e.g., 98% accuracy).
Then, we collect a new, and more recent, set of 35,462 extensions from the CWS, published or last updated in 2023, with unknown ground truth.
We were eventually able to identify 68 malicious extensions that bypassed the vetting process of the CWS. However, our classifiers also reported over 1k likely malicious extensions which may overestimate their true number.
Based on this finding (further supported with other experiments and realistic analyses), we elucidate, for the first time, a strong concept drift effect on browser extensions.
We also provide factual evidence that commercial detectors (e.g., VirusTotal) work poorly to detect known malicious extensions.
Altogether, our results highlight the fact that detecting malicious browser extensions is a fundamentally hard problem which has not (yet) received an adequate degree of attention. This requires additional work both by the research community and by Google itself---potentially by revising their approaches. In the meantime, we informed Google of our discoveries, and we release our artifacts.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/tweb25/tweb25.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/tweb25/tweb25_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://ieeexplore.ieee.org/" target="_blank" rel="noopener">ACM DL</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/its-not-easy/tweb25" target="_blank" rel="noopener">Code</a>  