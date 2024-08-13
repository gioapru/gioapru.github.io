---
title: "When Adversarial Perturbations meet Concept Drift: an Exploratory Analysis on ML-NIDS"
collection: publications
permalink: /publications/aisec24
excerpt: 'What happens when two popular phenomena in ML security join forces?'
code: '[AISec24]'
date: 2024-08-06
venue: 'Workshop on Artificial Intelligence Security'
badge: <span class='badge badge-danger'>Workshop</span>
type: Workshop
authors: '<u>Apruzzese, G.</u>, Fass, A., & Pierazzi, F.'
citation: '<u>Apruzzese, G.</u>, Fass, A., & Pierazzi, F. (2024, October). "When Adversarial Perturbations meet Concept Drift: an Exploratory Analysis on ML-NIDS." In <i>2024 17th ACM Workshop on Artificial Intelligence Security (AISec)</i>. ACM.'
---
{% include base_path %}

<b>Abstract.</b> We scrutinize the effects of "blind" adversarial perturbations against machine learning (ML)-based network intrusion detection systems (NIDS) affected by concept drift. There may be cases in which a real attacker -- unable to access and hence unaware that the ML-NIDS is weakened by concept drift -- attempts to evade the ML-NIDS with data perturbations. It is currently unknown if the cumulative effect of such adversarial perturbations and concept drift leads to a greater or lower impact on ML-NIDS. In this "open problem" paper, we seek to investigate this unusual, but realistic, setting---we are not interested in perfect knowledge attackers.

We begin by retrieving a _publicly available_ dataset of documented network traces captured in a real, large (>300 hosts) organization. Overall, these traces include several years of raw traffic packets---both benign and malicious. Then, we adversarially manipulate malicious packets with "problem-space" perturbations, representing a _physically realizable attack_. Finally, we carry out the _first exploratory analysis_ focused on comparing the effects of our "adversarial examples" with their respective unperturbed malicious variants in concept drift scenarios. Through two case studies (a "short-term" one of 8 days; and a "long-term" one of 4 years) encompassing 48 detectors, we find that, although our perturbations induce a lower detection rate in concept-drift scenarios, some perturbations yield adverse-effects for the attacker in intriguing use-cases. Overall, our study shows that the topics we covered are an still an open problem which require a re-assessment from future research.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/aisec24/aisec24.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/aisec24/aisec24_cite.html" target="_blank" rel="noopener">Cite</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/hihey54/aisec24" target="_blank" rel="noopener">Code</a>