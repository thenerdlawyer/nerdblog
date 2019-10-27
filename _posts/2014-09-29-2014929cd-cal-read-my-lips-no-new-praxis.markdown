---
author: temjeito@yahoo.com
comments: true
date: 2014-09-29 14:23:37+00:00
excerpt: <p>The Central District of California invalidated patents asserted against
  a "who's who" of the video game industry, finding that although the patents-in-suit
  disclosed a novel concept vis-à-vis the prior art, the concept was claimed too broadly.
  Applying the Supreme Court's recent decision in <em>Alice Corp. Pty. Ltd. v. CLS
  Bank Int'l</em>, the court found that the patents claimed little more than the idea
  of having software do what previously had been done by human beings, without disclosing
  the specific method by which the software would accomplish that task.</p>
layout: post
slug: 2014929cd-cal-read-my-lips-no-new-praxis
title: 'C.D. Cal: "Read My Lips: No New Praxis"'
wordpress_id: 53
categories:
- Intellectual Property
- Patent
tags:
- Alice
- patent
- video games
---
McRO, Inc., d/b/a "Planet Blue," sued every name[^1] it could find on the backs of boxes at GameStop® claiming that they all infringed Planet Blue's patent[^2] for aligning 3D characters' lip movements and facial expressions with their speech. Last week, Judge Wu of the Central District of California granted the defendants' motion for judgment on the pleadings, finding that Planet Blue's patent disclosed a non-patentable abstract idea under *Alice*.[^3]

As disclosed in the prior art, the old-fashioned method of lip-synching was to model the mouth in a neutral position, and then in various non-neutral positions, usually corresponding with specific phonemes,[^4] called "morph targets." The animator then would assign a specific morph target to specific points along the speech track ("keyframes"), and software would interpolate the intermediate positions at each of the frames in between keyframes. Planet Blue contends that its patent discloses the "utiliz\[ation of\] a set of rules that determine the system\['\]s output comprising a stream or streams of morph weight sets[^5] when a sequence of timed phonemes or other timed data is encountered." In other words: the patent discloses the use of a rules-based system to automate the process of setting keyframes.

The court observed that the claims of the patent-in-suit, taken individually, described specific, tangible steps in a technological process that was not disclosed in the prior art. The court also noted that the defendants claimed that their own automated lip-synch methods were not covered by Planet Blue's patent. Said the court: "It is hard to show that an abstract idea has been preempted if there are non infringing ways to use it in the same field. Section 101 motions can place parties in unfamiliar and uncomfortable positions: here it is to the patentee's advantage to identify non infringing alternatives, and it is the accused infringer's advantage to posit the lack of any; the reverse of their positions at the infringement and damages stages of the case."

Nevertheless, the court found that "what the claim adds to the prior art is the use of rules, rather than artists, to set the morph weights and transitions between phonemes. **However, both of these concepts are specified at the highest level of generality.**"[^6] Significantly, the patent does not disclose the rules to be used. Rather, the specification states that "\[i\]n operation and use, the user must manually set up default correspondence rules…." Although the patent does provide an example of what the court called "a very partial set of default and secondary rules," it is only an example. Because the claim purports to cover **all** such rules, the court held (quoting *Alice*) that "it merely states 'an abstract idea while adding the words "apply it."'"

Had Planet Blue disclosed a specific method (*i.e.*, a specific set of rules for the automatic setting of keyframes), its patent may have successfully run the § 101 / *Alice* gauntlet. Of course, then it may not have covered the defendants' own methods of automating lip synchronization. As the court noted: "This case illustrates the danger that exists when the novel portions of an invention are claimed too broadly."

------------------------------------------------------------------------

[^1]: Virtually all the faiths were represented: Namco, Sega, EA, Disney, Capcom, Neversoft, Treyarch, Warner Bros., LucasArts, Activision, Blizzard, Infinity Ward, Atlus, Konami, Square Enix, Obsidian, Naughty Dog, SCEA, Sucker Punch, Codemasters, and Valve. 

[^2]: Planet Blue actually sued on two patents, one of which is a continuation of the other; because the patents share the same disclosure, I will simply refer to them as "the patent". 

[^3]: *Alice Corp. Pty. Ltd. v. CLS Bank Int'l*, 134 S.Ct. 2347 (2014). 

[^4]: A phoneme is the atomistic unit of spoken language: each distinguishable sound that makes up a word is a phoneme. 

[^5]: A "morph weight" is a value from 0 to 1 that defines intermediate positions between neutral and a morph target. For example, applying morph weight of 0.5 to the "oh" sound would move the mouth halfway between neutral and the "oh" position. 

[^6]: Emphasis added. 
