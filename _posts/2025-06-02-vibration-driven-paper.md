---
layout: post
title: "Optimization and control of an energy-efficient vibration-driven robot"
date: 2025-06-02
categories: research papers
excerpt: "<img src='/assets/images/vibration_robot.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This paper investigates the modeling, optimization, and motion control of an energy-efficient two-module vibration-driven robot. The robot consists of two masses connected by a spring and moves along a straight path through actuation by an unbalanced rotating mass.

The governing dynamics are simulated in MATLAB/Simulink and verified through comparison with MSC Adams results. A parametric study examines the influence of physical design variables on average velocity and energy consumption. The design parameters are then optimized using the NSGA-II genetic algorithm.

For trajectory tracking, proportional–integral–derivative (PID) and fractional-order PID controllers are designed. Both controllers are tuned using a genetic algorithm that considers tracking error and control effort, and their performances are compared.

## Key Features

- **Dynamic modeling and verification:** Develops the robot's equations of motion and compares MATLAB/Simulink predictions with MSC Adams simulations.
- **Energy-aware design optimization:** Uses NSGA-II to select design parameters based on locomotion and energy-consumption objectives.
- **Motion control:** Optimizes and compares PID and fractional-order PID controllers for trajectory tracking.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/vibration_robot.png" alt="Schematic of the vibration-driven robot." style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Schematic of the analyzed vibration-driven robot</p>
</div>


## Read More

Read the [full paper](https://doi.org/10.1177/10775463231175543).

## Citation

```text
@article{amiri2024optimization,
  title={Optimization and control of an energy-efficient vibration-driven robot},
  author={Amiri, Niloufar and Sohrabi, Kourosh and Eftekharian, Ghazal and Fakhari, Vahid},
  journal={Journal of Vibration and Control},
  volume={30},
  number={9-10},
  pages={2184--2199},
  year={2024},
  publisher={SAGE Publications Sage UK: London, England}
}
```