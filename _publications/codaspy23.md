---
title: "Attribute Inference Attacks in Online Multiplayer Video Games: a Case Study on Dota2"
collection: publications
permalink: /publications/codaspy23
excerpt: 'We discovered a privacy issue affecting millions of video gamers!'
code: '[CODASPY23]'
date: 2022-12-18
venue: 'ACM Conference on Data and Application Security and Privacy'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Tricomi, P. P., Facciolo, L., <u>Apruzzese, G.</u>, & Conti, M.'
citation: 'Tricomi, P. P., Facciolo, L. Apruzzese, G., & Conti, M. (2023, April). "Attribute Inference Attacks in Online Multiplayer Video Games: a Case Study on Dota2." In <i>2023 13th ACM Conference on Data and Application Security and Privacy (CODASPY)</i>. ACM.'
---
{% include base_path %}
<b>Abstract.</b> Did you know that over 70 million of Dota2 players have their in-game data freely accessible? What if such data is used in malicious ways? This paper is the first to investigate such a problem.

Motivated by the widespread popularity of video games, we propose the first threat model for Attribute Inference Attacks (AIA) in the Dota2 context. We explain how (and why) attackers can exploit the abundant public data in the Dota2 ecosystem to infer private information about its players. Due to lack of concrete evidence on the efficacy of our AIA, we empirically prove and assess their impact in reality. By conducting an extensive survey on ∼500 Dota2 players spanning over 26k matches, we verify whether a correlation exists between a player’s Dota2 activity and their real-life. Then, after finding such a link (𝑝 < 0.01 and 𝜌 > 0.3), we ethically perform diverse AIA. We leverage the capabilities of machine learning to infer real-life attributes of the respondents of our survey by using their publicly available in-game data. Our results show that, by applying domain expertise, some AIA can reach up to 98% precision and over 90% accuracy. This paper hence raises the alarm on a subtle, but concrete threat that can potentially affect the entire competitive gaming landscape. We alerted the developers of Dota2.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/codaspy23/codaspy23.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/codaspy23/codaspy23_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://dl.acm.org/doi/abs/10.1145/3577923.3583653" target="_blank" rel="noopener">ACM Digital Library</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/hihey54/Dota2AIA" target="_blank" rel="noopener">Code</a>  
