---
layout: post
title: "Keypoint Detection Technique for Image-Based Visual Servoing of Manipulators"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/open_manipulator.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This study presents a novel keypoint detection method using Convolutional Neural Networks (CNNs) to improve the accuracy and robustness of Deep Visual Servoing (DVS) systems. Initially, Image-Based Visual Servoing (IBVS) is validated through real-world experiments using fiducial markers for feature tracking. To overcome the limitations of these artificial markers, a new CNN-based feature detector is developed to identify keypoints corresponding to the corners of more realistic objects.

A custom dataset is generated from images captured by a robot-mounted camera during random movements in its workspace. The dataset is automatically labeled and augmented through rotation and flipping to enhance training diversity. The CNN is adapted from the VGG-19 architecture pre-trained on ImageNet, with the base layers frozen and the fully connected layers fine-tuned to minimize the mean absolute error between predicted and actual keypoint positions.

Two key enhancements are introduced: substituting max-pooling with average-pooling in the feature extractor and applying a progressively decreasing adaptive learning rate. These refinements result in a 50% drop in validation loss. The model’s generalization capability is further verified using k-fold cross-validation.

## Key Features
- CNN-Based Keypoint Detection Without Fiducial Markers: A novel CNN model is developed to detect keypoints representing realistic object corners, eliminating the reliance on fiducial markers in visual servoing tasks.

- Customized and Augmented Dataset for Training: A dataset is created using images from a robot-mounted camera, automatically labeled and augmented through rotation and flipping to improve model generalization.

- Enhanced CNN Architecture for Improved Accuracy: Modifications to the VGG-19 network—replacing max-pooling with average-pooling and introducing an adaptive learning rate—result in a 50% reduction in validation loss.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/open_manipulator.png" alt="The mounted camera on the robot with an eye-in-hand configuration" style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">The mounted camera on the robot with an eye-in-hand configuration</p>
</div>


## Read More

You can read the full paper [here](https://doi.org/10.1109/CASE59546.2024.10711798).

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