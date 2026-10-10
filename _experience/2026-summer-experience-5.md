---
title: "NVIDIA - Learning and Perception Research group (May 2026)"
collection: experience
type: "Research Intern"
permalink: /experience/2026-summer-experience-5
venue: "Research Intern"
location: "Redmond, WA (USA)"
---

I worked in a variety of projects broadly under the robot perception umbrella. We first developed MG-VQA, an interactive manipulation grounded spatial reasoning benchmark for tool-calling VLMs, lifting static perception to dynamic environments. This project involved developing a simulation environment in PyBullet with Blender as the high quality renderer for VLM-facing tools. We leveraged grasp pose estimation with GraspGen, and designed a pushing primitive that allows VLMs to point to objects and push them in directions to declutter the workspace. This benchmark is now publicly released, and is also used for internal evaluations at NVIDIA.

My second project involved developing a Sim2Real data engine for generating physically and visually diverse demonstration data to finetune VLAs. I designed a data engine that uses Newton+Mujoco for physics variations followed by blender for visual augmentations. The generated data comprised 16 domain randomizations axes such as mass, action noise, robot/object init pose variation, and material texture diversity among others. We generated 1M trajectories for pick-and-place tasks and finetuned VLAs and a behaviour cloning baseline to study the performance and reliability of the pipeline for industrial applications. This work is now a collaborated effort with an internal team.

My last and ongoing project studies precision tasks in robot manipulation beyond pick-and-place. We are developing a benchmark and method for performing mechanical assembly tasks that require precise insertion and placement, along with metrics defined to measure this - which is often ignored in existing pick-and-place benchmark tasks.

---
