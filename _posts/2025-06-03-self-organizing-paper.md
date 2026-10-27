---
layout: post
title: "Robust Image-based Visual Servoing of an Aerial Robot Using Self-organizing Neural Networks"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/drone_turtlebot.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This paper investigates robust image-based visual servoing (IBVS) for a quadrotor tracking a moving ground vehicle. A camera rigidly attached to the UAV provides visual features derived from the zeroth-, first-, and second-order moments of a binary target image. These features encode position- and yaw-related information for feedback control.

The image-feature error is used to generate a desired thrust vector for tracking. To compensate for variations in target velocity and UAV payload, a self-organizing neural network (SONN) is incorporated into the control architecture.

The approach is evaluated through ROS–Gazebo simulations and real-world flight experiments. Closed-loop stability is analyzed using Lyapunov theory while accounting for the modeled uncertainties.

## Key Features

- **Image-moment-based control:** Uses visual features associated with UAV position and yaw to guide tracking.
- **Adaptive uncertainty compensation:** Incorporates an SONN to address changes in target velocity and payload.
- **Experimental evaluation and stability analysis:** Combines physical flight tests with ROS–Gazebo simulations and Lyapunov-based analysis.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/drone_turtlebot.png" alt="UAV and UGV positions" style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">UAV tracking the trajectory of a moving ground vehicle.</p>
</div>


## Read More

Read the [full paper](https://doi.org/10.1007/s12555-024-0367-5).

## Citation

```text
@article{sepahvand2024robust,
  title={Robust Image-based Visual Servoing of an Aerial Robot Using Self-organizing Neural Networks},
  author={Sepahvand, Shayan and Janabi-Sharifi, Farrokh and Masnavi, Houman and Aghili, Farhad and Amiri, Niloufar},
  journal={International Journal of Control, Automation and Systems},
  volume={22},
  number={12},
  pages={3762--3776},
  year={2024},
  publisher={Springer}
}
```