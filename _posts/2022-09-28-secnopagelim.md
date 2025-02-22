---
title: 'SecNoPageLim: Unlimited pages for Appendices and References'
date: 2022-09-28
excerpt: 'My opinion on why we need them.'
permalink: /posts/2022/secnopagelim
tags:
  - research
  - peer-review
---

This post discusses some of my (personal!) viewpoints on why having more venues with "unlimited" pages for _references_ and _appendices_ can improve the current peer-review process. For reference (pun intended☺), I invite you to look at this website, which I created a few hours ago: [SecNoPageLim](https://secnopagelim.github.io/). 



## Backstory

The [SecNoPageLim](https://secnopagelim.github.io/) website was inspired by the "Rump Session" of [7th IEEE European Symposium on Security and Privacy](https://www.ieee-security.org/TC/EuroSP2022/program.html) (held on Wednesday, June 8th, 2022).

In particular, during such Rump Session, I gave a talk on the length of papers in cybersecurity conferences. Funnily enough, [David Evans](https://www.cs.virginia.edu/~evans/) (co-chair of EuroS&P22) at the beginning of the session, said that "the ideal length of a paper is 0 pages", which is something to which I agree with---in principle. Yet, the discussion was very engaging (I believe it lasted nearly 1 hour), and a lot of interesting points were raised by many participants (h/t to all those who contributed!).

In what follows, you will find what is---in a sense---a summary of the discussion that transpired during such Rump Session at EuroS&P22, which is further enriched with my own viewpoints.

## My viewpoint

Let me elucidate the reasons why I believe that both **references** and **appendices** should be unlimited. I will separately address each of these, providing my perspective both as an "author" (i.e., the one who _writes_ a paper) and as a "reviewer" (i.e., the one who _reads_ and _evaluates_ a paper).


### Appendices
Research in cybersecurity---and in computer science in general---is becoming increasingly more demanding. Finding "novelty" often requires to reproduce prior work, sometimes by developing _original code_, or by creating _ad-hoc datasets_, or perhaps a mix of both (thereby realizing entirely new testbeds). All such operations (i) require intensive _human effort_ and (ii) are very _lengthy to describe_ in a paper, but (iii) are **not a contribution**. Hence, what should an author do?

* Skip them when describing the experimental methodology!
  * But what about reproducibility and transparency?  
* Carefully describe them in the main paper!
  * Unfortunately, the main paper is subject to _page limitations_.
* Do not describe them in the paper, but report them in the artifact (if the venue has an artifact evaluation committee)!
  * Unfortunately, the artifact is evaluated _after_ a decision on the paper has been made.
* Provide a link to an (anonymous) repository/resource that includes all such information!
  * Would the reviewers read it? Most reviewers read on hard-paper, and unless they were made aware of such "extra" resources, such information would not be included in the printed version. Moreover, opening a link, extracting and navigating some folders, finding the correct files---all of these are arguably annoying operations.

A (possible) solution to all the above is by removing the limit to the length of _appendices_ that can be included in a paper---at least at the time of submission. The idea is providing a "shield" to authors, so that they can focus on describing their main contribution while transparently providing all technical details related to a given implementation (or a theoretical proof). At the same time, reviewers **can** inspect such details---if they believe it necessary; or, at the very least, they should not state that "the paper does not provide enough details" in their reviews. 

As an **author** it is disappointing:
* when you have to "cut" some technical details simply because the page limits do not allow you to do it feasibly---and then seeing your paper "rejected" because of "lack of details";
* when your paper is "rejected" because a reviewer complained about the "lack of details", despite such details being included in the appendix.

(both circumstances happened to me, and it was incredibly frustrating)

As a **reviewer**, however, I acknowledge that it is discouraging when you open a paper and you see 30 pages (in a DC template), 15 of which being of appendices... and even more-so when such appendices include content outside your main area of expertise.
The reviewer, however, _can skip the appendix_: in this case, the reviewer should---_before_ submitting their review---check if some shortcomings outlined in their review are addressed in the appendix. If this is true, then the reviewer can either:
* read the corresponding part of the appendix, and check its correctness (perhaps the reviewer was genuinely interested in having a question answered!);
* remove the shortcoming from their review, which would be unfounded (and perhaps reconsider the whole review in light of such change);
* fairly state that the shortcoming may be unfounded by admitting that it may have been discussed in the Appendix, which the reviewer did not fully read---either for lack of time, or of domain expertise (both of which are legitimate reasons!).

(I strive to always do one of the above when I review a paper)

### References

The amount of papers that are accepted every year is constantly increasing (see [here](http://jianying.space/conference-ranking.html) for some trends). For instance, the number of papers accepted at IEEE S&P was 17 in 2005, 55 in 2015, and 147 in 2022.
Such abundance implicitly leads to _more related work_, which should be discussed---and cited---in any given paper. And such citations "take space". 

As an **author**, it is discouraging when a reviewer criticizes the lack of "crucial references" when you were fully aware of their relevance, but which you did not include because you did not have the space for them. (on a personal note, I do not understand why some venues accept SoK papers, but impose limits on the length of references.)

As a **reviewer**, it may appear daunting to look at a paper and see hundreds of references. However---personally---I believe that this is a "fake" issue: a reviewer should not look at the references, but at the main text. Then, on the basis of where (and how) such references are used in the text, a comment can be made.

### Takeaway

I believe that there is much to gain (and little to lose) by having more venues to accept papers with "unlimited" references and appendices. If some papers end up being "very long", then a possible workaround is mentioning it at the time of submission (e.g., prepending "LONG" in the title, as done at [FSE](https://fse.iacr.org/2022/files/cfp_21.pdf)), so that reviewers are informed. I acknowledge that some venues may have constraints due to their editorial proceedings: in these cases, however, it is still possible to impose a constraint only for the final version of the paper (this is what is done, e.g., by [USENIX SEC](https://www.usenix.org/sites/default/files/sec23_cfp_092722.pdf)). 

Bottom line: the purpose is to improve the _peer-review_. This solution is obviously not perfect, but (IMHO) it is a step towards a more constructive and fair peer-review process.  




