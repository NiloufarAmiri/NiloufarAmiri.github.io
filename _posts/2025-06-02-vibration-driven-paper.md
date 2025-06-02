---
layout: post
title: "Optimization and control of an energy-efficient vibration-driven robot"
date: 2025-06-02
categories: research papers
excerpt: "<img src='/assets/images/vibration_robot.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

Vibration-driven robots represent a class of simple yet highly capable systems used in various fields such as disaster debris removal, pipeline inspection, and medical applications. This work focuses on the modeling, optimization, and control of a two-module vibration-driven robot designed for rectilinear motion. The robot consists of two masses connected via a spring and is actuated by an unbalanced rotating mass.

The robot’s dynamic behavior is first modeled and simulated in MATLAB/Simulink, with validation performed through comparative analysis against results from MSC Adams. A parametric study is then conducted to analyze how physical design parameters influence the robot’s energy consumption and average velocity.

An optimization framework is developed using the NSGA-II genetic algorithm to identify the most effective configuration based on a defined objective function. To ensure precise motion control of the optimized system, two control strategies—PID and Fractional Order PID—are implemented. Both controllers are further tuned using genetic algorithms to minimize tracking error and control effort simultaneously.

The study concludes with a comparative evaluation of the two control methods, highlighting their effectiveness in achieving energy-efficient and accurate locomotion for the vibration-driven robot.

## Key Features
- A genetic algorithm (NSGA-II) is utilized to optimize physical parameters and minimize energy consumption for rectilinear motion.
- The robot’s dynamic equations are derived and simulated using MATLAB/Simulink, and the model is validated through physics-based simulations in MSC Adams.
- Both PID and Fractional Order PID controllers are designed and optimized to achieve precise trajectory tracking with minimal control effort.
## Figures

<div style="text-align: center;">
  <img src="/assets/images/vibration_robot.png" alt=" Schematic of the analyzed vibration-driven robot." style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Schematic of the analyzed vibration-driven robot</p>
</div>


## Read More

You can read the full paper [here](https://doi-org.ezproxy.lib.torontomu.ca/10.1177/10775463231175543).

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