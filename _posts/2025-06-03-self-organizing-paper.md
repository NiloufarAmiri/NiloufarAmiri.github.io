---
layout: post
title: "Robust Image-based Visual Servoing of an Aerial Robot Using Self-organizing Neural Networks"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/drone_turtlebot.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This work tackles the challenge of robust image-based visual servoing (IBVS) for aerial robots tasked with tracking a moving vehicle. A perspective projection model is employed using a camera rigidly mounted to the quadrotor. Key image features are extracted from the projection of target points onto the image plane, formulated using zeroth, first, and second image moments. These features encode the relative position and yaw orientation of the UAV in Cartesian space.

To control the UAV, a visual error signal is computed and translated into a thrust command that stabilizes both position and yaw. However, real-world uncertainties—such as dynamic target velocity and payload variations—can degrade tracking accuracy. To address this, a self-organizing neural network (SONN) is integrated into the control architecture, enabling adaptive compensation for these uncertainties.

The proposed approach is validated through extensive simulations in ROS-Gazebo and real-world flight tests, surpassing many prior studies that rely only on MATLAB environments. Finally, system stability is rigorously confirmed using Lyapunov analysis, accounting for all modeled uncertainties.

## Key Features
- Moment-Based Visual Features: Utilizes zeroth, first, and second image moments to extract position and yaw-related features from a binary image, enabling precise image-based control.

- Adaptive Neural Compensation: Incorporates a self-organizing neural network (SONN) to handle uncertainties from target velocity changes and payload variations, improving robustness.

- Real-World Validation and Stability Proof: Validated through both ROS-Gazebo simulations and physical experiments, with system stability guaranteed via Lyapunov-based analysis under uncertainty.
## Figures

<div style="text-align: center;">
  <img src="/assets/images/drone_turtlebot.png" alt="UAV and UGV positions" style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">The unmanned aerial vehicle traversing the trajectory defined by the unmanned ground vehicle</p>
</div>


## Read More

You can read the full paper [here](https://doi.org/10.1007/s12555-024-0367-5).

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