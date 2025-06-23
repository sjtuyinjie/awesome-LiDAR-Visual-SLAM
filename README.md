# Awesome-LiDAR-Visual-SLAM
💎 Author: [**Jie Yin 殷杰**](https://github.com/sjtuyinjie)

[![Author](https://img.shields.io/badge/Author-Jie%20Yin-blue)](https://sjtuyinjie.github.io/)
[![License](https://img.shields.io/badge/License-MIT-cyan)]()


I'm an active open-source contributor interested on robotics and embodied AI, especially on reinforcement learning, dexterous manipulation, SLAM and arm plan and control. Welcome to follow me!

## 📝 Introduction

This is a curated list of resources relevant to LiDAR-Visual-Fusion-SLAM, which overviews **over 30** top-tier publications on LiDAR-Visual fusion SLAM systems. I will keep updating this website from time to time. If this project is helpful for your research, please give me a star and fork, thanks!
**If your work about LiDAR-Visual-SLAM is accepted to top conferences or transactions, welcome to propose a issue and remind me of updating your work!**

LiDAR-Visual SLAM combines the strengths of LiDAR and visual sensors to provide highly accurate and robust localization and mapping. This fusion leverages the precise distance measurements from LiDAR and the rich environmental details captured by cameras, resulting in enhanced performance in diverse and challenging environments.
Below is a demo video of LiDAR-Visual-IMU SLAM system from [SR LIVO](https://github.com/ZikangYuan/sr_livo), which shows the amazing performance of localization and mapping.

<div align="left">
<img src="pic/map.png" width=40.0% />
<img src="pic/runx8.gif" width=52.11% />
</div>


## 🚩 Papers
### 2025 (updating!)
- 🔥 **[IROS2025] Towards Robust Sensor-Fusion Ground SLAM: A Comprehensive Benchmark and A Resilient Framework [[paper](https://ieeexplore.ieee.org/document/9739244)][[code](https://github.com/sjtuyinjie/Ground-Fusion2)][[dataset](https://github.com/sjtuyinjie/M3DGR)]** (A complete solution for SLAM under corner cases, including benchmark datasets and a resilient multi-sensor fusion SLAM framework)



### 2024

- 🔥 **[TRO2024] FAST-LIVO2: Fast, Direct LiDAR-Inertial-Visual Odometry [[paper](TBD)][[code](https://github.com/hku-mars/FAST-LIVO2)]**

- 🔥 **[TPAMI2024] R3LIVE++: A Robust, Real-time, Radiance reconstruction package with a tightly-coupled LiDAR-Inertial-Visual state Estimator [[paper](https://arxiv.org/abs/2209.03666)][[code](https://github.com/hku-mars/r3live)]**
  
- [RAL2024] LIVER: A Tightly Coupled LiDAR-Inertial-Visual State Estimator With High Robustness for Underground Environments [[paper](https://ieeexplore.ieee.org/abstract/document/10404014)]

- [RAL2024] A LiDAR-inertial-visual odometry and mapping system based on the sweep reconstruction method [[paper](https://xplorestaging.ieee.org/document/10501952)][[code](https://github.com/ZikangYuan/sr_livo)]

- [RAL2024] LVIO-Fusion:Tightly-Coupled LiDAR-Visual-Inertial Odometry and Mapping in Degenerate Environments [[paper](https://ieeexplore.ieee.org/abstract/document/10452777)]


- [TIM2024] Dynam-LVIO: A Dynamic-Object-Aware LiDAR Visual Inertial Odometry in Dynamic Urban Environments [[paper](https://ieeexplore.ieee.org/document/10511062)]

- [Remote Sensing2024] LVI-Fusion: A Robust Lidar-Visual-Inertial SLAM Scheme [[paper](https://www.mdpi.com/2072-4292/16/9/1524)]





### 2023

- [TPAMI2023] SDV-LOAM: Semi-Direct Visual–LiDAR Odometry and Mapping [[paper](https://ieeexplore.ieee.org/abstract/document/10086694)][[code](https://github.com/ZikangYuan/SDV-LOAM)]

- [RAL2023] Coco-LIC: Continuous-Time Tightly-Coupled LiDAR-Inertial-Camera Odometry using Non-Uniform B-spline [[paper](https://arxiv.org/pdf/2309.09808)][[code](https://github.com/APRIL-ZJU/Coco-LIC)]

- [TM2023] CR-LDSO: Direct Sparse LiDAR-Assisted Visual Odometry With Cloud Reusing [[paper](https://ieeexplore.ieee.org/abstract/document/10071952/)]

- [TM2023] Continuous-Time Fixed-Lag Smoothing for LiDAR-Inertial-Camera SLAM [[paper](https://ieeexplore.ieee.org/abstract/document/10045587)]




### 2022

- [IROS2022] Fast and Tightly-coupled Sparse-Direct LiDAR-Inertial-Visual Odometry [[paper](https://ieeexplore.ieee.org/document/9739244)][[code](https://github.com/hku-mars/FAST-LIVO)]

- 🔥 **[ICRA2022] R3LIVE: A Robust, Real-time, RGB-colored, LiDAR-Inertial-Visual tightly-coupled state Estimation and mapping package [[paper](https://ieeexplore.ieee.org/document/9811935)][[code](https://github.com/hku-mars/r3live)]**

- [RAL2022] mvil-fusion: Monocular visual-inertial-lidar simultaneous localization and mapping in challenging environments [[paper](https://ieeexplore.ieee.org/abstract/document/9968060/)]



### 2021


- 🔥 **[RAL2021] R2LIVE: A Robust, Real-time, LiDAR-Inertial-Visual tightly-coupled state Estimator and mapping [[paper](https://github.com/hku-mars/r2live/blob/master/paper/r2live_ral_final.pdf)][[code](https://github.com/hku-mars/r2live)]**


- [IROS2021] Lvio-Fusion: A Self-adaptive Multi-sensor Fusion SLAM Framework Using Actor-critic Method [[paper](https://arxiv.org/abs/2106.06783)][[code](https://github.com/jypjypjypjyp/lvio_fusion)]


- [IROS2021] Super odometry: Imu-centric lidar-visual-inertial estimator for challenging environments [[paper](https://arxiv.org/pdf/2104.14938)][[code](https://github.com/jypjypjypjyp/lvio_fusion)]

- [WACV2021] Self-Supervised Visual-LiDAR Odometry With Flip Consistency [[paper](https://openaccess.thecvf.com/content/WACV2021/papers/Li_Self-Supervised_Visual-LiDAR_Odometry_With_Flip_Consistency_WACV_2021_paper.pdf)][[code](https://github.com/jypjypjypjyp/lvio_fusion)]


- [ICRA2021] CamVox: A Low-cost and Accurate Lidar-assisted Visual SLAM System [[paper](https://ieeexplore.ieee.org/abstract/document/9561149)][[code](https://github.com/ISEE-Technology/CamVox)]

- [ICRA2021] LVI-SAM: Tightly-coupled Lidar-Visual-Inertial Odometry via Smoothing and Mapping [[paper](https://github.com/TixiaoShan/LVI-SAM/blob/master/doc/paper.pdf)][[code](https://github.com/TixiaoShan/LVI-SAM)]

- [TIV2021] Efficient and Accurate Tightly-Coupled Visual-Lidar SLAM [[paper](https://ieeexplore.ieee.org/abstract/document/9632274)]

- [ROBIO2021] LVIO-SAM: A Multi-sensor Fusion Odometry via Smoothing and Mapping [[paper](https://ieeexplore.ieee.org/document/9739244)][[code](https://github.com/TurtleZhong/LVIO-SAM)]

- [Remote Sensing2021] DV-LOAM: Direct Visual LiDAR Odometry and Mapping [[paper](https://www.mdpi.com/2072-4292/13/16/3340)][[code](https://github.com/kinggreat24/dv-loam)]
  
### 2020
- [IROS2020] LIC-Fusion 2.0: LiDAR-Inertial-Camera Odometry with Sliding-Window Plane-Feature Tracking [[paper](https://arxiv.org/pdf/2008.07196)]

- [ICRA2020] Lidar-Monocular Visual Odometry using Point and Line Features [[paper](https://ieeexplore.ieee.org/abstract/document/9196613)]


- [Automomous Robots2020] DVL-SLAM: sparse depth enhanced direct visual-LiDAR SLAM [[paper](https://link.springer.com/article/10.1007/s10514-019-09881-0)]





### 2019
- [IROS2019] LIC-Fusion: LiDAR-Inertial-Camera Odometry [[paper](https://ieeexplore.ieee.org/xpl/conhome/8957008/proceeding)]

- [IROS2019] ViLiVO: Virtual LiDAR-Visual Odometry for an Autonomous Vehicle with a Multi-Camera System [[paper](https://ieeexplore.ieee.org/abstract/document/8968484)]



### 2018
- [IROS2018] LIMO: Lidar-Monocular Visual Odometry [[paper](https://ieeexplore.ieee.org/abstract/document/8594394)][[code](https://github.com/johannes-graeter/limo)]



### 2015
- [ICRA2015] Visual-lidar odometry and mapping: Low-drift, robust, and fast [[paper](https://frc.ri.cmu.edu/~zhangji/publications/ICRA_2015.pdf)]


## ⭐️ Related awesome lists

- [awesome-wheel-slam](https://github.com/sjtuyinjie/awesome-wheel-slam)
- [awesome-isaac-sim](https://github.com/sjtuyinjie/awesome-isaac-sim)
- [awesome-LiDAR-Camera-Calibration](https://github.com/Deephome/Awesome-LiDAR-Camera-Calibration)
- [awesome-SLAM](https://github.com/SilenceOverflow/Awesome-SLAM)
- [awesome-SLAM-datasets](https://github.com/youngguncho/awesome-slam-datasets)
- [Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)
- [awesome-humanoid-learning](https://github.com/jonyzhang2023/awesome-humanoid-learning)
- [awesome-isaac-gym](https://github.com/wangcongrobot/awesome-isaac-gym)
- [Awesome-Quadrupedal-Robots](https://github.com/curieuxjy/Awesome_Quadrupedal_Robots)
- [Awesome-Robot-Descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions)
- [awesome-legged-locomotion-learning](https://github.com/gaiyi7788/awesome-legged-locomotion-learning)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sjtuyinjie/awesome-LiDAR-Visual-SLAM&type=Timeline)](https://star-history.com/#Ashutosh00710/github-readme-activity-graph&Timeline)


