---
title: GenAI and Critical Thinking
description: How do programming students use ChatGPT? And what can we learn from this? Our observational study (published at FSE'25) shows that concerns about potential decrease in programmers' agency and productivity with Generative Ai are justified.
category: AI for Software Engineering
date: 2025-03-01 10:00:00 
Paper: Link to PDF
image: '/images/fse25-1.jpg'

---

[How do programming students use ChatGPT?](https://arxiv.org/abs/2501.10091)
And what can we learn from this?

I am excited to share with you this new study, recently accepted to [FSE25](https://conf.researchr.org/home/fse-2025), the ACM International Conference on the Foundations of Software Engineering, which is quite renowned in our field. You can download the full paper and the replication package from [Arxiv](https://arxiv.org/abs/2501.10091).

For the last 1.5 years, my student Christian Rahe and I have been trying to carefully answer two questions:
* What strategies do students usually follow when using ChatGPT (or other LLM bots) while solving programming exercises? Particularity, how much autonomous/critical thinking do they keep?
* Could a student pass an introductory programming course using only ChatGPT-generated answers? Or: would ChatGPT pass our course?

Meanwhile there are several studies on the use of hashtag#GenAI in higher education incl. programming. However, our study is kind of unique concerning the _task_ we gave to the participants, since it was *not directly solvable* by an LLM. Thus, the students had to "really think" and comprehend to arrive at a relevant prompt and solve the task. 

Our most interesting observation was a widespread lazy cycle of asking the bot to solve the task, executing its wrong/misleading suggestion, and then copying the error message and asking again. And so on. We called this "a vicious cycle" of submitting wrong generated code and then asking the bot for a fix. The paper includes a batch of qualitative and quantitative analyses, including significant interaction patterns with the bot, which task the bot wasn't able to tackle, interesting correlations, and examples of misleading answers. 

What are my main takeaways:

1. GenAI tools should be carefully taught in software development (as we do for IDEs, debuggers, or version control systems) since unguided usage seems rather contra-productive. This includes teaching best practices and limitations.

2. It is super important for development agents (and RSSEs) using Foundation Models to encounter "human laziness" and ensure critical thinking. 

2. The *interaction* between developers and GenAI agents seems like a Pandora's box, which we are just opening and which need much foundational research: for a meaningful, constructive, responsible usage in Software Engineering.

Most credits for this work goes to Christian Rahe for his fantastic and dedicated work during his master thesis. The work is part of a bigger initiative, where my students, collaborators, and I are studying opportunities but also the *risks* of using Foundation Models and GenAI in Software Development: including in [Requirements Engineering and Design](https://arxiv.org/abs/2408.17404), [Documentation and Knowledge Summarisation](https://arxiv.org/abs/2408.00686), or [Usability Testing](https://arxiv.org/abs/2411.00634). 

I try to regularly post updates on this work. Please stay tuned and feel free to also share your experiences and thoughts in the comments. 

