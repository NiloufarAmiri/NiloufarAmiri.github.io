---
layout: post
title: "Strain-Parameterized Coupled Dynamics and Dual-Camera Visual Servoing for Aerial Continuum Manipulators"
date: 2026-10-27
categories: research papers
excerpt: "<img src='/assets/tmech-dual-camera-acm.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This paper presents a unified dynamic modeling and control framework for tendon-driven aerial continuum manipulators (TD-ACMs). The proposed formulation combines the rigid-body dynamics of an underactuated uncrewed aerial vehicle (UAV) with a strain-parameterized Cosserat rod model of the continuum robot. By expressing the coupled dynamics through a Lagrangian ordinary differential equation framework on SE(3), the method accounts for continuum elasticity, damping, and distributed external wrenches without requiring computationally intensive explicit symbolic derivations of the coupled dynamic matrices.

Building on this model, a hierarchical dual-camera image-based visual servoing (IBVS) architecture is developed. A local camera mounted at the continuum robot tip provides image feedback for precise positioning, while a global camera mounted on the UAV supports target reacquisition when the target leaves the local camera's field of view (FoV). A virtual-camera formulation compensates for image motion induced by UAV roll and pitch, and a low-level adaptive model-based controller addresses modeling uncertainties under the stated stability assumptions.

The approach is evaluated through simulations and experiments using a custom-built TD-ACM, including ground-based continuum robot tests and free-flight aerial manipulation. Under matched numerical conditions, the proposed dynamic formulation reduces the average computation time per iteration by approximately **26.3%** compared with the evaluated coupled Lagrangian baseline. The results also demonstrate target reacquisition and convergence of image-feature errors during vision-guided control.

## Key Features

- **Strain-parameterized coupled dynamics:** Integrates an underactuated UAV and a Cosserat rod continuum robot within a unified SE(3)-based Lagrangian formulation, avoiding explicit symbolic derivation of large coupled dynamic matrices.
- **Dual-camera visual servoing:** Combines local, tip-mounted visual feedback with a UAV-mounted global camera for FoV recovery, while compensating for attitude-induced image motion.
- **Adaptive control and experimental validation:** Incorporates a model-based adaptive controller with Lyapunov-based stability analysis and evaluates the framework in simulation, fixed-base tests, and free-flight experiments.

## Figures

<div style="text-align: center;">
  <img src="{{ '/assets/tmech-dual-camera-acm.png' | relative_url }}" alt="Photograph and component views of the custom-built X650-based tendon-driven aerial continuum manipulator, including its Nitinol backbone, tendons, spacer disks, cameras, and onboard electronics." style="width:80%; border-radius: 8px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Customized TD-ACM experimental platform and its main mechanical, sensing, and onboard control components.</p>
</div>

## Read More

Read the [full paper](https://doi.org/10.1109/TMECH.2026.3739180).

## Citation

```text
@article{amiri2026strain,
  title={Strain-Parameterized Coupled Dynamics and Dual-Camera Visual Servoing for Aerial Continuum Manipulators},
  author={Amiri, Niloufar and Janabi-Sharifi, Farrokh},
  journal={IEEE/ASME Transactions on Mechatronics},
  year={2026},
  doi={10.1109/TMECH.2026.3739180},
  note={Accepted for publication}
}
```
