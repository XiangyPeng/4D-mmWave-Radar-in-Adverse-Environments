Happy to announce that our paper has been accepted by ITSC 2025!

# 4D mmWave Radar for Sensing Enhancement in Adverse Environments: Advances and Challenges
This is the repository for 4D mmWave Radar for Sensing Enhancement in Adverse Environments: Advances and Challenges

![weather](https://github.com/user-attachments/assets/7e3322d6-c121-4968-9212-3edf0432b734)       
Fig. 1: Visualization of camera, LiDAR and 4D mmWave data in rainy nighttime. The raw data is from the Dual Radar dataset. (a) shows the camera image. (b) illustrates LiDAR point clouds in blue and 4D mmWave radar (Arbe Phoenix) point clouds in red.

Abstract
------
Intelligent transportation systems require accurate and reliable sensing. However, adverse environments, such as rain, snow, and fog, can significantly degrade the performance of LiDAR and cameras. In contrast, 4D mmWave radar not only provides 3D point clouds and velocity measurements but also maintains robustness in challenging conditions. Recently, research on 4D mmWave radar under adverse environments has been growing, but a comprehensive review is still lacking. To bridge this gap, this work reviews the current research on 4D mmWave radar under adverse environments. First, we present an overview of existing 4D mmWave radar datasets encompassing diverse weather and lighting scenarios. Subsequently, we analyze current learning-based methods leveraging 4D mmWave radar to enhance performance according to different adverse conditions. Finally, the challenges and potential future directions are discussed for advancing 4D mmWave radar applications in harsh environments. To the best of our knowledge, this is the first review specifically concentrating on 4D mmWave radar in adverse environments. 

![Structure](https://github.com/user-attachments/assets/378aef5f-1525-44cb-8c56-f8cce55179a4)


Dataset
---------

## Table of Contents

- [Datasets for Perception](#datasets-for-perception)
- [Datasets for SLAM](#datasets-for-slam)
- [License](#license)

## Datasets for Perception

| Dataset           | Paper                                                                                   | Data Download                                           |
|-------------------|-----------------------------------------------------------------------------------------|---------------------------------------------------------|
| TJ4DRadSet        | TJ4DRadSet: A 4D Radar Dataset for Autonomous Driving                                    | [GitHub](https://github.com/TJRadarLab/TJ4DRadSet)      |
| K-Radar           | K-Radar: 4D Radar Object Detection for Autonomous Driving in Various Weather Conditions  | [GitHub](https://github.com/kaist-avelab/K-Radar)       |
| aiMotive          | aimotive dataset: A multimodal dataset for robust autonomous driving with long-range perception | [GitHub](https://github.com/aimotive/aimotive_dataset)  |
| Dual Radar        | Dual radar: A multi-modal dataset with dual 4d radar for autonomous driving              | [GitHub](https://github.com/adept-thu/Dual-Radar)       |
| L-RadSet          | L-radset: A long-range multimodal dataset with 4d radar for autonomous driving and its application | [GitHub](https://github.com/crrasjtu/L-RadSet)         |
| Bosch Street      | Bosch street dataset: A multi-modal dataset with imaging radar for automated driving     | _Link not available_                                    |
| MAN TruckScenes   | Man truckscenes: A multimodal dataset for autonomous trucking in diverse conditions      | [GitHub](https://github.com/TUMFTM/truckscenes-devkit)  |
| CMD               | CMD: A cross mechanism domain adaptation dataset for 3D object detection                 | [GitHub](https://github.com/im-djh/CMD)                 |
| VOD-Fog           | L4DR: Lidar-4DRadar fusion for weather-robust 3D object detection                        | [GitHub](https://github.com/ylwhxht/L4DR)               |
| V2X-Radar         | V2X-Radar: A multi-modal dataset with 4D radar for cooperative perception                | [GitHub](https://github.com/yanglei18/V2X-Radar)        |
| V2X-R             | V2X-R: Cooperative Lidar-4D Radar Fusion for 3D Object Detection with Denoising Diffusion | [GitHub](https://github.com/ylwhxht/V2X-R)              |
| ZJU-Multispectrum | RIDERS: Radar-Infrared Depth Estimation for Robust Sensing                               | [GitHub](https://github.com/MMOCKING/RIDERS)            |
| OmniHD-Scenes     | OmniHD-Scenes: A next-generation multimodal dataset for autonomous driving               | [Official Website](https://www.2077ai.com/OmniHD-Scenes) |
| WaterScenes       | Waterscenes: A multi-task 4d radar-camera fusion dataset and benchmarks for autonomous driving on water surfaces | [GitHub](https://github.com/waterscenes/waterscenes)   |

## Datasets for SLAM

| Dataset           | Paper                                                                                   | Data Download                                           |
|-------------------|-----------------------------------------------------------------------------------------|---------------------------------------------------------|
| MSC RAD4R         | Msc-rad4r: ROS-based automotive dataset with 4D radar                                     | [GitHub](https://mscrad4r.github.io/home/)             |
| NTU4DRadLM        | Ntu4dradlm: 4D radar-centric multi-modal dataset for localization and mapping             | [GitHub](https://github.com/junzhang2016/NTU4DRadLM)    |
| DIDLM             | DIDLM: A SLAM Dataset for Difficult Scenarios Featuring Infrared, Depth Cameras, LIDAR, 4D Radar, and Others under Adverse Weather, Low Light Conditions, and Rough Roads | [GitHub](https://github.com/GongWeiSheng/DIDLM)         |
| MINE4DRAD         | Autonomous Mining Transportation Systems: Integrating 4D Mmwave Radar for Enhanced Detection of Obstructed Static Objects | [GitHub](https://mscrad4r.github.io/home/)             |
| SNAIL Radar       | SNAIL Radar: A large-scale diverse benchmark for evaluating 4D-radar-based SLAM           | [GitHub](https://github.com/snail-radar/snail-radar.github.io) |
| HeRCULES          | HeRCULES: Heterogeneous Radar Dataset in Complex Urban Environment for Multi-session Radar SLAM | [Website](https://sites.google.com/view/herculesdataset) |
| NavINST           | The NavINST Dataset for Multi-Sensor Autonomous Navigation                                | [GitHub](https://navinst.github.io/)                   |

## License

Please refer to each dataset's individual license and usage terms.



Methods
---------


- ## Table of Contents

- [Overall Adverse Environments](#overall-adverse-environments)
- [Rain and Snow](#rain-and-snow)
- [Fog and Smoke](#fog-and-smoke)
- [Challenging Illumination](#challenging-illumination)
  
## Overall Adverse Environments

| Paper                                                                                   | Paper Link                                          |
|-----------------------------------------------------------------------------------------|---------------------------------------------------------|
|  K-radar: 4d radar object detection for autonomous driving in various weather conditions                                  | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/185fdf627eaae2abab36205dcd19b817-Abstract-Datasets_and_Benchmarks.html)      |
| Radarocc: Robust 3d occupancy prediction with 4d imaging radar  | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/b81d83165e3145a2e7d33bb5e33ea913-Abstract-Conference.html)       |
| RTNH+: Enhanced 4D Radar Object Detection Network using Two-Level Preprocessing and Vertical Encoding | [Paper](https://ieeexplore.ieee.org/abstract/document/10599871)       |
|  Enhanced k-radar: Optimal density reduction to improve detection performance and accessibility of 4d radar tensor-based object detection | [Paper](https://ieeexplore.ieee.org/abstract/document/10186820)       |
| Exploring Domain Shift on Radar-Based 3D Object Detection Amidst Diverse Environmental Conditions | [Paper](https://arxiv.org/abs/2408.06772)       |
| Echoes Beyond Points: Unleashing the Power of Raw Radar Data in Multi-modality Fusion | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/a8f7f12b29d9b8c227785f6b529f63b7-Abstract-Conference.html)       |
| DPFT: Dual Perspective Fusion Transformer for Camera-Radar-based Object Detection | [Paper](https://ieeexplore.ieee.org/abstract/document/10769556)       |
| Towards Robust 3D Object Detection with LiDAR and 4D Radar Fusion in Various Weather Conditions | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Chae_Towards_Robust_3D_Object_Detection_with_LiDAR_and_4D_Radar_CVPR_2024_paper.html)       |
| LiDAR-Based All-Weather 3D Object Detection via Prompting and Distilling 4D Radar | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72992-8_21)       |
| L4DR: Lidar-4DRadar fusion for weather-robust 3D object detection | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32397)       |
| Efficient 4D Radar Data Auto-labeling Method using LiDAR-based Object Detection Network | [Paper](https://ieeexplore.ieee.org/abstract/document/10588669)       |
| Availability-aware Sensor Fusion via Unified Canonical Space for 4D Radar, LiDAR, and Camera | [Paper](https://arxiv.org/abs/2503.07029)       |
| 4D RadarPR: Context-Aware 4D Radar Place Recognition in harsh scenarios | [Paper](https://www.sciencedirect.com/science/article/pii/S0924271625000383)       |
| Doracamom: Joint 3D Detection and Occupancy Prediction with Multi-view 4D Radars and Cameras for Omnidirectional Perception | [Paper](https://arxiv.org/abs/2501.15394)       |
| Human Detection from 4D Radar Data in Low-Visibility Field Conditions | [Paper](https://arxiv.org/abs/2404.05307)       |
| TransLoc4D: Transformer-based 4D Radar Place Recognition | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Peng_TransLoc4D_Transformer-based_4D_Radar_Place_Recognition_CVPR_2024_paper.html)       |

We summarize 3D object detection approaches under adverse weather on K-Radar dataset.
![experiment](https://github.com/user-attachments/assets/79282ca1-69c8-4636-b8bc-67b74a52ef9e)


## Rain and Snow

| Paper                                                                                   | Paper Link                                          |
|-----------------------------------------------------------------------------------------|---------------------------------------------------------|
| Augmented Millimeter Wave Radar and Vision Fusion Simulator for Roadside Perception | [Paper](https://www.mdpi.com/2079-9292/13/14/2729)       |
| Adaptive Training for Robust Object Detection in Autonomous Driving Environments | [Paper](https://ieeexplore.ieee.org/abstract/document/10634305)       |
|  V2X-R: Cooperative Lidar-4D Radar Fusion for 3D Object Detection with Denoising Diffusion | [Paper](https://github.com/ylwhxht/V2X-R)       |


## Fog and Smoke

| Paper                                                                                   | Paper Link                                          |
|-----------------------------------------------------------------------------------------|---------------------------------------------------------|
| TL-4DRCF: A Two-Level 4-D Radar–Camera Fusion Method for Object Detection in Adverse Weather | [Paper](https://ieeexplore.ieee.org/abstract/document/10491101)       |
| L4DR: Lidar-4DRadar fusion for weather-robust 3D object detection | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32397)       |
| Adaptive LiDAR-Radar Fusion for Outdoor Odometry Across Dense Smoke Conditions | [Paper](https://arxiv.org/abs/2403.17441)       |
| RIDERS: Radar-Infrared Depth Estimation for Robust Sensing | [Paper](https://ieeexplore.ieee.org/abstract/document/10623522)       |



## Challenging Illumination

| Paper                                                                                   | Paper Link                                          |
|-----------------------------------------------------------------------------------------|---------------------------------------------------------|
| DADAN: Dynamic-Augmented and Density-Aware Network for Accurate 3-D Object Detection With 4-D Radar | [Paper](https://ieeexplore.ieee.org/abstract/document/10847758)       |
| RCFusion: Fusing 4-D Radar and Camera With Bird’s-Eye View Features for 3-D Object Detection | [Paper](https://ieeexplore.ieee.org/abstract/document/10138035)       |
| LXL: LiDAR Excluded Lean 3D Object Detection With 4D Imaging Radar and Camera Fusion | [Paper](https://ieeexplore.ieee.org/abstract/document/10268601)       |
| MSSF: A 4D Radar and Camera Fusion Framework With Multi-Stage Sampling for 3D Object Detection in Autonomous Driving | [Paper](https://ieeexplore.ieee.org/abstract/document/10947638)       |
| HGSFusion: Radar-Camera Fusion with Hybrid Generation and Synchronization for 3D Object Detection | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32328)       |





Citation
---------

@article{peng20254d,          
  title={4D mmWave Radar in Adverse Environments for Autonomous Driving: A Survey},     
  author={Peng, Xiangyuan and Tang, Miao and Sun, Huawei and Servadei, Lorenzo and Wille, Robert},      
  journal={arXiv preprint arXiv:2503.24091},    
  year={2025}     
}


