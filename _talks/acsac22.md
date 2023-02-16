---
title: "SpacePhish: The Evasion-space of Adversarial Attacks against Phishing Website Detectors using Machine Learning"
collection: talks
type: "Conference"
excerpt: 'A joint effort with UniPD, casting light on some overlooked aspects of adversarial ML in the context of phishing website detection.'
badge: <span class='badge badge-primary'>Conference <i class="fa fa-code"></i></span>
permalink: /talks/acsac22
venue: "Annual Computer Security Applications Conference"
date: 2022-12-07
location: "Austin, TX, USA"
---
{% include base_path %}

Giving (and making) this presentation was really fun. I decided to start with a thought-provoking question ("do you know of any adversarial ML attack that has an effectiveness of only 3%?"), and I did not expect to receive any comment on it _during_ my talk. Surprisingly, one of the attendees interrupted me, asking "what is the point of describing such an attack?" -- which was the entire point behind our paper! 

Indeed, the most important takeaway of this paper is that it is possible to craft adversarial ML attacks that, despite having an intrinsically low effectiveness (around 3%), are _extremely cheap_ (only 7 lines of code) and that are also dangerous---given the high number of phishing webpages created every day. With these premises, we argue that real phishers are more inclined to opt for these "cheap" strategies over more "expensive" ones previously proposed in literature.

In a sense, this paper tells the importance of _context_ (phishing, in our case) w.r.t. the "real" risk of adversarial ML attacks. I must commend the other main author, [Ying Yuan](https://sites.google.com/view/yingyuan/home), for the insane effort she put in the experiments (which allowed us to obtain a "Reusable" artifact!)



<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/talks/acsac22.pdf" target="_blank" rel="noopener">Slides</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.acsac.org/2022/" target="_blank" rel="noopener">Venue</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{base_path}}/publications/acsac22" rel="noopener">Paper</a>