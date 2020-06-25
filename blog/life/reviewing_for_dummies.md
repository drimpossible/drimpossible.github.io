---
title: Reviewing for Dummies
author: drimpossible
layout: post
permalink: "/blog/life/reviewing_for_dummies/"
categories:
- reviews
tags:
- Life
- Community
date: 2019-12-26 00:00:00 +0000
---

One important aspect of research is reviewing, aka, how to evaluate a research paper to guide writing of my research papers. I recently reorganized [2] to form a review guideline which I actively refer for ensuring decent evaluation of papers, given below.

## How to evaluate a paper?

Evaluate aspects of paper and give concrete feedback to make the work better:

* Within your area of expertise. If not, better return the paper.
* A reasonably important problem is attacked, and method of attack is well motivated.
* Claims are new and unambiguously stated.
* Claims address the primary issue targeted.
* Acknowledgement is given to the existing body of work, and differences with proposed work are clear.
* Methodology implements the main claims appropriately and exhaustively.
* Results are clearly and logically presented, justified by the data presented.
* The improvements can be attributed to the method and not some other change.
* Results presented have been interpreted correctly and all interpretations considered.
* The claims do not go too far compared to the evidence presented.

Inutitive guidelines:

* Is it useful to you (as a proxy for the community)? Do the claims make sense intuitively (are they too good to be true)?
* How complex is the presented model? Is the complexity justified?
* Ensure that the results are not too preliminary or too speculative, but at the same time try to not block innovative new research and theories.
* If your expertise does not cover all aspects of the article, only respond to perspectives you can contribute and state it in the review. It's silly to pretend to be an expert.

## Organizing the review aspects: A typical review structure

A review would typically consist of 3 parts: (i) Summary (ii) Positives and Negatives (iii) Overall.

The summary: It is for the area chair to get an independent assessment of the crux of the contribution. Your aim is to summarize the contributions you find valuable from your perspective on the field and describe why the contributions proposed teach something valuable. The summary should be an independent assessment, absolutely not be a restatement of the abstract of the paper. This also enables better assessment of the work, when reviewers who have different angles approach a given piece of work. Also, if you can't distill the ideas down then you haven't really understood the paper.

Positives: It should detail to the area chair whats aspects from the above list are contributed in the paper, aka. how does it add value -- interesting ideas that are experimentally validated, new tools, impressive results, creative idea, along with an insightful organization of related literature?  A good intuition of things to include in positives is what can someone interested in the topic learn from the paper?  

Negatives: What detracts from the contributions? Does the paper lack controlled experiments to validate the contributions? Are there misleading claims or technical errors? Is it possible to understand (and ideally reproduce) the method and experimental setups by reading the paper?

Overall: is where you consider how you weighed the positives and negatives in reaching to your final score.

### Inadequencies people have got tired telling reviewers

There are some "dont's" which have typically seen.

* Vague criticisms are unacceptable. "Show your work" by pointing to specific figures, paragraphs, or results for each major issue; use references from previous literature to back up your claims and be concrete about the problems. 
* Using a numbered list of points and some score/tag of the influence of the point to your recommendation helps the author(s) respond better.
* Make sure that your review is constructive and not offensive like insulting criticism or sarcasm. Rule of thumb: avoid using terms like "the author(s)", "they", "them", "you", or "he/she", since it's often taken personally.
* Minor issues should be seperated from negatives. Examples of minor issues include simulations that miss some cases, figures that are missing information, or the paper has extraneous results that aren't relevant to the claims being made.
* Typos are not minor issues or major issues. It is not your responsibility to find them.
* If there are a huge number of typos then that may be stated as a minor issue. If the paper is completely unreadable then that is a major issue. Completely unreadable means you could not follow the paper even after ignoring all typos.
* You should not ask authors to restructure the paper, change the message of the paper, or make them do something that wasn't in the scope of the original work. Simply point out shortcomings in the current version.
* Asking citations to a bunch of your papers and requesting for experiments/simulations that are unnecessary to justify the main points in the paper are probably two common failure modes that you should avoid.


## Writing guidelines

Remember that this is a professional document. You get no bonus points for being nitpicky, verbose, or long. Some guidelines [2]:

* Be concise - Nothing extraneous
* Be precise - State specific problems with the manuscript, be concrete!
* Be constructive - State how problems you found can be addressed by authors
* Be polite - Focus on real issues rather than pet peeves.

## Decision

Your prior belief should be that the scientists in question are reasonable people who made efforts to be correct, thorough, transparent, and not exaggerate.

Strong reject is when you wouldn't accept the paper even if the authors amend major parts of their work. Typical reasons [2] include:

* Papers which have methods, design, results, or claims are blatantly false.
* Papers which have major flaws that cannot not be corrected.
* Papers which are clearly far inferior than the current state of the art or indentical (in idea and depth) to work(s) in past literature.
* Papers which propose methods or results which appear completely incorrect.
* Papers which are not readable by a person trying their best to understand it.

This category aids authors to stop wasting time on this idea and explore other directions. Overall, it's expected to help avoid at best wrong, at worst fraudulent results which mislead the field.

Weak reject is when you believe the paper suggests a good direction, but is currently not ready for publication. Typical reasons [2] include:

* Manuscript’s story is not cohesive and tightly reasoned.
* Critical missing pieces of information.
* Claims not supported by the data.
* Insufficient data.
* Statistically non-significant improvements.
* Contradictory data (Not self-consistent or disagree with the conclusions).
* Confirmatory data that adds little, if anything, to current understanding. (unless strong arguments for such repetition are made)

Typically weak rejections prevent works which kill follow-up by flagplanting ideas, unnecessarily non-standard setups, set bad precedent (weak paper X got in, so this one should too), at best end up wasting everyone’s time. 

Accepts are when a paper reasonably passes the above checks. Weak accepts are typically papers [1] provide incremental steps that expand the sum of the community’s knowledge significantly, adding bricks to the cathedral of knowledge; papers introducing useful tools; or papers of large interest to a subcommunity. Whereas strong accepts are major advances that will heavily impact the field; will be used by many people potential to be very significant; worthwhile for the whole community to hear about.

## Post-Rebuttal Reviewing

The authors typically have a chance to respond to your review. The re-review process is very straightforward:

* Authors addressed all your major issues reasonably - Accept
* Authors didn't address some critical major issues - Reject (Recommend resubmission with the outstanding issues)
* Additional experiment showed their method was incorrect/uninteresting - Reject

## Ethics

How to: Contact the program chairs with the paper number and explanation of the suspected problem. Review the paper as if there is no problem. Program chairs/ Editors will follow up on the issue, but it may take some time.


## Why write this?

Well, I could rather than link to [2] as major chunks of this guide are **directly sourced** from [2], with occasional lines borrowed from [1]. However, this guide was written with the objective to educate myself, and is targeted towards the applied ML/CV area (my research area). Secondly, I hope the restructuring is non-trivial, and expect the guide will evolve in the next few years, adding further distinctions. 

[1] [CVPR 2020 Review Guidelines](http://cvpr2020.thecvf.com/sites/default/files/2019-09/CVPRReviewerTutorial.pptx)
[2] [The Leek Group](https://github.com/jtleek/reviews)
