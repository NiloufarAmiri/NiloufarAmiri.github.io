---
layout: post
title: "A Novel Fuzzy Image-Based UAV Landing Using RGBD Data and Visual SLAM"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/drones_pipline.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This paper proposes a perception-guided framework for autonomous UAV landing in cluttered, unstructured environments. RGB-D images and point clouds are processed to characterize surface flatness, steepness, inclination, and depth variation. A fuzzy inference system combines these terrain metrics into a landing suitability map.

Visual simultaneous localization and mapping (vSLAM) estimates the UAV's pose and generates sparse 3D map points. These points are projected onto the image plane and filtered using a thresholded landing suitability map. Candidate regions are assessed using clustering, surface geometry, and the area required for landing to select a suitable location.

Four synthetic corner points are then defined around the selected location based on the UAV's dimensions. Their projected image features are used for image-based visual servoing (IBVS) during landing. The complete approach is evaluated in ROS–Gazebo simulations and compared with an existing landing-site detection method.

## Key Features

- **Fuzzy landing suitability map:** Combines depth and surface-geometry information to identify potentially safe landing regions.
- **vSLAM-based landing-site selection:** Filters mapped 3D points and evaluates candidate regions using geometric and area constraints.
- **Image-based landing control:** Uses synthetic corner points and image moments to guide the UAV toward the selected landing site.

## Figures

<div style="text-align: center;">
  <img src="/assets/images/drones_pipline.png" alt="Diagram of the fuzzy landing, vSLAM, and image-based visual servoing pipeline." style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Proposed landing pipeline: sensory inputs (green), vSLAM (yellow), fuzzy landing map (red), and IBVS control (purple).</p>
</div>


## Read More

Read the [full paper](https://doi.org/10.3390/drones8100594).

## Citation

```text
@article{sepahvand2024novel,
  title={A Novel Fuzzy Image-Based UAV Landing Using RGBD Data and Visual SLAM},
  author={Sepahvand, Shayan and Amiri, Niloufar and Masnavi, Houman and Mantegh, Iraj and Janabi-Sharifi, Farrokh},
  journal={Drones},
  volume={8},
  number={10},
  pages={594},
  year={2024},
  publisher={MDPI}
}
```