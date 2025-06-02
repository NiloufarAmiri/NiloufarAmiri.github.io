---
layout: post
title: "Robust controller design for a class of MIMO nonlinear systems using TOPSIS function-link fuzzy cerebellar model articulation controller and interval type-2 fuzzy compensator"
date: 2025-06-02
categories: research papers
excerpt: "<img src='/assets/images/trajectory_tracking.png' width='150' style='border-radius: 8px;'>"
---

## Article Overview

This study introduces an advanced control framework designed for multiple-input multiple-output (MIMO) systems with limited prior knowledge of the plant model. The core of the controller is a Function-Link Fuzzy Cerebellar Model Articulation Controller (FLFCMAC), which integrates the TOPSIS method to prioritize and retain only the most influential fuzzy inference rules. To further boost tracking accuracy, a Function-Link Network (FLN) is incorporated into the control structure. Additionally, an Interval Type-2 Fuzzy Logic Controller (IT2FLC) is developed to enhance the closed-loop performance under uncertainty.

Given the highly nonlinear nature of the caterpillar robot and the presence of external disturbances and parameter variations, the controller includes online adaptation laws to ensure robust performance. The design is grounded in Lyapunov stability theory, ensuring system stability and guiding the derivation of adaptive learning rules. The effectiveness and robustness of the proposed control system are validated through simulations on both the caterpillar robot and the inverted double pendulum.

## Key Features
- Hybrid Intelligent Control Framework: Combines a Function-Link Fuzzy CMAC (FLFCMAC) with a Function-Link Network (FLN) and Interval Type-2 Fuzzy Logic Controller (IT2FLC) to handle complex MIMO systems with limited plant knowledge.

- Robustness via Online Adaptation: Incorporates online tuning laws and adaptive mechanisms to manage external disturbances and parametric uncertainties, ensuring consistent performance in nonlinear environments like caterpillar robots.

- Stability Guaranteed by Lyapunov Theory: Utilizes Lyapunov-based analysis to ensure system stability and derive adaptive learning rules, reinforcing the controller's reliability and robustness.
## Figures

<div style="text-align: center;">
  <img src="/assets/images/trajectory_tracking.png" alt=" Trajectory tracking of the controlled states." style="width:60%; border-radius: 8px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Trajectory tracking of the controlled states.</p>
</div>


## Read More

You can read the full paper [here](https://doi.org/10.22111/ijfs.2023.43250.7618).

## Citation

```text
@article{sepahvand2023robust,
  title={Robust controller design for a class of MIMO nonlinear systems using TOPSIS function-link fuzzy cerebellar model articulation controller and interval type-2 fuzzy compensator},
  author={Sepahvand, Shayan and Amiri, Niloufar and Pourgholi, Mahdi and Fakhari, Vahid},
  journal={Iranian Journal of Fuzzy Systems},
  volume={20},
  number={5},
  pages={89--107},
  year={2023},
  publisher={University of Sistan and Baluchestan}
}
```