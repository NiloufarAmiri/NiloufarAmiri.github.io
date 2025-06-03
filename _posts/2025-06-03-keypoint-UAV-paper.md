---
layout: post
title: "Deep Visual Servoing of an Aerial Robot Using Keypoint Feature Extraction"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/keypoint_background.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This work explores image-based visual servoing (IBVS) for aerial robots using deep learning-driven keypoint detection. A monocular RGB camera onboard the UAV captures real-time visual data, which is processed by a convolutional neural network (CNN) to extract key visual features for control.

Unlike traditional methods that rely on artificial markers, this approach eliminates that dependency and enhances robustness against occlusions, lighting changes, background clutter, and scene variability. As a result, it significantly extends the practicality of perception-based control for aerial platforms in dynamic environments.

The system's performance is rigorously evaluated through physics-based simulations in ROS-Gazebo, offering a more realistic assessment compared to marker-dependent or simplified simulation environments.
A demonstration video is available: [here](https://youtu.be/Dd2Her8Ly-E)

## Key Features

- Marker-Free Keypoint Detection: Utilizes a CNN to extract visual features from RGB images, removing the reliance on artificial fiducial markers.

- Robustness to Real-World Variability: Enhances performance under challenging conditions such as occlusion, illumination changes, background clutter, and dynamic scenes.

- Realistic Evaluation Environment: Validated through physics-based ROS-Gazebo simulations, offering a more accurate representation of real-world aerial robot behavior compared to simplified simulation setups.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/keypoint_background.png" alt="Various worlds created in Gazebo were utilized to
carry out robustness tests." style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Various worlds created in Gazebo were utilized to
carry out robustness tests.</p>
</div>


## Read More

You can read the full paper [here](https://doi.org/10.1109/ICUAS65942.2025.11007902).

## Citation

```text
@inproceedings{sepahvand2025deep,
  title={Deep Visual Servoing of an Aerial Robot Using Keypoint Feature Extraction},
  author={Sepahvand, Shayan and Amiri, Niloufar and Janabi-Sharifi, Farrokh},
  booktitle={2025 International Conference on Unmanned Aircraft Systems (ICUAS)},
  pages={37--43},
  year={2025},
  organization={IEEE}
}
```