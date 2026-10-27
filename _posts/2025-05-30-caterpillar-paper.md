---
layout: post
title: "Motion control of a caterpillar robot using optimized feedback linearization and sliding mode controllers"
date: 2025-05-30
categories: research papers
excerpt: "<img src='/assets/images/motion_propagation.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This study designs and compares two control strategies—optimized feedback linearization and optimized sliding mode control—for the forward locomotion of a bio-inspired caterpillar robot composed of five links connected by torque-actuated joints. Starting from the robot's nonlinear equations of motion, both controllers are formulated to track desired joint trajectories.

Controller parameters are tuned using a genetic algorithm with an objective that considers both tracking error and control effort. Robustness is then evaluated under parameter uncertainty, sensor noise, and actuator disturbances.

## Key Features

- **Nonlinear dynamic modeling:** Derives the equations of motion for a five-link caterpillar robot.
- **Optimized motion control:** Designs feedback linearization and sliding mode controllers and tunes their parameters using a genetic algorithm.
- **Robustness evaluation:** Compares tracking performance under parameter uncertainty, sensor noise, and actuator disturbances.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/motion_propagation.png" alt="Sequential motion propagation" style="width:60%; border-radius: 8px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Sequential motion propagation</p>
</div>


## Read More

Read the [full paper](https://doi.org/10.1007/s40435-020-00736-6).

## Citation

```text
@article{amiri2021motion,
  title={Motion control of a caterpillar robot using optimized feedback linearization and sliding mode controllers},
  author={Amiri, Niloufar and Fakhari, Vahid and Sepahvand, Shayan},
  journal={International Journal of Dynamics and Control},
  volume={9},
  number={3},
  pages={1107--1116},
  year={2021},
  publisher={Springer}
}
```