---
title: "The Impact of Emerging Phishing Threats: Assessing Quishing and LLM-generated Phishing Emails against Organizations"
collection: publications
permalink: /publications/asiaccs25
excerpt: 'We (are the first to) carry out a large-scale and cross-organizational user study on the effectiveness of quishing and LLM-written phishing emails (spoiler alert: they work very well).'
code: '[AsiaCCS25]'
date: 2025-08-29
venue: 'ACM Asia Conference on Computer and Communications Security'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Weinz, M., Zannone, N., Allodi, L., & <u>Apruzzese, G.</u>'
citation: 'Weinz, M., Zannone, N., Allodi, L., &  Apruzzese, G., (2025, August). "The Impact of Emerging Phishing Threats: Assessing Quishing and LLM-generated Phishing Emails against Organizations." In <i>2025 20th ACM Asia Conference on Computer and Communications Security (AsiaCCS)</i>.'
---
{% include base_path %}
<b>Abstract.</b> Modern organizations are persistently targeted by phishing emails. Despite advances in detection systems and widespread employee training, attackers continue to innovate, posing ongoing threats. Two emerging vectors stand out in the current landscape: QR-code baits and LLM-enabled pretexting. 
Yet, little is known about the effectiveness of current defenses against these attacks, particularly when it comes to real-world impact on employees. This gap leaves uncertainty around to what extent related countermeasures are justified or needed. Our work addresses this issue.

We conduct three phishing simulations across organizations of varying sizes---from small-medium businesses to a multinational enterprise.
In total, we send over 71k emails targeting employees, including: a "traditional" phishing email with a click-through button; a nearly-identical "quishing" email with a QR code instead; and a phishing email written with the assistance of an LLM and open-source intelligence. 
Our results show that quishing emails have the same effectiveness as traditional phishing emails at luring users to the landing webpage---which is worrying, given that quishing emails are much harder to identify even by operational detectors. 
We also find that LLMs can be very good "social engineers": in one company, over 30\% of the emails opened led to visiting the landing webpage---a rate exceeding some prior benchmarks. Finally, we complement our study by conducting a survey across the organizations' employees, measuring their ``perceived'' phishing awareness. Our findings suggest a correlation between higher self-reported awareness and organizational resilience to phishing attempts.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/asiaccs25/asiaccs25.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/asiaccs25/asiaccs25_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://doi.org/10.1145/3708821.3736195" target="_blank" rel="noopener">ACM Digital Library</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{base_path}}/talks/asiaccs25" rel="noopener">Talk</a>