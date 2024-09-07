---
title: "It Doesn't Look Like Anything to Me: Using Diffusion Model to Subvert Visual Phishing Detectors"
collection: publications
permalink: /publications/sec24
excerpt: "We design a new attack that bypasses 3 SOTA visual-based phishing website detection systems in an end-to-end fashion, as well as end-users (humans)"
date: 2024-08-15
code: '[SEC24]'
venue: 'USENIX Security Symposium'
badge: <span class='badge badge-primary'>Conference</span>
type: Conference
authors: 'Hao, Q., Yuan, Y., Diwan, N., <u>Apruzzese, G.</u>, Conti, M., & Gang, W.'
citation: 'Hao, Q., Yuan, Y., Diwan, N., <u>Apruzzese, G.</u>, Conti, M., & Gang, W. (2024, August). "It Doesn`t Look Like Anything to Me: Using Diffusion Model to Subvert Visual Phishing Detectors." In <i>USENIX Security Symposium (SEC)</i>.'
---
{% include base_path %}
<b>Abstract.</b> Visual phishing detectors rely on website logos as the invariant _identity indicator_ to detect phishing websites that mimic a target brand's website. Despite their promising performance, the robustness of these detectors is not yet well understood. In this paper, we challenge the invariant assumption of these detectors and propose new attack tactics, LogoMorph, with the ultimate purpose of enhancing these systems. LogoMorph is rooted on a key insight: users can neglect _large_ visual perturbations on the logo as long as the perturbation preserves the original logo's semantics. We devise a range of attack methods to create semantic-preserving adversarial logos, yielding phishing webpages that bypass state-of-the-art detectors. For text-based logos, we find that using alternative fonts can help to achieve the attack goal. For image-based logos, we find that an adversarial diffusion model can effectively capture the style of the logo while generating new variants with large visual differences. Practically, we evaluate LogoMorph with controlled experiments and test the resulting adversarial webpages against various visual phishing detectors end-to-end. User studies (n=150) confirm the effectiveness of our adversarial phishing webpages on end users (with a detection rate of 0.59, barely better than a coin toss). We also empirically assess potential countermeasures and discuss lessons learned.


<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/sec24/sec24.pdf" target="_blank" rel="noopener">Paper PDF</a><a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="{{ base_path }}/files/papers/sec24/sec24_cite.html" target="_blank" rel="noopener">Cite</a><a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://github.com/gyNancy/Visualphish_public" target="_blank" rel="noopener">Artifact (Code)</a>