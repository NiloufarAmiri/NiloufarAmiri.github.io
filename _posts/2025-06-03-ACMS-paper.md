---
layout: post
title: "High-performance coupled kinematics of aerial continuum manipulation systems for control applications"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/ACMS_prototype.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This work introduces a generalized discrete coupled kinematic model for a tendon-driven aerial continuum manipulation system (TD-ACMS), grounded in the strain-based formulation of Cosserat rod theory. Unlike traditional models limited to planar bending, this approach accounts for all six deformation modes of the continuum segments, enabling full-body coordination with the aerial platform.

A key contribution is the derivation of a conventional-format coupled Jacobian, which simplifies the development of kinematics-based controllers without requiring the solution of complex differential–algebraic equations. The model’s effectiveness is demonstrated through an image-based visual servoing (IBVS) task featuring a customized tendon routing strategy.

Comparative results show significant improvements in trajectory tracking performance, especially for complex and time-sensitive maneuvers. Real-world experiments on a physical aerial continuum manipulator validate the proposed model and control strategy.

## Key Features
- Fusion of Fuzzy Logic and vSLAM: Combines fuzzy inference with visual SLAM to generate a reliable and adaptive landing zone detection pipeline in unstructured environments.

- Risk-Aware Landing Site Selection: Processes RGB images and point clouds to evaluate terrain characteristics (flatness, inclination, depth variation), identifying the safest landing region via a fuzzy suitability map and point cloud projection.

- IBVS-Based Landing Execution: Enhances final landing precision using image-based visual servoing (IBVS) guided by synthetic points and image moment features, tailored to the UAV's physical dimensions.
## Figures

<div style="text-align: center;">
  <img src="/assets/images/ACMS_prototype.png" alt="Components of the tendon-driven aerial continuum manipulation system." style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Components of the tendon-driven aerial continuum manipulation system.</p>
</div>


## Read More

You can read the full paper [here](https://doi.org/10.1016/j.robot.2025.105021).

## Citation

```text
@article{amiri2025high,
  title={High-performance coupled kinematics of aerial continuum manipulation systems for control applications},
  author={Amiri, Niloufar and Janabi-Sharifi, Farrokh},
  journal={Robotics and Autonomous Systems},
  pages={105021},
  year={2025},
  publisher={Elsevier}
}
```