# Recent_SLAM_Research
【回馈社区】跟踪SLAM前沿动态 （2017-2018），精选paper包括纯视觉SLAM，三维重建，基础数学工具，导航路径规划，深度学习SLAM，激光与视觉融合等类别。

## Visual SLAM
----------ECCV 2018【都无代码，可惜】----------
#### 44. 2018-09-14-[Realtime Time Synchronized Event-based Stereo](http://openaccess.thecvf.com/content_ECCV_2018/papers/Alex_Zhu_Realtime_Time_Synchronized_ECCV_2018_paper.pdf) 双目事件相机，第一家吧
#### 43. 2018-09-14-[Stereo relative pose from line and point feature triplets](http://openaccess.thecvf.com/content_ECCV_2018/papers/Alexander_Vakhitov_Stereo_relative_pose_ECCV_2018_paper.pdf) 点线结合，但是匹配的是三帧图像
#### 42. 2018-09-14-[Fast and Accurate Camera Covariance Computation for Large 3D Reconstruction](http://openaccess.thecvf.com/content_ECCV_2018/papers/Michal_Polic_Fast_and_Precise_ECCV_2018_paper.pdf) 以数学为切入点，难懂
#### 41. 2018-09-14-[Structure-from-Motion-Aware PatchMatch for Adaptive Optical Flow Estimation](http://openaccess.thecvf.com/content_ECCV_2018/papers/Daniel_Maurer_Structure-from-Motion-Aware_PatchMatch_for_ECCV_2018_paper.pdf) 三维重建方向
#### 40. 2018-09-14-[Stereo Vision-based Semantic 3D Object and Ego-motion Tracking for Autonomous Driving](http://openaccess.thecvf.com/content_ECCV_2018/papers/Peiliang_LI_Stereo_Vision-based_Semantic_ECCV_2018_paper.pdf) 沈老师出品，既估计相机位姿，也估计物体位置，对动态物体鲁棒
#### 39. 2018-09-14-[Scale-Awareness of Light Field Camera based Visual Odometry](http://openaccess.thecvf.com/content_ECCV_2018/papers/Niclas_Zeller_Scale-Awareness_of_Light_ECCV_2018_paper.pdf) 传感器特殊，使用[光场相机](https://www.zhihu.com/question/20511442/answer/24066624)
#### 38. 2018-09-14-[Semantically Aware Urban 3D Reconstruction with Plane-Based Regularization](http://openaccess.thecvf.com/content_ECCV_2018/papers/Thomas_Holzmann_Semantically_Aware_Urban_ECCV_2018_paper.pdf) 最近都很喜欢加平面信息做SLAM
#### 37. 2018-09-14-[VSO: Visual Semantic Odometry](http://openaccess.thecvf.com/content_ECCV_2018/papers/Konstantinos-Nektarios_Lianos_VSO_Visual_Semantic_ECCV_2018_paper.pdf) 题目越短，文章越牛逼？
#### 36. 2018-09-14-[Direct Sparse Odometry with Rolling Shutter](http://openaccess.thecvf.com/content_ECCV_2018/papers/David_Schubert_Direct_Sparse_Odometry_ECCV_2018_paper.pdf) 同样是Cremers出品，看题目就知道了
#### 35. 2018-09-14-[Modeling Varying Camera-IMU Time Offset in Optimization-Based Visual-Inertial Odometry](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yonggen_Ling_Modeling_Varying_Camera-IMU_ECCV_2018_paper.pdf) 科大沈老师门生根叔出品，解决了卷帘快门问题，加速IMU预积分，以及使初始化更鲁棒，AR界梦寐以求的算法，可惜没代码
#### 34. 2018-09-14-[Deep Virtual Stereo Odometry:Leveraging Deep Depth Prediction for Monocular Direct Sparse Odometry](http://openaccess.thecvf.com/content_ECCV_2018/papers/Nan_Yang_Deep_Virtual_Stereo_ECCV_2018_paper.pdf)  Cremers出品，用单目深度估计+DSO 
#### 33. 2018-09-14-[Good Line Cutting: towards Accurate Pose Tracking of Line-assisted VO/VSLAM](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yipu_Zhao_Good_Line_Cutting_ECCV_2018_paper.pdf) 对于线特征提取线内信息最多的一段做SLAM，声称对低纹理，运动模糊鲁棒
#### 32. 2018-09-14-[Linear RGB-D SLAM for Planar Environments](http://openaccess.thecvf.com/content_ECCV_2018/papers/Pyojin_Kim_Linear_RGB-D_SLAM_ECCV_2018_paper.pdf) 卡尔曼滤波估计位姿与平面特征 
----------ECCV 2018 ----------
#### 31. 2018-09-10-Monocular Object and Plane SLAM in Structured Environments. 约束中加入识别的物体与平面
#### 30. DOVO: Mixed Visual Odometry Based on Direct Method and Orb Feature: 通过特征点个数判断用直接法与光流法。交替使用

#### 29. UFSM_VO: STEREO ODOMETRY BASED ON UNIFORMLY FEATURE SELECTION AND STRICTLY CORRESPONDENCE MATCHING： 创新度一般

#### 28. A Review of Visual-Inertial Simultaneous Localization and Mapping from Filtering-Based and Optimization-Based Perspectives： VINSLAM 综述

#### 27. A Loop Closure Detection Algorithm in Dynamic Scene： 动态环境下回环检测

#### 26. Directional grid maps: modeling multimodal angular uncertainty in dynamic environments

#### 25. Grid Map Guided Indoor 3D Reconstruction for Mobile Robots with RGB-D Sensors

#### 24. Robustness Improvement of Long Range Landmark Tracking for Mobile Robots

#### 23. Lightweight Visual Odometry for Autonomous Mobile Robots

#### 22. Enhanced Visual Loop Closing for Laser-Based SLAM 

#### 21. A Fast Stereo Visual-Inertial Odometry for MAVs

#### 20. Low-Cost Multiple-MAV SLAM Using Open Source Software

#### 19. PCR-Pro: 3D Sparse and Different Scale Point Clouds Registration and Robust Estimation of Information Matrix For Pose Graph SLAM https://sites.google.com/view/pcr-pro

#### 18. Comparison of two different objective functions in 2D point feature SLAM

#### 17. Pose Estimation with Dual Quaternions and Iterative Closest Point 

#### 16. SLAMBench2: Multi-Objective Head-to-Head Benchmarking for Visual SLAM https://github.com/pamela-project/slambench2

#### 15. Estimating Metric Poses of Dynamic Objects Using Monocular Visual-Inertial Fusion

#### 14. Data-Efficient Decentralized Visual SLAM  https://github.com/uzh-rpg/dslam_open

#### 13. Direct Sparse Visual-Inertial Odometry using Dynamic Marginalization 

#### 12. A General Framework for Flexible Multi-Cue Photometric Point Cloud Registration : https://gitlab.com/srrg-software/srrg_mpr

#### 11. ProSLAM: Graph SLAM from a Programmer's Perspective: 改变数据结构，计算资源更少https://gitlab.com/srrg-software/srrg_proslam/tree/master

#### 10. DS-PTAM: Distributed Stereo Parallel Tracking and Mapping SLAM System

#### 9. A Robust and Accurate Simultaneous Localization and Mapping System for RGB-D Cameras

#### 8. Online Photometric Calibration of Auto Exposure Video for Realtime Visual Odometry and SLAM （对于光照变化很鲁棒）

#### 7. Direct Sparse Odometry with Rolling Shutter

#### 6. Online Temporal Calibration for Monocular Visual-Inertial Systems

#### 5. PL-VIO: Tightly-Coupled Monocular Visual–Inertial Odometry Using Point and Line Features 

#### 4. Gaoxiang: LDSO: Direct Sparse Odometry with Loop Closure  带有回环检测的DSO

#### 3. MULTICOL-SLAM - A MODULAR REAL-TIME MULTI-CAMERA SLAM SYSTEM

#### 2. Loosely-Coupled Semi-Direct Monocular SLAM

#### 1. Absolute Orientation and Localization Estimation from an Omnidirectional Image 


## 基础工具 Basic tools 

#### 11. An Improved RANSAC Algorithm for Simultaneous Localization and Mapping

#### 10. Baidu Apollo Auto-Calibration System - An Industry-Level Data-Driven and Learning based Vehicle Longitude Dynamic Calibrating Algorithm

#### 9.RES-Q: Robust Outlier Detection Algorithm for Fundamental Matrix Estimation

#### 8.Fast and robust local feature extraction for 3D reconstruction

#### 7.Matrix Difference in Pose-Graph Optimization https://gitlab.com/srrg-software/srrg_g2o_chordal_plugin 

#### 6. Nonlinear Distortion Calibration of an Optical Flow Sensor for Monocular Visual Odometry

#### 5. Five-point algorithm: an efficient cloud-based FPGA implementation

#### 4. SC-RANSAC: Spatial consistency on RANSAC 

#### 3.Towards A Deep Insight into Landmark-based Visual Place Recognition: Methodology and Practice 

#### 2. In Defense of Relative Multi-View Geometry

#### 1. MatchBench: An Evaluation of Feature Matchers 

## 视觉激光融合 Fusion of visual and laser 

#### 3. Laser-visual-inertial odometry and mapping with high robustness and low drift1

#### 2. ROBUST LOOP CLOSURES FOR SCENE RECONSTRUCTION BY COMBINING ODOMETRY AND VISUAL CORRESPONDENCES （RGBD+odometry 做回环检测）https://www.youtube.com/watch?v=peXrP374MVI https://github.com/zlaskar/Robust-Loop-Closures

#### 1.Scale Correct Monocular Visual Odometry Using a LiDAR Altimeter

## 三维重建 3D reconstruction 
#### 6.2018-09-15-[Real-time High-accuracy Three-Dimensional Reconstruction with Consumer RGB-D Cameras](http://sci-hub.tw/10.1145/3182157)加入了uncertaintyaware,and local-to-global RGB-D bundle adjustment strategy 
#### 5.Object Pose Estimation from Monocular Image using Multi-View Keypoint Correspondence

#### 4.Depth Super-Resolution Meets Uncalibrated Photometric Stereo (低分辨率depth+不同光照下，同一视角高分辨率RBG => 高分辨率深度图)

#### 3. Robust 3D Surface Reconstruction in Real-Time with Localization Sensor

#### 2. EchoFusion: Tracking and Reconstruction of Objects in 4D Freehand Ultrasound Imaging without External Trackers

#### 1. PSDF Fusion: Probabilistic Signed Distance Function for On-the-fly 3D Data Fusion and Scene Reconstruction

## 深度学习（DL）+SLAM
#### 8. 2018-07-25 Deep Virtual Stereo Odometry: Leveraging Deep Depth Prediction for Monocular Direct Sparse Odometry.TUM DL+DSO大作
 
#### 7. Fusion++: Volumetric Object-Level SLAM

#### 6. UnDeepVO: Monocular Visual Odometry through Unsupervised Deep Learning github:https://github.com/drmaj/UnDeepVO

#### 5. Learning-based Image Enhancement for Visual Odometry in Challenging HDR Environments

#### 4. Graph-Based Place Recognition in Image Sequences with CNN Features

#### 3. VSO: Visual Semantic Odometry

#### 2. Real-time Dense Monocular SLAM with Online Adapted Depth Prediction Network 

#### 1. DeepTAM: Deep Tracking and Mapping 











































