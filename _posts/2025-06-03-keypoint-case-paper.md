---
layout: post
title: "Keypoint Detection Technique for Image-Based Visual Servoing of Manipulators"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/open_manipulator.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This study develops a convolutional neural network (CNN)-based keypoint detector to support deep visual servoing (DVS) without relying on fiducial markers. Conventional image-based visual servoing (IBVS) is first evaluated in physical experiments using markers. A learned detector is then designed to identify the corners of more realistic target objects.

A dataset is collected using a camera mounted on the robot's end-effector as the manipulator moves through its workspace. The images are automatically labeled and augmented through rotation and flipping. Starting from an ImageNet-pretrained VGG-19 model, the feature-extraction layers are kept fixed while the fully connected layers are trained to estimate keypoint coordinates.

Replacing max-pooling with average-pooling and introducing a progressively decreasing learning rate reduce validation loss by 50%. The model is further evaluated using k-fold cross-validation.

## Key Features

- **Marker-free keypoint detection:** Develops a CNN to identify object corners for visual servoing.
- **Automated dataset preparation:** Collects, labels, and augments images from an eye-in-hand robotic setup.
- **Improved CNN training:** Adapts VGG-19 with average-pooling and a decreasing learning rate, followed by cross-validation.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/open_manipulator.png" alt="The mounted camera on the robot with an eye-in-hand configuration" style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Camera mounted on the robot in an eye-in-hand configuration.</p>
</div>


## Read More

Read the [full paper](https://doi.org/10.1109/CASE59546.2024.10711798).

## Citation

```text
@inproceedings{amiri2024keypoint,
  title={Keypoint Detection Technique for Image-Based Visual Servoing of Manipulators},
  author={Amiri, Niloufar and Wang, Guanghui and Janabi-Sharifi, Farrokh},
  booktitle={2024 IEEE 20th International Conference on Automation Science and Engineering (CASE)},
  pages={3557--3562},
  year={2024},
  organization={IEEE}
}
```