---
layout: post
title: "High-performance coupled kinematics of aerial continuum manipulation systems for control applications"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/ACMS_prototype.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This paper presents a strain-parameterized, discrete coupled kinematic model for a tendon-driven aerial continuum manipulation system (TD-ACMS) based on Cosserat rod theory. The formulation accounts for the aerial platform's motion and all six deformation modes of the continuum robot segments, including bending, shear, extension, and torsion.

A coupled Jacobian is derived in a conventional matrix form, facilitating the design of kinematics-based controllers without solving stiff differential–algebraic equations. The model is evaluated in an image-based visual servoing (IBVS) task using a customized tendon routing strategy.

Comparative simulations assess trajectory-tracking performance on complex paths, while experiments with an aerial continuum manipulator prototype validate the proposed modeling and control approach.

## Key Features

- **Coupled strain-based modeling:** Represents UAV motion together with the full set of continuum robot deformation modes.
- **Control-oriented Jacobian:** Provides a conventional-form coupled Jacobian to simplify kinematics-based controller design.
- **Simulation and experimental validation:** Evaluates IBVS performance with customized tendon routing and a physical aerial continuum manipulator prototype.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/ACMS_prototype.png" alt="Components of the tendon-driven aerial continuum manipulation system." style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Components of the tendon-driven aerial continuum manipulation system.</p>
</div>


## Read More

Read the [full paper](https://doi.org/10.1016/j.robot.2025.105021).

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