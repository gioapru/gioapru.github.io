---
title: 'The Ephemeral Threat: Attacking Algorithmic Trading Systems powered by Deep Learning'
collection: publications
permalink: /publications/wacco24
excerpt: 'We delve into the security of machine learning applications in computational finance.'
code: '[WACCO24]'
date: 2024-07-08
venue: 'Workshop on Attackers and Cyber-Crime Operations'
badge: <span class='badge badge-danger'>Workshop</span>
type: Workshop
authors: 'Rizvani, A., Laskov, P., <u>Apruzzese, G.</u>'
citation: 'Rizvani, A., Laskov, P., & Apruzzese, G. (2024, July). "The Ephemeral Threat: Attacking Algorithmic Trading Systems powered by Deep Learning" In <i>2024 Workshop on Attackers and Cyber-Crime Operations (WACCO)</i> (co-located with IEEE EuroS&P24).'
---
{% include base_path %}

<b>Abstract.</b> We scrutinize the security of an application domain of Deep Learning (DL) overlooked by prior security research: time-series forecasting of financial predictions. Despite abundant efforts revealing the brittleness of DL models to adversarial perturbations, such efforts hardly envisioned practical adversarial threat models and assessed their effects on a DL-powered algorithmic trading system (ATS).

In this work, we shed light on the vulnerability of ATS to adversarial perturbations launched by a constrained, but realistic, attacker. First, through an extensive literature review, we expose the limited attention given to DL security in the financial domain—which is naturally attractive for adversaries. Then, we formalize the concept of ephemeral perturbations (EP), which can be used to stage a novel type of attack tailored for DL-based ATS. Finally, we carry out an end-to-end evaluation of our proposed EP against a profitable ATS. Our results reveal that the introduction of small changes to the input stock-prices not only (i) induces the DL model to behave incorrectly—which is well-known; but also (ii) leads to the whole ATS to make suboptimal buy/sell decisions—which translate in a net-loss by the targeted organization. We will release our implementation.

(This is an extended abstract discussing ongoing work. The final paper can be found in our [CODASPY'25](https://www.giovanniapruzzese.com/publications/codaspy25) publication.)
 
