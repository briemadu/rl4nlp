---
title: Guidelines
layout: default
navigation_weight: 4
---

# Guidelines

Detailed guidelines for this seminar.

Each one of you will be the blogger once during the semester, working on one paper of your choice. Every participant is always a debater in the audience throughout the semester, except during the week when she/he is a blogger. 

During the first week of the course, I will publish the schedule with papers and assigned participants, based on those who have enroled at Moodle (so please do it) and as far as possible on your paper preferences. 

In the first (probably two) weeks there will be no bloggers: I have posted the introductory articles we will read together and I will propose the discussion topics. The role of debaters comes into force for every participant as of April 20.

### Blogger

**Duties**
* Carefully read the paper assigned to you. Be skeptical, judge the accuracy of choices made, the credibility of information. It is important to do parallel research and take a look at the referenced works. We normally have to read a paper several times to get a complete glimpse of the work and identify potential flaws. Allow enough time for this. 
* Write a blog post about it and send it to me by email as a pdf file on your scheduled **Monday before 11:59 a.m**.
* In the body of your e-mail, write three discussion topics. I will immediately publish these and the pdf on Moodle.
* Add three new entries to the course's cooperative glossary on Moodle, with words of your choice that are related to RL and were new to you.
* You have to interact with your peers in the forums during the week. It does not mean you must be online 24 hours and answer straight away, but you have to be present everyday, answer questions, reply to comments etc.
* On the following Monday, we meet online at 3 p.m. for a 15-minute talk. I wish to hear from you what you have learned, the difficulties you have faced and your impressions on the forum debates. This is an informal talk, so don't worry about preparing any material, but be ready to spontaneously talk about the content you worked with. I will also give you anonymous feedback provided by your colleagues.
 
**Instructions**
* Your blog post should have not less than 3,500 words (an approximately 15-minute read in [Medium.com's](https://blog.medium.com/read-time-and-you-bc2048ab620c) estimates, plus the needed time for non-textual content). 
* Assume your audience is familiar with NLP, but not at all with the paper, and so is willing that you spoon-feed them with whatever they need to understand it.
* Be creative: the style may be more informal and pedagogical; you can use pictures, memes, emojis, examples etc.
* The post **must** include the following:
    * title of the blog post as a heading, your name as the author and information about the paper as a subheading
    * begin with a TL;DR (max 100 words)
    * briefly describe the NLP task that the paper is trying to solve and other methods people have been using apart from RL
    * explain what the authors of the paper have done
    * especially explain how the ideas of RL have been used to model the task (e.g. how was the reward translated into NLP concepts?); this should be the main focus of the post
    * mention good aspects and accomplishments of the paper: which ideas did you find interesting and why?
    * criticize the paper: which ideas did you disagree with? how would you change that?
    * propose some suggestions for a follow-up research
    * references (not included in the word count)
* You can also cover who the authors are, what is their background/workplace and how it could affect the research, external sources that were useful for you, questions left unanswered, what other researchers think about this paper, anything you find important. 
* You don't have to dissect the maths, but if a mathematical expression is essential, explaining it using words is useful.
* You don't have to explain any code, but if an algorithm is important, again it is useful to describe what it does.
    
A few examples of blog posts about papers: [here](http://nlp.seas.harvard.edu/2018/04/03/attention.html), [here](https://ruder.io/learning-select-data/index.html) and [here](https://jalammar.github.io/illustrated-bert/). [This one](https://karpathy.github.io/2016/05/31/rl/) and [this one](https://lilianweng.github.io/lil-log/2018/02/19/a-long-peek-into-reinforcement-learning.html) have a good overview of RL, that I recommend you to read before the course starts.

Getting used to reading papers after years of nice textbooks takes a while. [These slides](https://www.lib.purdue.edu/sites/default/files/libraries/engr/Tutorials/Newest%20Scientific%20Paper.pdf) may be a place to start, and you can easily find more material on the internet (search for *how to read a scientific paper*). If you need inspiration on how to critically evaluate a paper, pretend you are an ACL reviewer following [their guidelines](https://acl2020.org/reviewers/). 

Feel free to contact me if you have any trouble. I do not expect you to be experts, neither on scientific literature nor on RL.

### Debaters

**Duties**
* skim through the current week's paper (read the abstract, introduction, conclusion and see the figures and tables).
* read the blogger's post and submit a short feedback (list 2 aspects you liked and 2 aspects you think could be improved) through the anonymous feedback form on Moodle before the following **Monday at 11:59 a.m.**. I will aggregate the data and provide it to the blogger.
* anytime before the following **Monday at 11:59 a.m.**, post at least one contribution to three discussion topics on Moodle (i.e. at least 3 comments per week). The comments should be pertinent to the development of the discussion so far. Your week contribution must consist of at least 300 words (split among all your comments). You may ask questions, politely disagree with the blogger, suggest improvements, support the author or blogger with more evidence, recommend material etc. Remember it is the participation (not the correctness) that counts on the grade, a relevant comment is fine even if it is not 100% right.
* anytime you encounter a new concept that you consider important, add it to the cooperative glossary on Moodle.

Be sincere on the feedback and provide constructive suggestions. This will be helpful for everyone. Do not write general comments that do not mean much (like 'the post was very useful'). Instead, talk about the structure of the text, how information was given, what caused you confusion etc.

# Final project
You can choose between writing a literature [review article](https://en.wikipedia.org/wiki/Review_article) or implementing (Python code+report) a model and running experiments. 

**Review article**: summarize the current state of understanding in applications of Reinforcement Learning to Natural Language Processing into an article. Follow the points in the Wikipedia's link above: mention the main people working in a field, recent major advances and discoveries, significant gaps in the research, current debates and ideas of where research might go next. Notice the idea is not describing paper by paper, by building a structured general analysis by finding patterns and similarities among all (or as many as possible) the papers listed on the bibliography (and any other you discover during the research). You can find great instructions [here](https://www.dcu.ie/sites/default/files/students_learning/scientific_lit_review_workshop_ug.pdf). 

Some examples of good review articles: the [second paper](https://www.ijcai.org/Proceedings/2019/880) we covered, [this one](https://www.aclweb.org/anthology/C18-1253/) about incremental processing and [this one](https://arxiv.org/abs/1512.05742) on corpora for dialog systems (this is a long one, though).

**Experiments**: implement a Reinforcement Learning approach applied to a Natural Language Processing task and run experiments. I do not expect originality, but it cannot be an exact copy of a work that already exists. Some idea, even if incremental, must be your own. Or your can use ideas from the papers that have not been tested yet. It is not a problem if your approach does not lead to good results, as long as you explain your motivation and describe what can be the causes for such results. Please implement it in **Pyhton**. 

The final report should follow the structure of a paper: introduction, related word, description of your model, results of your experiments and conclusion. If your choose this option, send me a short proposal (half a page) describing what you intend to do by **July 30**. 

**Format**

In both cases, for you to practice how a real paper submission works, write your article following the formatting guidelines of long papers either of [COLING2020](https://coling2020.org/pages/submission) or [EMNLP2020](https://2020.emnlp.org/call-for-papers). The only difference is that your report must have **exactly 9 pages** plus blibliography and (if you need) appendix.

There will be a link in Moodle for you to submit a pdf. Those who opt for the experiments must also submit a compressed file with your code or point to a repository.

**Submission deadline for the final project: September 30, 23:59.**

