---
title: '“bot lane noob” Towards Deployment of NLP-based Toxicity Detectors in Video Games'
collection: publications
permalink: /publications/esorics26
excerpt: "To fight toxicity, we manually labeled an (open-source) dataset of toxic LoL matches, and show its utility for NLP applications."
date: 2026-03-19
code: '[ESORICS26]'
venue: 'European Symposium on Research In Computer Security'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Ave, J., Pekaric, I., Frohner, M., <u>Apruzzese, G.</u>'
citation: 'Ave., J., Pekaric, I., Frohner, M., & Apruzzese, G. (2026, Sept.). "“bbot lane noob” Towards Deployment of NLP-based Toxicity Detectors in Video Games." In <i>European Symposium on Research in Computer Security (ESORICS)</i>.'
---
{% include base_path %}
<b>Abstract.</b> 
Toxicity and harassment are widespread in the video-gaming context. Especially in competitive online multiplayer scenarios, gamers oftentimes send harmful messages to other players (teammates or opponents) whose consequences span from mild annoyance to withdrawal and depression. Abundant prior work tackled these problems, e.g., pointing out the negative effects of toxic interactions. However, few works proposed countermeasures specifically developed and tested on textual messages sent during a match---i.e., when the "harassment" actually occurs. We posit that such a scarcity stems from the lack of high-quality datasets that can be used to devise "automated" detectors based on natural-language processing (NLP) and machine learning (ML), and which can -- ideally -- mitigate the harm of toxic comments during a gaming session.

This work provides a foundation for addressing the problem of toxicity and harassment in video games. First, through a systematic literature review (n=1,039), we provide evidence that only few works proposed ML/NLP-based detectors of toxicity/harassment during live matches. Then, to foster more practical research in this domain, we partner-up with 8 expert League of Legend (LoL) players and create a fine-grained labelled dataset, L2DTnH, containing 1.4k toxic and 13.8k non-toxic messages exchanged during LoL matches. We use L2DTnH to develop an ML-based detector that we then empirically show outperforms general-purpose and state-of-the-art toxicity detectors reliant on NLP. Finally, to further demonstrate the practicality of our resources, we test our detector on game-related data beyond that included in L2DTnH; and we develop a Web-browser extension that flags toxic content in Webpages---without making any query to third-party servers owned by AI companies. We publicly release all of our resources. Our contributions pave the way for more applied research devoted to fighting the spread of toxicity and harassment in video games. 



<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/esorics26/esorics26.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/esorics26/esorics26_cite.html" target="_blank" rel="noopener">Cite</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://link.springer.com/chapter/" target="_blank" rel="noopener">SpringerLink</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/irdin-pekaric/esorics26_toxicity/" target="_blank" rel="noopener">Artifact (Code)</a>
 
