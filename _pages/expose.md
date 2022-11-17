---
layout: archive
title: "Expose"
permalink: /expose
author_profile: true
---

{% include base_path %}

This page is dedicated at all MSc. students at the University of Liechtenstein who are currently working on a thesis with a strong focus in Computer Science, and who also have some interest in pursuing a career in research or academia (i.e., they aim to go for a PhD). 

## Goal of the Expose
In principle, the Expose (at UniLi) has one goal: show that the student will be able to make a good thesis. To this purpose, the Expose should demonstrate that the student:
* is aware of the state-of-the-art;
* understand what is the problem / research question tackled by the thesis;
* has a generic idea of how to carry out the activities that will (hopefully) fulfill the goal of the thesis.

## Structure of the Expose
You can use the guidelines of UniLi for the generic structure of an Expose, and/or adhere to the LaTeX template that has already been provided to you. At a high-level, there are four "crucial" sections that allow to determine whether a student will (or will not) be able to do a good job:
* The **Introduction**. Here, the student should motivate *what* will be done in the thesis, and *why* it is relevant
* The **Background / Related Work**. Here, the student should show that they know what has been done in this area (i.e., Background), and should also show how the thesis differ from such prior work (i.e., Related Work)
* The **Problem Statement** (or "Contribution", or "Research Question"). Here, the student should explicitly mention what is the expected contribution of the thesis.
* The **Method**. Here, the student should explain how the problem mentioned in the previous section is expected to be addressed.

## Considerations on the Expose
It is impossible to know with so much advance how the thesis will turn out. Hence, while you should "do your best" to write a good introduction and to formulate the specific problem tackled by your thesis, chances are that things will go much different than expected _during the thesis_.

However, it is unlikely that the background / related work will change: unless you change your thesis completely, your topic will remain the same.

Hence, to maximize the use of your time, I recommend to _spend a lot of effort in writing a good Background/Related Work section_! Doing this has the following benefits:
* Reducing your future workload. You can "almost" copy-paste this entire section when you will have to write your final thesis.
* Allowing you to better understand the state-of-the-art. This will implicitly turn into a better Introduction (for the Expose, which you have to write _last_).
  * It will also implicitly provide a nice "guide" of what you will have to do during your project (e.g., maybe some paper did something similar and very well, so you can avoid doing that! Or, some paper did something similar but very poorly, so you can easily improve it!)
* Assist your supervisor, who can not only see "if the student did a good job", but also fill some "knowledge gaps" that the supervisor has (remember: supervisors are humans!)



## Writing a good Section 2

The most common mistake that students (at all levels) make when writing Section 2 of (any) scientific paper is that they simply "summarize prior work", sometimes by providing redundant information. **This is not what Section 2 is for!**

We can distinguish two parts of Section 2:
* Background. This part focuses on providing the _essential_ elements required to understand the rest of the Expose/Thesis. Note that I wrote "essential": whoever is going to read your thesis is _an expert_, so you do not need to write everything that mankind has done in the last 10000 years!
* Related Work. This part focuses on _distancing_ your thesis with existing work. It is very unlikely that you will be addressing a problem that has "never" been tackled before: typically, substantial papers have focused on very similar problems (if not the very same one!). Hence, your goal here is _stating how your work is "better" than previous ones **to address the problem of your thesis**_!

You should use Section 2 to your advantage: instead of merely "explaining what is (already) known", you should use what is known to point out "what is not (yet) known"!

### What "not to do"

Here are some poor attempts at writing the Background part of Section 2:
* Mentioning papers that have nothing to do with your thesis "just to fill space" (e.g., you do not need to describe what a "computer" is)
* Citing works that are not peer reviewed. This is not a "dogma", but if you need to provide "background" you should use a solid basis. Try considering papers that have "a lot of" citations.
* The tone should be that of a "coherent description", and not a "list". You should not state ```The authors of [X] did A; those of [Y] did B```, but rather create an natural discussion that sets-up the stage of your paper (e.g., ```The fundamental principles of A is that...[X]. It is, however, important to consider also B [Y]``` or also ```According to previous literature [X], A can be seen as...```)
* Plagiarism (I'm not even going to explain this)

Here are some poor attempts at writing the Related Work part of Section 2:
* Doing a list of ```[X] did A```, without mentioning _why_ or _how_ such works are different from yours.
* Stating things that are wrong. If you state ```[X] did A``` but in reality "[X] did B", then you're in a very bad spot! Always double (or triple!) check when you want to critique something!
* Forgetting to mention crucial works. Your goal is tell the reader that "there is a problem"; but if the reader responds that "this paper [Z] solved the problem and you did not cite it here" then you've already lost all credibility.

### What "could be done"

It is recommended to enhance the "Background" section with schemas or illustrations <span class="footnote"><a style="color:firebrick">[a]</a><span class="footnote_content">I recommend using [Draw.io](https://draw.io)</span></span>. Make them yourself -- but if they are similar to those made by prior work do cite the original source.

For the "Related Work", you can make a Table
 <span class="footnote"><a style="color:firebrick">[b]</a><span class="footnote_content">A good example of this is Table 4 of my [SpacePhish paper](https://www.giovanniapruzzese.com/files/papers/acsac22/acsac22.pdf).</span></span> that lists all the closest works, and explicitly states what they did "well" and what they did "not-so-well" _in the context of the goal of your thesis_. The intention is showing the reader that the state-of-the-art does not allow to answer your "research question" (because not a single work did "well" everything that is "needed to answer your research question").

Of course, the Table mentioned above should not include every paper that has been written up until today! Focus on the most relevant ones. In general, it is good practice to have from 10 to 30 papers in such a table.

## Generic Tips

The following are some generic tips that apply for "any" kind of scientific document (and an Exposé is definitely a precursor of one such document).

* Value, value, value. It's irrelevant if you tackle a "novel" problem, or if you find a "new" research question, if you cannot communicate _what **value** is there_ in having such a problem solved!
* Readers first. Any scientific document _is not about what's in your mind_. Your goal is to **change other people's minds**, and you are unlikely to do so if you present everything according to _your thought process_! 
  * It's the readers who will determine the value of your work, and such value depends on how they perceive your work --- in other words, present your ideas in a way that the readers can understand!
* There are no rules. Your goal is simple: have "others" accept the fact that you changed the way they see the world. How you do this it's up to you.
* In general, at the end of Section 2 the reader should have understood that (i) there is a _problem_ (ii) which imposes a _cost_ on them (iii) and that your thesis is _valuable_ because it will solve such a problem. 
  * Avoid having Section 2 occupy more than 20% of your document (excluding references) [of course, the Expose is a special case].
* Know your strengths, but also your weaknesses. Do you do something _better_ than another work, and can you _prove_ it? Then state it. Is there something that you cannot do? Then acknowledge it as a limitation.
  * This point should not pertain to your expose, but it's still good to keep in mind.
* Take inspiration from good papers. Do you see a nice schematic, or a nice table? Use it (not the same one, just the style).
* Criticize with elegance. Do you know for a fact that a given paper has some limitations? Then state it, but in a "soft" way. 
  * Create "tension". Remember that people are more attracted by "problems" than by "positive" (or "neutral") statements.
* When writing in LaTeX, remember to use Google if you encounter problems. In 99% of the cases, the solution is already there (you only need to search for it).
  * Also, put [Google Scholar](https://scholar.google.com/) on your bookmarks, and use that as your main source of literature search.
* I have (arguably) written a good amount of papers. **Read them** (typically, the most recent ones are the best ones). I'm not the best researcher, but they should still provide you a good foundation.
  * Also, if you find some figure/table to be of particular interest, just drop me a message and I'll give you the source code! 


### Fancy words

Below is a list of words that naturally "create tension", which you can use to build your argument and induce the reader into believing that "there is a problem, which your thesis will solve":

Anomaly, inconsistency, but, however, nevertheless, problem, contrast, on the contrary, instead, while/although, surprisingly, unfortunately, unclear, confusing, vague, flawed, incomplete, unrealistic, poor, struggle, over/under-whelming, (over)exaggeration, simplistic, over/under-estimation, unless, limited, overlook, neglect.
