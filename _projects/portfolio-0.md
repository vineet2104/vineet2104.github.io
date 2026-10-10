---
title: "MG-VQA: Manipulation Grounded Visual Question Answering with VLMs"
excerpt: "<br/><img src='/images/mg-vqa-header.png'>"
collection: projects
---

Imagine asking a household robot, “What’s underneath the blue bowl?” or “How many batteries are left in the pile?” In a cluttered workspace, the answer often isn’t visible: objects are stacked, buried, or turned away from the camera, and finding out means actually lifting or sliding things aside. Vision-language models have become impressive spatial reasoners, but they are almost always tested on static images where the evidence is already in view, which tells us nothing about whether they can recognize when evidence is missing and physically go uncover it. Everyday environments are cluttered and manipulation is no oracle: grasps fail, objects slip, and pushes disturb the scene without revealing anything new. To study this, we introduce Manipulation-Grounded Visual Question Answering (MG-VQA), where an agent answers questions about a cluttered scene by using manipulation as a tool for gathering evidence. Our benchmark, MG-VQA-Bench, contains 600 human-verified questions across four tasks (Count, Find, Beneath, and Compare), each built so the critical evidence is hidden at the start, and runs in a physics simulator with a UR5 robot. Across eight frontier VLMs, perception tools barely beat an image-blind baseline, while manipulation lifts average success from about 37% to 57%. The strongest models search persistently and re-ground after failed actions, while weaker ones answer too early or give up after a single miss, pointing to the need for VLM agents that gather evidence through persistent, physically grounded interaction.

[Paper](https://arxiv.org/pdf/2608.17129v2) [Code](https://github.com/vineet2104/MG-VQA)

---
