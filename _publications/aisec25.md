---
title: "E-PhishGEN: Unlocking Novel Research in Phishing Email Detection"
collection: publications
permalink: /publications/aisec25
excerpt: 'Most research in phishing email detection uses outdated datasets, so we try to make things a bit better.'
code: '[AISec25]'
date: 2025-08-11
venue: 'ACM Workshop on Artificial Intelligence Security'
badge: <span class='badge badge-danger'>Workshop</span>
type: Workshop
authors: 'Pajola, L., Caripoti, E., Banzer, S., Pizzi, S., Conti, M., & <u>Apruzzese, G.</u>'
citation: 'Pajola, L., Caripoti, E., Banzer, S., Pizzi, S., Conti, M., & <u>Apruzzese, G.</u> (2025, October). "E-PhishGEN: Unlocking Novel Research in Phishing Email Detection." In <i>2025 18th ACM Workshop on Artificial Intelligence Security (AISec)</i>. ACM.'
---
{% include base_path %}

<b>Abstract.</b> Every day, our inboxes are flooded with unsolicited emails, ranging between annoying spam to more subtle phishing scams. Unfortunately, despite abundant prior efforts proposing solutions achieving near-perfect accuracy, the reality is that countering malicious emails still remains an unsolved dilemma.

This "open problem" paper carries out a critical assessment of scientific works in the context of phishing email detection. First, we focus on the _benchmark datasets_ that have been used to assess the methods proposed in research. We find that most prior work relied on datasets containing emails that---we argue---are not representative of current trends, and mostly encompass the English language. Based on this finding, we then re-implement and re-assess a variety of _detection methods reliant on machine learning_ (ML), including large-language models (LLM), and release all of our codebase---an (unfortunately) uncommon practice in related research. We show that most such methods achieve near-perfect performance when trained and tested on the same dataset---a result which intrinsically hinders development (how can future research outperform methods that are already near perfect?). To foster the creation of "more challenging benchmarks" that reflect current phishing trends, we propose E-PhishGen, an LLM-based (and privacy-savvy) framework to generate novel phishing-email datasets. We use our E-PhishGen to create E-PhishLLM, a novel phishing-email detection dataset containing 16616 emails in three languages. We use E-PhishLLM to test the detectors we considered, showing a much lower performance than that achieved on existing benchmarks---indicating a larger room for improvement. We also validate the quality of E-PhishLLM with a user study (n=30). To sum up, we show that phishing email detection is still an open problem---and provide the means to tackle such a problem by future research.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/aisec25/aisec25.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/aisec25/aisec25_cite.html" target="_blank" rel="noopener">Cite</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/" target="_blank" rel="noopener">Code (TBD)</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://doi.org/" target="_blank" rel="noopener">ACM Digital Library</a>

