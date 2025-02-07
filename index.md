---
layout: default
title: "CS294/194-280 <br> Advanced Large Language Model Agents"
permalink: /sp25
redirect_from:
 - /
---

### Prospective Students

- ***Students interested in the course should first try enrolling in the course in CalCentral. The class number for CS194-280 is 33840. The class number for CS294-280 is 33841. Please join the waitlist if the class is full.***
- ***We plan to expand the class size to allow more students to join. Please fill in the <a href="https://forms.gle/sfWW8M2w1LDTnQWm9">petition form</a> if you are on the waitlist or can't get added to the waitlist. You will receive an email notification around the beginning of the spring semester if you are allowed in.***
- ***<span style="color:red">Do not email course staff or TAs. Please use [Edstem](https://edstem.org/us/join/QMmJkA) for any questions. For private matters, post a private question on Edstem and make sure it is visable to all teaching staff.</span>***

## Course Staff

<table>
<tbody>
<tr>
<td>Instructor</td>
<td>(Guest) Co-instructor</td>
<td>(Guest) Co-instructor</td>
</tr>
<tr>
<td><img src="assets/dawn-berkeley.jpg" height=200/></td>
<td><img src="assets/XinyunChen.jpg" height=200/></td>
<td><img src="assets/KaiyuYang.jpg" height=200/></td>
</tr>
<tr>
<td><a href="https://people.eecs.berkeley.edu/~dawnsong/">Dawn Song</a></td>
<td>Xinyun Chen</td>
<td>Kaiyu Yang</td>
<tr>
<td>Professor, UC Berkeley</td>
<td>Research Scientist, <br> Google DeepMind</td>
<td>Research Scientist, <br> Meta FAIR</td>
</tr>
</tr>
</tbody>
</table>

Teaching Staff: Alex Pan, Tara Pande, Ashwin Dara, Jason Yan

## Class Time and Location

Lecture: 4-6pm PT Monday at Anthro/Art Building 160

## Course Description

Large language model (LLM) agents have been an important frontier in AI, however, they still fall short critical skills, such as complex reasoning and planning, for solving hard problems and enabling end-to-end applications in real-world scenarios. Building on our [previous course](https://llmagents-learning.org/f24), this course dives deeper into advanced topics in LLM agents, focusing on reasoning, AI for mathematics, code generation, and program verification. We begin by introducing advanced inference and post-training techniques for building LLM agents that can search and plan. Then, we focus on two application domains: mathematics and programming. We study how LLMs can be used to prove mathematical theorems, as well as generate and reason about computer programs. Specifically, we will cover the following topics:
- Inference-time techniques for reasoning
- Post-training methods for reasoning
- Search and planning
- Agentic workflow, tool use, and functional calling
- LLMs for code generation and verification
- LLMs for mathematics: data curation, continual pretraining, and finetuning
- LLM agents for theorem proving and autoformalization

## Syllabus
*‡Livestream Only*

| Date   | Guest Lecture <br> (4:00PM-6:00PM PST) | Supplemental Readings | 
|--------|-------|-------|
| Jan 27th | **Inference-Time Techniques for LLM Reasoning** <br> Xinyun Chen, Google DeepMind <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/llm-agents-berkeley-intro-sp25.pdf">Intro</a> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/inference_time_techniques_lecture_sp25.pdf">Slides</a> | - [Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409) <br> - [Large Language Models Cannot Self-Correct Reasoning Yet](https://arxiv.org/abs/2310.01798) <br> - [Teaching Large Language Models to Self-Debug](https://arxiv.org/abs/2304.05128) <br> *All readings are optional this week.* |   
| Feb 3rd‡ | **Learning to reason with LLMs** <br> Jason Weston, Meta <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/Jason-Weston-Reasoning-Alignment-Berkeley-Talk.pdf">Slides</a> | - [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290) <br> - [Iterative Reasoning Preference Optimization](https://arxiv.org/abs/2404.19733) <br> - [Chain-of-Verification Reduces Hallucination in Large Language Models](https://arxiv.org/abs/2309.11495) |   
| Feb 10th‡ | **On Reasoning, Memory, and Planning of Language Agents** <br> Yu Su, Ohio State University  |  - [Grokked Transformers are Implicit Reasoners: A Mechanistic Journey to the Edge of Generalization](https://arxiv.org/abs/2405.15071) <br> - [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831) <br> - [Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents](https://arxiv.org/abs/2411.06559) |   
| Feb 17th | *No Class - Presidents' Day*  | |   
| Feb 24th‡ | **Reasoning and Planning in Large Language Models** <br> Hanna Hajishirzi, University of Washington | |   
| Mar 3rd | **Coding Agents and AI for Vulnerability Detection** <br> Charles Sutton, Google DeepMind | |   
| Mar 10th‡ | **Coding agents/web agents** <br> Ruslan Salakhutdinov, CMU/Meta | |   
| Mar 17th | **Multimodal Agents** <br> Caiming Xiong, Salesforce AI Research | |   
| Mar 24th | *No Class - Spring Recess*  | |   
| Mar 31st‡ | **AlphaProof** <br> Thomas Hubert, Google DeepMind | |   
| Apr 7th | **Language models for autoformalization and theorem proving** <br> Kaiyu Yang, Meta FAIR | |   
| Apr 14th‡ | **Advanced topics in theorem proving** <br> Sean Welleck, CMU | |   
| Apr 21st‡ | **Program verification & generating verified code** <br> Swarat Chaudhuri, UT Austin | |   
| Apr 28th‡ | **Agent safety & security** <br> Dawn Song, UC Berkeley | |   

## Enrollment and Grading

***Prerequisites:*** **Students are strongly encouraged to have had experience and basic understanding of Machine Learning and Deep Learning before taking this class, e.g., have taken courses such as CS182, CS188, and CS189.**

***Please fill out the <a href="https://forms.gle/sfWW8M2w1LDTnQWm9">petition form</a> if you are on the waitlist or can't get added to the waitlist.***

This is a variable-unit course. All enrolled students are expected to participate in lectures in person and complete weekly reading summaries related to the course content. Students enrolling in one unit are expected to submit an article that summarizes one of the lectures. Students enrolling in more than one unit are expected to submit a lab assignment and a project instead of the article.
For students enrolling in 2 units, the project should have a written report, which can be a survey in a certain area related to LLMs. For students enrolling in 3 or 4 units, projects will follow either an applications track or a research track:
 - **Applications Track:** Projects in this track focus on applied use cases of LLMs and do not necessarily need to contribute novel research. Students in this track will work in groups of 3-4. The project for 3-unit students should include an implementation (coding) component that programmatically interacts with LLMs, while 4-unit students must complete a more substantial implementation with the potential for real-world impact.
 - **Research Track:** Students in this track will conduct novel research under the supervision of postdocs and graduate students, with the goal of publishing in a workshop or conference. Research track projects must be completed in groups of 2-3, and students must apply to participate via a forthcoming Google form. The expectations for implementation and intellectual contributions will align with the project requirements for 3- and 4-unit students.
    
The grade breakdowns for students enrolled in different units are the following:

|                              | 1 unit | 2 units | 3/4 units |
|------------------------------|--------|---------|-----------|
| Participation                | 40%    | 16%     | 8%        |
| Reading Summaries            | 10%    | 4%      | 2%        |
| Quizzes                      | 10%    | 4%      | 2%        |
| Article                      | 40%    |         |           |
| Lab                          |        | 16%     | 8%        |
| Project                      |        |         |           |
| &nbsp;&nbsp;*Proposal*       |        | 10%     | 10%       |
| &nbsp;&nbsp;*Milestone 1*    |        | 10%     | 10%       |
| &nbsp;&nbsp;*Milestone 2*    |        | 10%     | 10%       |
| &nbsp;&nbsp;*Presentation*   |        | 15%     | 15%       |
| &nbsp;&nbsp;*Report*         |        | 15%     | 15%       |
| &nbsp;&nbsp;*Implementation* |        |         | 20%       |

## Lab and Project Timeline

|                         | Released | Due    |
|-------------------------|----------|--------|
| Project group formation | 1/27      | 2/17    |
| Project proposal        |  2/3     | 2/17    |
| Project milestone #1    |  2/17     |  3/24   |
| Project milestone #2    |  3/24     |  4/28   |
| Lab                     |  3/31     |  4/28   |
| Project final presentation    |  4/28     | 5/9    |
| Project final poster    |  4/28     | 5/9    |
| Project final report    |  4/28     | 5/16    |

## Office Hours
- Alex: 6-7pm on Mondays on [Zoom](https://berkeley.zoom.us/j/2012565201)
