---
layout: default
title: "CS294/194-196 Large Language Model Agents"
permalink: /f24
redirect_from:
 - /
---

### Prospective Students

- ***Students interested in the course should first try enrolling in the course in CalCentral. The class number for CS194-196 is 32306. The class number for CS294-196 is 32304. Please join the waitlist if the class is full.***
- ***We plan to expand the class size to allow more students to join. Please fill in the <a href="https://forms.gle/8sHgNLQm44G9yLRA8">signup form</a> if you are on the waitlist or can't get added to the waitlist. You will receive an email notification around the beginning of the fall semester if you are allowed in.***
- ***<span style="color:red">Do not email course staff or TAs. Please use [Edstem](https://edstem.org/us/join/Mmkzqx) for any questions. For private matters, post a private question on Edstem and make sure it is visable to all teaching staff.</span>***

## Course Staff

<table>
<tbody>
<tr>
<td>Instructor</td>
<td>(Guest) Co-instructor</td>
</tr>
<tr>
<td><img src="assets/dawn-berkeley.jpg" height=200/></td>
<td><img src="assets/XinyunChen.jpg" height=200/></td>
</tr>
<tr>
<td><a href="https://people.eecs.berkeley.edu/~dawnsong/">Dawn Song</a></td>
<td>Xinyun Chen</td>
<tr>
<td>Professor, UC Berkeley</td>
<td>Research Scientist, Google DeepMind</td>
</tr>
</tr>
</tbody>
</table>

GSIs: Alex Pan & Sehoon Kim

Readers: Tara Pande & Ashwin Dara

## Class Time and Location

Lecture: 3-5pm PT Monday at Latimer 120

## Course Description

Large language models (LLMs) have revolutionized a wide range of domains. In particular, LLMs have been developed as agents to interact with the world and handle various tasks. With the continuous advancement of LLM techniques, LLM agents are set to be the upcoming breakthrough in AI, and they are going to transform the future of our daily life with the support of intelligent task automation and personalization. In this course, we will first discuss fundamental concepts that are essential for LLM agents, including the foundation of LLMs, essential LLM abilities required for task automation, as well as infrastructures for agent development. We will also cover representative agent applications, including code generation, robotics, web automation, medical applications, and scientific discovery. Meanwhile, we will discuss limitations and potential risks of current LLM agents, and share insights into directions for further improvement. Specifically, this course will include the following topics:
- Foundation of LLMs
- Reasoning
- Planning, tool use
- LLM agent infrastructure
- Retrieval-augmented generation
- Code generation, data science
- Multimodal agents, robotics
- Evaluation and benchmarking on agent applications
- Privacy, safety and ethics
- Human-agent interaction, personalization, alignment
- Multi-agent collaboration

## Syllabus

| Date   | Guest Lecture | Readings <br> (due Sunday 11:59pm before lecture on Gradescope) | 
|--------|-------|-------|
| Sept 9 | **LLM Reasoning** <br> Denny Zhou, Google DeepMind <br> <a href="./assets/intro.pdf">Intro</a> <a href="./assets/llm-reasoning.pdf">Slides</a> [Original Recording](https://bcourses.berkeley.edu/courses/1535641/external_tools/90481) [Edited Video](https://www.youtube.com/watch?v=QL-FS_Zcmyo) | - [Chain-of-Thought Reasoning Without Prompting](https://arxiv.org/abs/2402.10200) <br> - [Large Language Models Cannot Self-Correct Reasoning Yet](https://arxiv.org/abs/2310.01798) <br> - [Premise Order Matters in Reasoning with Large Language Models](https://arxiv.org/abs/2402.08939) <br> - [Chain-of-Thought Empowers Transformers to Solve Inherently Serial Problems](https://arxiv.org/abs/2402.12875) <br> *All readings are optional this week.* |   
| Sept 16 | **LLM agents: brief history and overview** <br> Shunyu Yao, OpenAI <br> <a href="./assets/llm_agent_history.pdf">Slides</a> [Original Recording](https://bcourses.berkeley.edu/courses/1535641/external_tools/90481) [Edited Video](https://www.youtube.com/watch?v=RM6ZArd2nVc) | - [WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents](https://arxiv.org/abs/2207.01206) <br> - [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)  |          
| Sept 23 | **Agentic AI Frameworks & AutoGen** <br> Chi Wang, AutoGen-AI <br> **Building a Multimodal Knowledge Assistant** <br> Jerry Liu, LlamaIndex <br> <a href="https://rdi.berkeley.edu/llm-agents-mooc/slides/autogen.pdf">Chi's Slides</a> <a href="https://rdi.berkeley.edu/llm-agents-mooc/slides/MKA.pdf">Jerry's Slides</a> [Original Recording](https://bcourses.berkeley.edu/courses/1535641/external_tools/90481) [Edited Video](https://www.youtube.com/watch?v=OOdtmCMSOo4) | - [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155) <br> - [StateFlow: Enhancing LLM Task-Solving through State-Driven Workflows](https://arxiv.org/abs/2403.11322)  |          
| Sept 30 | **Enterprise trends for generative AI, and key components of building successful agents/applications** <br> Burak Gokturk, Google <br> <a href="https://rdi.berkeley.edu/llm-agents-mooc/slides/Burak_slides.pdf">Slides</a> [Original Recording](https://bcourses.berkeley.edu/courses/1535641/external_tools/90481) [Edited Video](https://www.youtube.com/live/Sy1psHS3w3I) | - [Google Cloud expands grounding capabilities on Vertex AI](https://cloud.google.com/blog/products/ai-machine-learning/rag-and-grounding-on-vertex-ai?e=48754805) <br> - [The Needle In a Haystack Test: Evaluating the performance of RAG systems](https://towardsdatascience.com/the-needle-in-a-haystack-test-a94974c1ad38) <br> - [The AI detective: The Needle in a Haystack test and how Gemini 1.5 Pro solves it](https://cloud.google.com/blog/products/ai-machine-learning/the-needle-in-the-haystack-test-and-how-gemini-pro-solves-it?e=48754805) |          
| Oct 7 | **Compound AI Systems & the DSPy Framework** <br> Omar Khattab, Databricks <br> <a href="https://rdi.berkeley.edu/llm-agents-mooc/slides/dspy_lec.pdf">Slides</a> [Original Recording](https://bcourses.berkeley.edu/courses/1535641/external_tools/90481) [Edited Video](https://www.youtube.com/live/JEMYuzrKLUw) | - [Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs](https://arxiv.org/abs/2406.11695) <br> - [Fine-Tuning and Prompt Optimization: Two Great Steps that Work Better Together](https://arxiv.org/abs/2407.10930) |          
| Oct 14 | **Agents for Software Development** <br> Graham Neubig, Carnegie Mellon University <br> <a href="https://rdi.berkeley.edu/llm-agents-mooc/slides/neubig24softwareagents.pdf">Slides</a> [Original Recording](https://bcourses.berkeley.edu/courses/1535641/external_tools/90481) [Edited Video](https://www.youtube.com/live/f9L9Fkq-8K4) | - [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793) <br> - [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741)  |          
| Oct 21 | **AI Agents for Enterprise Workflows** <br> Nicolas Chapados, ServiceNow <br> <a href="https://rdi.berkeley.edu/llm-agents/assets/agentworkflows.pdf">Slides</a> [Original Recording](https://bcourses.berkeley.edu/courses/1535641/external_tools/90481) [Edited Video](https://www.youtube.com/live/-yf-e-9FvOc) | - [WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?](https://arxiv.org/abs/2403.07718) <br> - [WorkArena++: Towards Compositional Planning and Reasoning-based Common Knowledge Work Tasks](https://arxiv.org/abs/2407.05291) <br> - <a href="https://rdi.berkeley.edu/llm-agents-mooc/assets/tapeagents.pdf">TapeAgents: a Holistic Framework for Agent Development and Optimization</a> |          
| Oct 28 | **Towards a unified framework of Neural and Symbolic Decision Making** <br> Yuandong Tian, Meta AI (FAIR) <br> <a href="https://rdi.berkeley.edu/llm-agents/assets/102824-yuandongtian.pdf">Slides</a> [Original Recording](https://bcourses.berkeley.edu/courses/1535641/external_tools/90481) [Edited Video](https://www.youtube.com/live/wm9-7VBpdEo) | - [Beyond A*: Better Planning with Transformers via Search Dynamics Bootstrapping](https://arxiv.org/abs/2402.14083) <br> - [Dualformer: Controllable Fast and Slow Thinking by Learning with Randomized Reasoning Traces](https://arxiv.org/abs/2410.09918v1) <br> - [Composing Global Optimizers to Reasoning Tasks via Algebraic Objects in Neural Nets](https://arxiv.org/abs/2410.01779) <br> - [SurCo: Learning Linear Surrogates For Combinatorial Nonlinear Optimization Problems](https://arxiv.org/abs/2210.12547) |          
| Nov 4 | **Foundation Agent** <br> Jim Fan, NVIDIA | - [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://voyager.minedojo.org/) <br> - [Eureka: Human-Level Reward Design via Coding Large Language Models](https://eureka-research.github.io/) <br> - [DrEureka: Language Model Guided Sim-To-Real Transfer](https://eureka-research.github.io/dr-eureka/) |          
| Nov 11 | **No Class - Veteran's Day** |          |          
| Nov 18 | **Cybersecurity, agents, and open-source** <br> Percy Liang, Stanford University |  |  
| Nov 25 | **Measuring Agent capabilities and Anthropic's RSP** <br> Ben Mann, Anthropic |  |   
| Dec 2 | **LLM Agent Safety** <br> Dawn Song, UC Berkeley |  |          


## Enrollment and Grading

- ***Prerequisite:*** **Students are strongly encouraged to have had experience and basic understanding of Machine Learning and Deep Learning before taking this class, e.g., have taken courses such as CS182, CS188, and CS189.**

***Please fill out the <a href="https://forms.gle/8sHgNLQm44G9yLRA8">signup form</a> if you are on the waitlist or can't get added to the waitlist.***

This is a variable-unit course.
All enrolled students are expected to participate in lectures in person and complete weekly reading summaries related to the course content.
Students enrolling in one unit are expected to submit an article that summarizes one of the lectures.
Students enrolling in more than one unit are expected to submit a lab assignment and a project instead of the article.
The project of students enrolling in 2 units should have a written report, which can be a survey in a certain area related to LLMs.
The project of students enrolling in 3 units should also have an implementation (coding) component that programmatically interacts with LLMs, and the project of students enrolling in 4 units should have a very significant implementation component with the potential for either real world impacts or intellectual contributions.
The grade breakdowns for students enrolled in different units are the following:

|                              | 1 unit | 2 units | 3/4 units |
|------------------------------|--------|---------|-----------|
| Participation                | 40%    | 16%     | 8%        |
| Reading Summaries & Q/A      | 10%    | 4%      | 2%        |
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
| Project group formation | 9/9      | 9/16    |
| Project proposal        |  9/22     | 9/30    |
| Labs                    |  10/1     |  10/15   |
| Project milestone #1    |  10/19     |  10/25   |
| Project milestone #2    |  10/29     |  11/20   |
| Project final presentation    |  11/19     | 12/17    |
| Project final report    |  11/19     | 12/17    |

## Office Hours

- Alex: 5-6pm on Mondays on [Zoom](https://berkeley.zoom.us/j/2012565201)
- Sehoon: 10-11am on Tuesdays on [Zoom](https://berkeley.zoom.us/j/5705498591)
