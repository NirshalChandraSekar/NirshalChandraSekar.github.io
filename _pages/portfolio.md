---
layout: archive
title: ""
permalink: /portfolio/
author_profile: true
---


# Work Experience

<h2 style="margin-top: 30px; margin-bottom: 4px;">
  Robotics Perception Engineer Intern @
  <a href="https://www.gritt.ai">Gritt Robotics</a>
</h2>
<p style="margin-top: 0; margin-bottom: 8px;">
  <em>May 2026 – Present · San Francisco, CA</em>
</p>

<p style="margin-top: 0; margin-bottom: 10px;">
  I am interning with the founding team at Gritt Robotics, developing Real2Sim pipelines that reconstruct solar installations as physically constrained digital twins from real-world RGB-D captures. By combining foundation-model perception, 6D object pose estimation, and assembly constraints, I connect scene understanding with simulation-ready reconstruction for robotic manipulation.
</p>

<p style="margin-top: 0; margin-bottom: 20px;">
  My perception work focuses on estimating object position and orientation for precise robot interaction. I implemented and evaluated a 6D pose estimation model that matched the production baseline on real-robot data, achieving <strong>0.76 cm translation error and 0.46&deg; rotation error</strong>, and trained a transformer-based pose estimation architecture. To support perception training and evaluation, I also built a domain-randomized synthetic data engine in Blender, generating over <strong>100,000 annotated images</strong> with depth, segmentation, and 6D pose labels.
</p>

<p style="margin-top: 0; margin-bottom: 20px;">
  I also coauthored <a href="https://arxiv.org/abs/2609.31896"><em>Auditing Quality Filters for Long-Tail Human Data Curation</em></a> with Rishav Agarwal and Anirudh Vemula, for the IROS 2026 Workshop on Long-Term Perception for Human-Centric Autonomy. The paper examines how automated data curation can disproportionately filter out workers in kneeling and bending poses, highlighting challenges in building representative human perception datasets for robots operating around people.
</p>

<h2 style="margin-top: 30px; margin-bottom: 4px;">
  Graduate Research Assistant @ 
  <a href="https://rpm-lab.github.io">Robotics Perception and Manipulation Lab</a>
</h2>
<p style="margin-top: 0; margin-bottom: 8px;">
  <em>January 2024 – Present · University of Minnesota, Minneapolis, MN</em>
</p>

<p style="margin-top: 0; margin-bottom: 10px;">
  My research explores embodied AI for manipulation: how robots can learn from human demonstrations, reason about objects in 3D, and translate learned behaviors into physical interaction. I have trained and deployed diffusion and flow matching policies on dual UR5e robots for contact-rich bimanual tasks, with the diffusion policy achieving <strong>95% task completion on real hardware</strong> using a dataset of 188 teleoperated demonstrations.
</p>

<p style="margin-top: 0; margin-bottom: 20px;">
  My work also spans one-shot grasp transfer using SAM2 and DINOv2, vision-language-action (VLA) policy deployment, and 3D representations for goal-conditioned manipulation. I build Real2Sim pipelines that reconstruct human-object interactions and retarget human hand motions to robot grippers for imitation learning, alongside generative models for predicting future depth observations. Currently, I am developing payload-aware navigation for the Unitree G1 humanoid, combining learned dynamics with predictive collision avoidance around moving obstacles.
</p>



<h2 style="margin-top: 0; margin-bottom: 4px;">
  Computer Vision Engineer Intern @
  <a href="https://www.nilfisk.com/global/">Nilfisk</a>
</h2>
<p style="margin-top: 0; margin-bottom: 8px;">
  <em>May 2024 – December 2024 · Brooklyn Park, MN</em>
</p>

<p style="margin-top: 0; margin-bottom: 10px;">
  At Nilfisk, I developed sim-to-real perception pipelines for autonomous cleaning systems, using NVIDIA Isaac Sim Replicator and domain randomization to generate synthetic training data for industrial debris detection. By combining synthetic and real-world data, I trained YOLO detection and segmentation models that achieved <strong>92% mAP on real-world evaluation data</strong>.
</p>

<p style="margin-top: 0;">
  I also built a Segment Anything Model (SAM)-assisted annotation tool to streamline human-in-the-loop segmentation and dataset preparation, supporting the training and evaluation of perception models for factory environments.
</p>

