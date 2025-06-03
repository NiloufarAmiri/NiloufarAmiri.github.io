---
layout: post
title: "A Novel Fuzzy Image-Based UAV Landing Using RGBD Data and Visual SLAM"
date: 2025-06-03
categories: research papers
excerpt: "<img src='/assets/images/drones_pipline.png' width='150' style='border-radius: 0px;'>"
---

## Article Overview

This project presents a novel perception-driven method for autonomous UAV landing in complex, obstacle-filled environments. The approach integrates visual SLAM (vSLAM) with fuzzy logic to enhance landing zone detection. RGB images and point clouds from an onboard camera are analyzed to assess terrain features such as flatness, inclination, and depth variation. A fuzzy inference system then generates a landing suitability map, highlighting safe regions.

Next, the UAV’s pose and a refined set of point clouds are computed using vSLAM. These points are projected onto the image plane and filtered through the fuzzy landing map, acting as a binary mask to isolate viable landing candidates. The optimal landing point is selected as the center of the largest safe cluster.

To execute a precise descent, four synthetic points—based on the UAV’s size—are added to the vSLAM map to enable image-based visual servoing (IBVS) guided by image moment features. The proposed system is validated in the ROS-Gazebo simulator, demonstrating superior performance compared to an existing state-of-the-art method.

## Key Features
- Fusion of Fuzzy Logic and vSLAM: Combines fuzzy inference with visual SLAM to generate a reliable and adaptive landing zone detection pipeline in unstructured environments.

- Risk-Aware Landing Site Selection: Processes RGB images and point clouds to evaluate terrain characteristics (flatness, inclination, depth variation), identifying the safest landing region via a fuzzy suitability map and point cloud projection.

- IBVS-Based Landing Execution: Enhances final landing precision using image-based visual servoing (IBVS) guided by synthetic points and image moment features, tailored to the UAV's physical dimensions.
## Figures

<div style="text-align: center;">
  <img src="/assets/drones_pipline.png" alt="The proposed landing system structure. The major subsystems are highlighted. The blocks highlighted in green represent the inputs. The yellow area corresponds to the vSLAM system. The red section illustrates the fuzzy map construction and postprocessing of vSLAM keypoints. The area highlighted in purple shows the IBVS landing subsystem. The black arrows show the data direction." style="width:60%; border-radius: 0px;">
  <p style="font-style: italic; font-size: 0.9em; margin-top: 5px;">The proposed landing system structure. The major subsystems are highlighted. The blocks highlighted in green represent the inputs. The yellow area corresponds to the vSLAM system. The red section illustrates the fuzzy map construction and postprocessing of vSLAM keypoints. The area highlighted in purple shows the IBVS landing subsystem. The black arrows show the data direction.</p>
</div>


## Read More

You can read the full paper [here](https://doi.org/10.3390/drones8100594).

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