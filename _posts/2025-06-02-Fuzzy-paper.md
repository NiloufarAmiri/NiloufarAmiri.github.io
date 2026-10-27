---
layout: post
title: "Robust controller design for a class of MIMO nonlinear systems using TOPSIS function-link fuzzy cerebellar model articulation controller and interval type-2 fuzzy compensator"
date: 2025-06-02
categories: research papers
excerpt: "<img src='/assets/images/trajectory_tracking.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This study develops an adaptive control framework for multiple-input, multiple-output (MIMO) nonlinear systems with limited prior knowledge of the plant model. The framework combines a function-link fuzzy cerebellar model articulation controller (FLFCMAC), a function-link network (FLN), and an interval type-2 fuzzy logic compensator. The TOPSIS method is used to identify influential fuzzy inference rules.

Online adaptation laws update the controller parameters to address disturbances and model uncertainty. Closed-loop stability is investigated through Lyapunov analysis, and the control framework is assessed in simulations involving a caterpillar robot and an inverted double pendulum.

## Key Features

- **Adaptive fuzzy control:** Combines an FLFCMAC and an FLN for control of nonlinear MIMO systems.
- **Rule selection and uncertainty compensation:** Uses TOPSIS to prioritize fuzzy rules and an interval type-2 fuzzy compensator to address uncertainty.
- **Stability and simulation studies:** Employs Lyapunov-based analysis and evaluates performance on two nonlinear systems.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/trajectory_tracking.png" alt="Trajectory tracking of the controlled states." style="width:60%; border-radius: 8px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Trajectory tracking of the controlled states.</p>
</div>


## Read More

Read the [full paper](https://doi.org/10.22111/ijfs.2023.43250.7618).

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