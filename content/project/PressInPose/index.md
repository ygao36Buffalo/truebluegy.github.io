---
title: "PressInPose: Integrating Pressure and Inertial Sensors for Full-Body Pose Estimation in Activities"
summary: "Introducing PressInPose, a novel system combining smart insoles and wrist IMUs with virtual data augmentation for precise full-body pose estimation in dynamic activities."
date: 2024-11-21 # 发布日期
# type: docs
# math: false
tags:
  - Wearable Computing
  - Pose Estimation
  - Sensor Fusion
  - AI
  - Human Biomechanics
# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Our PressInPose system for full-body pose estimation.'

authors:
  - admin
---

## Project Overview

Accurate human body posture assessment through wearable technology has significant implications across various fields, including sports science, clinical diagnostics, rehabilitation, and VR interaction. Traditional methods often face limitations due to complex setups or environmental constraints. To address these challenges, we developed **PressInPose**, an innovative system that integrates pressure and inertial sensors for precise full-body pose estimation in dynamic activities. This work was published in **Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT)** and will be presented at **UbiComp 2025**.

## Key Innovations & Contributions:

### 1. Novel Multi-Sensor Fusion
PressInPose employs an advanced shoe insole embedded with pressure sensors and an Inertial Measurement Unit (IMU), coupled with a single wrist-mounted IMU. This unique multi-modal sensor fusion approach allows for a comprehensive analysis of human biomechanics, capturing intricate body dynamics that traditional single-sensor systems often miss.

### 2. LLM-Powered Virtual Data Augmentation
To enhance the robustness and generalization of our system, we leveraged large language models (LLMs) to generate virtual human motion sequences. These sequences were utilized to create synthetic IMU data for data augmentation, effectively addressing the challenge of limited real-world data availability and variability, especially for complex and dynamic movements.

### 3. Physical Kinematics Modeling & Deep Learning Network
Our approach uniquely combines physical kinematics modeling based on pressure data with a multi-region human posture estimation network. This integration allows PressInPose to accurately capture interactions and dependencies between different body parts, leading to superior accuracy in pose reconstruction.


## Media & Resources:

*   **Paper:** [Full Paper (ACM DL)](`https://doi.org/10.1145/3699773`)

---
Did you find this page helpful? Consider sharing it 🙌