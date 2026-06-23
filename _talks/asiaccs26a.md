---
title: '“What is the Problem Space?” Defining Host-space Adversarial Perturbations against Network Intrusion Detection Systems'
collection: talks
type: "Conference"
excerpt: 'Changing one character of one command can lead to a complete bypass.'
badge: <span class='badge badge-primary'>Conference</span>
permalink: /talks/asiaccs26a
venue: "ACM Asia Conference on Computer and Communications Security"
date: 2026-06-03
location: "Bangalore, India"
---
{% include base_path %}

This talk is the natural extension of our <a href="{{base_path}}/publications/satml26a" rel="noopener">SaTML'26 paper</a>, which presented ConCap, a tool for automatically generating and labeling NetFlow data. Originally, these two contributions were in the same paper. However, we had really a hard time with reviewers: some liked ConCap but did not appreciate the "Host-space Perturbations" (HsP) contribution; others thought the opposite. Eventually, we decided to split the paper in two---and it appears that this was the right way to go.

What we do in this paper is quite simple: we show that by minimally altering a command to launch a network-related attack, one can completely defeat ML-driven classifiers that detect malicious NetFlows. We show that even a single character change can lead to this---without altering the overarching goal of the attacker or the involved hosts. We argue such tactics, which can only be observed by operating on the host, are much more viable than traditional "adversarial perturbations" applied in the feature space. We hope future research can better examine this complementary way to evade ML-driven NIDS.



<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/talks/asiaccs26b.pdf" target="_blank" rel="noopener">Slides</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://asiaccs2026.cse.iitkgp.ac.in/#" target="_blank" rel="noopener">Venue</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{base_path}}/publications/asiaccs26b" rel="noopener">Paper</a>