---
layout: post
title: "Deep Visual Servoing of an Aerial Robot Using Keypoint Feature Extraction"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/keypoint_background.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This study investigates image-based visual servoing (IBVS) for aerial robots using deep-learning-based keypoint detection. A monocular RGB camera mounted on the UAV supplies images to a convolutional neural network (CNN), which extracts visual features for feedback control.

Unlike conventional approaches that depend on artificial markers, the learned detector does not require fiducial markers. Its robustness is evaluated under occlusion, changes in illumination, visual clutter, and variations in the background.

The proposed approach is evaluated through physics-based ROS–Gazebo simulations. A [demonstration video](https://youtu.be/Dd2Her8Ly-E) is also available.

## Key Features

- **Marker-free feature extraction:** Uses a CNN to detect image keypoints without relying on fiducial markers.
- **Robustness evaluation:** Examines performance under occlusion, illumination changes, clutter, and background variation.
- **Physics-based simulation:** Assesses visual servoing performance in ROS–Gazebo environments.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/keypoint_background.png" alt="Gazebo environments used for robustness testing." style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Gazebo environments used for robustness testing.</p>
</div>


## Read More

Read the [full paper](https://doi.org/10.1109/ICUAS65942.2025.11007902).

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