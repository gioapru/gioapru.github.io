---
title: 'Adversarial News and Lost Profits: Manipulating Headlines in LLM-Driven Algorithmic Trading'
collection: publications
permalink: /publications/satml26b
excerpt: 'Placing an "e" instead of an "e" in a news headline can lead to substantial economical losses.'
code: '[SaTML26b]'
date: 2025-12-12
venue: 'IEEE Conference on Secure and Trustworthy Machine Learning'
badge: <span class='badge badge-primary'> Conference</span>
type: Conference
authors: "Rizvani, A., <u>Apruzzese, G.</u>, Laskov, P."
citation: "Rizvani, A., Apruzzese, G., & Laskov, P. (2026, March).  “Adversarial News and Lost Profits: Manipulating Headlines in LLM-Driven Algorithmic Trading” In <i>2026 International Conference on Secure and Trustworthy Machine Learning (SaTML)</i>."
---
{% include base_path %}
<b>Abstract.</b> Large Language Models (LLMs) are increasingly adopted in the financial domain. Their exceptional capabilities to analyse textual data make them well-suited for inferring the sentiment of finance-related news. Such feedback can be leveraged by algorithmic trading systems (ATS) to guide buy/sell decisions. However, this practice bears the risk that a threat actor may craft “adversarial news” intended to mislead an LLM. In particular, the news headline may include “malicious” content that remains invisible to human readers but which is still ingested by the LLM. Although prior work has studied textual adversarial examples, their system-wide impact on LLM-supported ATS has not yet been quantified in terms of monetary risk.

To address this threat, we consider an adversary with no direct access to an ATS but able to alter stock-related news headlines on a single day. We evaluate two human-imperceptible manipulations in a financial context: Unicode homoglyph substitutions that misroute models during stock-name recognition, and hidden-text clauses that alter the sentiment of the news headline. We implement a realistic ATS in Backtrader that fuses an LSTM-based price forecast with LLM-derived sentiment (FinBERT, FinGPT, FinLLaMA, and six general-purpose LLMs), and quantify monetary impact using portfolio metrics. Experiments on real-world data show that manipulating a one-day attack over 14 months can reliably mislead LLMs and reduce annual returns by up to 17.7 percentage points. To assess real-world feasibility, we analyze popular scraping libraries and trading platforms and survey 27 FinTech practitioners, confirming our hypotheses. We notified trading platform owners of this security issue.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/satml26b/satml26b.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/satml26b/satml26b_cite.html" target="_blank" rel="noopener">Cite</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="" target="_blank" rel="noopener">IEEE Xplore</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/AdvijeR/satml26_adversarial-news" target="_blank" rel="noopener">Repository</a>


