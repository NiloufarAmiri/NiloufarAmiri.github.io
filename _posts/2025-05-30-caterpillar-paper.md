---
layout: post
title: "Motion control of a caterpillar robot using optimized feedback linearization and sliding mode controllers"
date: 2025-05-30
categories: research papers
---

## Article Overview

In this research, we develop and evaluate two advanced control strategies—optimized feedback linearization and optimized sliding mode control—for guiding the forward locomotion of abio-inspired caterpillar robot composed of five interconnected segments with torque-driven joints. The study begins with the derivation of the robot's nonlinear dynamic equations. Next, the controllers are designed to accurately track desired joint trajectories.

To ensure a fair comparison, key control parameters are fine-tuned through a genetic algorithm, using a cost function that simultaneously minimizes both stabilization errors and control efforts. The robustness of each optimized controller is further assessed under challenging conditions, including parameter uncertainties, sensor noise, and actuator disturbances, with a focus on quantitative performance metrics related to accuracy and efficiency.

## Key Features

- Dynamic modeling of a caterpillar robot consisting of five links 
- Development of feedback linearization and sliding mode controllers optimized using genetic algorithms
- Robustness analysis under parametric uncertainty, sensor noise, and actuator disturbances

## Figures

![System Diagram](/assets/images/motion_propagation.png)
*Sequential motion propagation*

<!-- ![Simulation Result](/assets/images/simulation-result.png)
*Landing trajectory using hybrid control.* -->

## Read More

You can read the full paper [here](https://doi.org/10.1007/s40435-020-00736-6).

## Citation

```bibtex

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
