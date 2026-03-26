---
title: "I can't recognize (yet): Delayed Rendering to Defeat Visual Phishing Detectors"
collection: publications
permalink: /publications/eurosp26
excerpt: "We identify and systematically analyse a fundamental weakness of visual phishing detectors."
date: 2026-03-11
code: '[EuroSP26]'
venue: 'IEEE European Symposium on Security and Privacy'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Yuan, Y., Rado, C. A., <u>Apruzzese, G.</u>, Conti, M., & Mancini, L. V.'
citation: 'Yuan, Y., Rado, C. A., Apruzzese, G., Conti, M., & Mancini, L. V. (2026, Jul.) "I can`t recognize (yet): Delayed Rendering to Defeat Visual Phishing Detectors" In <i>IEEE European Symposium on Security and Privacy (EuroS&P) </i>.'
---
{% include base_path %}
<b>Abstract.</b> Phishing webpages are continuously polluting the Web. By impersonating real-and-trusted services, such malicious websites can deceive users, leading to credential theft or malware download. To cope with such a threat, plenty of countermeasures have been proposed and the most advanced techniques leverage machine-learning methods that infer whether a webpage is benign or not by inspecting its visual representation. The rationale is that a webpage that is (i) visually similar to that of a trustworthy website, but which is (ii) hosted on a domain different from that of such a website, is a clear sign of a phishing webpage. Yet, despite the demonstrated effectiveness of such detection methods, this class of defenses is, by design, susceptible to a specific kind of subtle-but-cheap timing-based attacks which---worryingly, and perhaps surprisingly---have never been investigated so far. Such an oversight questions the overall reliability of these defenses in the wild, and demands a dedicated treatment.

First, we show that timing-based evasion attacks have not been accounted for by prior work on visual phishing website detectors. Then, we elucidate the intrinsic vulnerability of these detectors: they can be bypassed by delaying the rendering of webpage elements. Practically, these detectors must compute a visual similarity score between a target webpage and a known legitimate one. This requires taking a "snapshot" of the target webpage before the similarity computation. Attackers can deliberately delay the rendering of key elements, such as the logo, so that these elements appear fully only after the snapshot has been taken. This simple tactic misleads the visual-similarity module, leading the system to incorrectly classify the phishing page as benign. We empirically show that state-of-the-art detectors can be completely defeated (detection rate dropping from 100% to 0%) by employing easy-to-apply "problem-space" techniques such as pixelation. We also carry out a user study, evaluating the effectiveness of these attacks against real humans, and find that end users are unable to reliably identify our "perturbations" (p<0.05). Finally, we propose mitigations, including a browser-extension that, without making any call to remote services, warns users that they may have landed on a phishing webpage. We release all of our resources.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/eurosp26/eurosp26.pdf" target="_blank" rel="noopener">Paper PDF</a> 
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/eurosp26/eurosp26_cite.html" target="_blank" rel="noopener">Cite</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://ieeexplore.ieee.org/" target="_blank" rel="noopener">IEEE Xplore</a>
<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/" target="_blank" rel="noopener">Artifact (Code)</a>
