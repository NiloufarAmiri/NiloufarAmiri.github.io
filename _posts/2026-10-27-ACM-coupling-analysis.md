---
layout: post
title: "Systematic Analysis of Coupling Effects on Closed-Loop and Open-Loop Performance in Aerial Continuum Manipulators"
date: 2026-10-27
categories: research papers
excerpt: "<img src='/assets/icuas-coupling-schematic.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This paper systematically compares coupled and decoupled dynamic models of aerial continuum manipulators (ACMs) to identify when the simpler formulation can provide comparable performance at a lower computational cost. The system dynamics are derived using the Euler–Lagrange method under the piecewise constant curvature (PCC) assumption, with a regularization strategy to handle near-zero curvature. The decoupled formulation is obtained by neglecting the dynamic coupling terms between the UAV and the continuum arm.

Open-loop simulations examine the effects of actuation profiles, external tip wrenches, and variations in system parameters, including UAV mass, continuum arm geometry and stiffness, and initial configurations. The results reveal conditions in which neglecting coupling substantially changes the predicted end-effector motion, particularly when the continuum arm is actively actuated.

For closed-loop control, a dynamics-based proportional–derivative sliding mode image-based visual servoing (DPD-SM-IBVS) controller is developed to track moving visual targets. Lyapunov analysis establishes global ultimate boundedness of the image-feature error. Under the simulated tracking scenarios, the difference between the coupled and decoupled image-feature error norms remains below 0.7 pixels, while the decoupled model reduces the reported computation time per sampling instant from 32 ms to 22 ms.

## Key Features

- **Coupled versus decoupled dynamics:** Derives and compares Euler–Lagrange ACM models under the PCC assumption, including treatment of the near-zero curvature singularity.
- **Open-loop sensitivity analysis:** Investigates how actuation, external wrenches, geometry, material stiffness, and platform parameters influence coupling effects.
- **Robust vision-guided control:** Introduces DPD-SM-IBVS for moving-target tracking and evaluates the accuracy–computation trade-off between the two dynamic formulations.

## Figures

<div style="text-align: center;">
  <img src="{{ '/assets/icuas-coupling-schematic.png' | relative_url }}" alt="Aerial continuum manipulator with the UAV base, tip, camera and inertial frames labeled, positioned opposite an AprilTag target." style="width:60%; border-radius: 8px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Aerial continuum manipulator with the coordinate frames and visual target used to illustrate the modeling and tracking setup.</p>
</div>

## Read More

Read the [full paper](https://doi.org/10.1109/ICUAS69441.2026.11598604).

## Citation

```text
@inproceedings{amiri2026systematic,
  title={Systematic Analysis of Coupling Effects on Closed-Loop and Open-Loop Performance in Aerial Continuum Manipulators},
  author={Amiri, Niloufar and Sepahvand, Shayan and Mantegh, Iraj and Janabi-Sharifi, Farrokh},
  booktitle={2026 International Conference on Unmanned Aircraft Systems (ICUAS)},
  pages={1184--1191},
  year={2026},
  organization={IEEE},
  doi={10.1109/ICUAS69441.2026.11598604}
}
```
