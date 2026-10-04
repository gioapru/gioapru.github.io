---
title: "Misleading Large Language Models used (or misused) in Scientific Peer-Reviewing via Hidden Prompt-Injection Attacks"
collection: talks
type: "Talk"
excerpt: 'My first keynote talk, given to four workshop simultaneously!'
badge: <span class='badge badge-warning'>Talk</span>
permalink: /talks/esorics26
venue: "European Symposium On Research In Computer Security"
date: 2026-09-18
location: "Rome, Italy"
---
{% include base_path %}

This was the first time I gave a keynote speech---and it was quite-a-unique experience. Indeed, this speech was _shared_ across four workshops simultaneously: [ADND](https://adnd.work/program_2026/), [HumSec](https://humsec26.github.io/), [HotDiSec](https://hotdisec.github.io/website_2026/program/), and [RAISE](https://raise-workshop.github.io/). I must thank all the organizers of these workshops for considering me as a keynote speaker for their events! Hopefully, the talk (which I believe to be the best version of [the ones I gave previously](https://giovanniapruzzese.com/talks/serics26) on the same subject) has been appreciated by the audience!


**Abstract.** Large Language Models (LLMs) have revolutionized many aspects of our society. Many tasks encompassing document summarization or autonomous content generation can now benefit from the capabilities of LLMs. Among these, a domain in which LLMs are receiving increasing attention is that of scientific peer reviewing. Yet, usage of LLMs in this context must be done with due care: LLMs have certain blind spots which, if exploited, can lead to detrimental effects to the human requesting the service of an LLM.
In this talk, Giovanni will outline the reasons why the author of a scientific paper may want to mislead an LLM tasked to review a given paper. Based on these reasons, He will then explain ways in which one can reach their goal via "hidden prompt injections". Finally, He will discuss the results of a large-scale systematic analysis wherein they studied the impact of prompt-injection attacks against commercial LLMs (e.g., ChatGPT, Gemini). In doing so, He will also outline potential countermeasures---as well as counter-countermeasures. The takeaway is that blind reliance on LLMs for peer-review duties is strongly discouraged, and human oversight is still necessary.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/talks/esorics26.pdf" target="_blank" rel="noopener">Slides</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="[https://ssie.dei.unipd.it/technical-program-ssie-2026-track-1/](https://sites.google.com/di.uniroma1.it/esorics2026/program/workshop-schedule)" target="_blank" rel="noopener">Venue</a>