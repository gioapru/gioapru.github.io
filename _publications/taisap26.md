---
title: "Misleading Large Language Models used (or misused) in Scientific Peer-Reviewing via Hidden Prompt-Injection Attacks"
collection: publications
permalink: /publications/taisap26
excerpt: 'We systematically analyse how, and why, LLMs can be misled in a peer-review context.'
date: 2026-03-15
code: '[TAISAP26]'
venue: "ACM Transactions on AI Security and Privacy"
badge: <span class='badge badge-success'><i class="fa fa-lightbulb"></i>Journal</span>
type: Journal
authors: 'Collu, M. G., Salviati, U., Confalonieri, R., Conti., M., <u>Apruzzese, G.</u> '
citation: 'Collu, M. G., Salviati, U., Confalonieri, R., Conti, M., & Apruzzese, G. (2026). Misleading Large Language Models used (or misused) in Scientific Peer-Reviewing via Hidden Prompt-Injection Attacks. <i>ACM Transactions on the Web</i>.'
---
{% include base_path %}
<b>Abstract.</b> Large Language Models (LLMs) are increasingly being integrated into the scientific peer-review process, raising new questions about their reliability and resilience to manipulation. In this work, we investigate the potential for hidden prompt injection attacks, where authors embed adversarial text within a paper's PDF to influence the LLM-generated review. We begin by formalising three distinct threat models that envision attackers with different motivations—not all of which implying malicious intent. For each threat model, we design adversarial prompts that remain invisible to human readers yet can steer an LLM's output toward the author's desired outcome. Using a user study with domain scholars, we derive four representative reviewing prompts used to elicit peer reviews from LLMs. We then evaluate the robustness of our adversarial prompts across (i) different reviewing prompts, (ii) different commercial LLM-based systems, and (iii) different peer-reviewed papers. Our results show that adversarial prompts can reliably mislead the LLM, sometimes in ways that adversely affect a “honest-but-lazy” reviewer. Finally, we propose and empirically assess methods to reduce detectability of adversarial prompts under automated content checks.

<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/taisap26/taisap26.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/taisap26/taisap26_cite.html" target="_blank" rel="noopener">Cite</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://dl.acm.org/doi/10.1145/3803804" target="_blank" rel="noopener">ACM Digital Library</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/Collins-115/TAISAP26" target="_blank" rel="noopener">Code</a>  