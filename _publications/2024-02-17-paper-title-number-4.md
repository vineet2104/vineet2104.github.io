---
title: "Grounding LLMs For Robot Task Planning Using Closed-loop State Feedback"
collection: publications
permalink: /publication/BBLLM-Arxiv
excerpt: 'This paper discusses a novel approach to robotic task planning, using a Two-LLM system for breaking down a complex task into executable plans followed by grounding to the robotic environment. We leverage environmental state information and error messages during execution to guide the LLM planner for task resolution. Our paper achieves improved results in the popular VirtualHome robotic simulation environment'
date: 2024-02-13
venue: 'ArXiv Preprint'
paperurl: 'https://arxiv.org/pdf/2402.08546'
---

Abstract: Robotic planning algorithms direct agents to perform actions within diverse environments to accomplish a task. Large Language Models (LLMs) like PaLM 2, GPT-3.5, and GPT-4 have revolutionized this domain, using their embedded real-world knowledge to tackle complex tasks involving multiple agents and objects. This paper introduces an innovative planning algorithm that integrates LLMs into the robotics context, enhancing task-focused execution and success rates. Key to our algorithm is a closed-loop feedback which provides real-time environmental states and error messages, crucial for refining plans when discrepancies arise. The algorithm draws inspiration from the human neural system, emulating its brainbody architecture by dividing planning across two LLMs in a structured, hierarchical fashion. Our method not only surpasses
baselines within the VirtualHome Environment, registering a notable 35% average increase in task-oriented success rates, but achieves an impressive execution score of 85%, approaching the human-level benchmark of 94%. Moreover, effectiveness of the algorithm in real robot scenarios is shown using a realistic physics simulator and the Franka Research 3 Arm. [Demo](http://tinyurl.com/2akwhvf2)


