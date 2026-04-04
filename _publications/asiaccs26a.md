---
title: '"What is the Problem Space?" Defining Host-space Adversarial Perturbations against Network Intrusion Detection Systems'
collection: publications
permalink: /publications/asiaccs26a
excerpt: 'Changing one character of one command can lead to a complete bypass.'
code: '[AsiaCCS26a]'
date: 2026-04-01
venue: 'ACM Asia Conference on Computer and Communications Security'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: "Verkerken, M., D'hooge, L., Volckaert, B., De Turck, Filip, & <u>Apruzzese, G.</u>"
citation: 'Verkerken, M., D`hooge, L., Volckaert, B., De Turck, Filip, & Apruzzese, G.,  (2026, June). ""What is the Problem Space?" Defining Host-space Adversarial Perturbations against Network Intrusion Detection Systems". In <i>2026 21st ACM Asia Conference on Computer and Communications Security (AsiaCCS)</i>.'
---
{% include base_path %}
<b>Abstract.</b> Network Intrusion Detection Systems (NIDS) are now increasingly leveraging Machine Learning (ML) techniques to detect malicious network activities. Numerous papers have scrutinized the security of ML-based NIDS (ML-NIDS) by testing them against various attacks involving adversarial perturbations. The findings were oftentimes worrying: by making imperceptible changes to a given input, powerful ML models would be bypassed. In this context, we took a step back and wondered: where (i.e., in what "space") have these perturbations been applied?

We argue that real-world adversaries can apply adversarial perturbations only by operating on the hosts they can control---a concept which we define as _host-space perturbations_. To some, such an observation may seem trivial. And yet, through a systematic literature review (n=316), we found that prior work applied perturbations by manipulating pre-collected datapoints (e.g., a packet _captured by the router_, or a network flow _analysed by the ML-NIDS_). Such operations, while not impossible, may be outside the reach of an attacker who can only control some (unprivileged) hosts in a network. Hence, to demonstrate how to craft host-space perturbations and study some of their effects, we experimented on well-known benchmarks and a real-world network. We show that ML-NIDS that can detect the SSH-bruteforcing attempts launched via a given command string cannot detect any attempt launched by changing a single character of such a string. We then examined how such a minuscule change in the "problem space" (i.e., the attacker's host) can lead to devastating effects on the "feature space". We derive lessons learned on how to practically assess host-space perturbations. Our stance is that the security of ML-NIDS should be re-assessed.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/asiaccs26a/asiaccs26a.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/asiaccs26a/asiaccs26a_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://doi.org/10.1145/3779208.3807482" target="_blank" rel="noopener">ACM Digital Library</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/idlab-discover/HsP" rel="noopener">Code</a>