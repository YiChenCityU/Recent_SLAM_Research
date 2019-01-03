# Recent_SLAM_Research
【回馈社区】跟踪SLAM前沿动态 （2018），技术更新太快，开启paper暴走模式，精选paper包括纯视觉SLAM，三维重建，基础数学工具，导航路径规划，深度学习SLAM，激光与视觉融合等类别。

## SLAM 能力图 

<img src="https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM%E8%83%BD%E5%8A%9B%E5%9B%BE.png" width ="300" height="550" />

### 战斗吧

## Visual SLAM
#### 121. 2018-12-28-[Patch-based Stereo Direct Visual Odometry Robust to Illumination Changes](https://sci-hub.tw/https://link.springer.com/article/10.1007/s12555-018-0199-2) 光照鲁棒性
#### 120. 2018-12-28-[Observability Analysis and Performance Evaluation of EKF-based Visual-inertial Odometry with Online Intrinsic Camera Parameter Calibration](https://sci-hub.tw/10.1109/jsen.2018.2886764) 
#### 119. 2018-12-20-[Real-time 3D scene reconstruction and localization with surface optimization](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8556661)
#### 118. 2018-12-20-[A fast initialization method of Visual-Inertial Odometry based on monocular camera ](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8559929/)
#### 117. 2018-12-20-[A Weighing Euler Pre-integration Method in the Visual-Inertial Odometry](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8559725)
#### 116. 2018-12-20-[DS-SLAM: A Semantic Visual SLAM towards Dynamic Environments](https://arxiv.org/pdf/1809.08379v1.pdf) 
#### 115. 2018-12-18-[Image-based Navigation using Visual Features and Map](https://arxiv.org/pdf/1812.03795.pdf)ETH formulate the map construction and self-localizationproblems as convex quadratic and second-order cone programs,respectively
#### 114. 2018-12-18-[From Coarse to Fine: Robust Hierarchical Localization at Large Scale](https://arxiv.org/pdf/1812.03506.pdf) HF-Net, a hierarchical localization approach based on a monolithic CNN that simultaneously predicts local features and global descriptors foraccurate 6-DoF localization
#### 113. 2018-12-18-[A Complete System for Vision-Based Micro-Aerial Vehicle Mapping, Planning, and Flight in Cluttered Environments](https://arxiv.org/pdf/1812.03892.pdf) ETH Siegwart 完整的视觉定位导航方案
#### 112. 2018-12-16-[Extrinsic 6DoF Calibration of a Radar – LiDAR – Camera System Enhanced by Radar Cross Section Estimates Evaluation](https://sci-hub.tw/https://www.sciencedirect.com/science/article/pii/S0921889018301994) 相机激光毫米波雷达外参估计
#### 111. 2018-12-16-[Visual-Based SLAM Configurations for Cooperative Multi-UAV Systems with a Lead Agent: An Observability-Based Approach](https://www.ncbi.nlm.nih.gov/pubmed/30513949) 
#### 110. 2018-12-16-[Robust Visual-Inertial State Estimation with Multiple Odometries and Efficient Mapping on an MAV with Ultra-Wide FOV Stereo Vision](https://elib.dlr.de/122805/1/IROS2018_multi_VO_elib.pdf) 鱼眼相机产生的四对虚拟双目VIO
#### 109. 2018-12-11-[Flying on point clouds: Online trajectory generation and autonomous navigation for quadrotors in cluttered environments](http://sci-hub.tw/10.1002/rob.21842)
#### 108. 2018-12-11-[CubemapSLAM: A Piecewise-Pinhole Monocular Fisheye SLAM System](https://arxiv.org/pdf/1811.12633.pdf)  鱼眼镜头slam
#### 107. 2018-12-11-[HOOFR SLAM System: An Embedded Vision SLAM Algorithm and Its Hardware-Software Mapping-Based Intelligent Vehicles Applications](http://sci-hub.tw/10.1109/tits.2018.2881556)
#### 106. 2018-12-10-[PoseFusion: Dense RGB-D SLAM in Dynamic Human Environments](https://hal.archives-ouvertes.fr/hal-01893144/document) 解决动态人体
#### 105. 2018-12-07-[Depth from Motion for Smartphone AR](http://delivery.acm.org/10.1145/3280000/3275041/a193-valentin.pdf?ip=203.166.220.2&id=3275041&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1544188110_8a4090e366f371eb54025ed793523da9) google 单目深度估计，效果很好
#### 104. 2018-12-06-[Stereo Visual-Inertial SLAM With Points and Lines](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8533332) 双目ＩＭＵ加点线
#### 103. 2018-12-05-[SLAM method: reconstruction and modeling of environment with moving objects using an RGBD camera](http://ceur-ws.org/Vol-2254/10000274.pdf)去除动态物体
#### 102. 2018-11-26-[VINS-MKF: A Tightly-Coupled Multi-Keyframe Visual-Inertial Odometry for Accurate and Robust State Estimation](https://www.mdpi.com/1424-8220/18/11/4036)多目VINS
#### 101. 2018-11-26-[Fast and accurate visual odometry from a monocular camera](http://sci-hub.tw/10.1007/s11704-018-6600-8)
#### 100. 2018-11-22-[Semi-independent Stereo Visual Odometry for Different Field of View Cameras](https://hal-upec-upem.archives-ouvertes.fr/hal-01912878/document) 
#### 99. 2018-11-22-[Spherical-Model-Based SLAM on Full-View Images for Indoor Environments](https://www.mdpi.com/2076-3417/8/11/2268) 大广角视觉SLAM
#### 98. 2018-11-18-[DynaSLAM: Tracking, Mapping and Inpainting in Dynamic Scenes](https://arxiv.org/pdf/1806.05620.pdf)FCN 辅助动态场景SLAM，[代码](https://github.com/BertaBescos/DynaSLAM)
#### 97. 2018-11-18-[EMoVI-SLAM: Embedded Monocular Visual Inertial SLAM with Scale Update for Large Scale Mapping and Localization](http://sci-hub.tw/https://ieeexplore.ieee.org/document/8525794) UKF 做融合，效果比VINS好
#### 96. 2018-11-16-[Optimization-based Legged Odometry and Sensor Fusion for Legged Robot Continuous Localization](sci-hub.tw/10.1016/j.robot.2018.10.013) 足腿式机器人slam
#### 95. 2018-11-16-[RGB-D SLAM in Dynamic Environments Using Points Correlations](https://arxiv.org/pdf/1811.03217.pdf) 解决动态物体影响
#### 94. 2018-11-13-[Semi-Semantic Line-Cluster Assisted Monocular SLAM for Indoor Environments](https://arxiv.org/pdf/1811.01592.pdf)
#### 93. 2018-11-12-[Evaluation of Lightweight Local Descriptors for Level Ground Navigation with Monocular SLAM](http://sci-hub.tw/10.1007/978-3-030-03341-5_29)对比不同描述子对slam影响
#### 92. 2018-11-12-[Incremental Feature Forest for Real-Time SLAM on Mobile Devices](http://sci-hub.tw/10.1007/978-3-030-03398-9_37)
#### 91. 2018-11-12-[Structure-aware SLAM with planes and lines in man-made environmen](https://sci-hub.tw/https://www.sciencedirect.com/science/article/pii/S0167865518308663)
#### 90. 2018-11-12-[A review on graph optimization and algorithmic frameworks](https://hal.archives-ouvertes.fr/hal-01901499/file/LATEX1.PDF) 
#### 89. 2018-11-06-[Non-iterative RGB-D-inertial odometry](https://arxiv.org/pdf/1710.05502.pdf)轻量型融合
#### 88. 2018-11-06-[Dense RGB-D-Inertial SLAM with Map Deformations](https://www.doc.ic.ac.uk/~sleutene/publications/IROS2017_Laidlow.pdf) RGBD 与IMU融合
#### 87. 2018-11-06-[Autonomous flight with robust visual odometry under dynamic lighting conditions](http://sci-hub.tw/10.1007/s10514-018-9816-4)很少见到韩国人做的SLAM，好像基本不开源，这个光照鲁棒性方法就无从验证了。
#### 86. 2018-11-06-[RTAB‐Map as an open‐source lidar and visual simultaneous localization and mapping library for large‐scale and long‐term online operation](http://sci-hub.tw/10.1002/rob.21831) RTAB-MAP有更新，增加laser odom。
#### 85. 2018-10-29-[Mobile Robot Localisation and Navigation Using LEGO NXT and Ultrasonic Sensor](https://arxiv.org/pdf/1810.08816.pdf) 仅仅是好玩
#### 84. 2018-10-29-[RaD-VIO: Rangefinder-aided Downward Visual-Inertial Odometry](https://arxiv.org/pdf/1810.08704.pdf) 卡尔曼不死
#### 83. 2018-10-29-[Dynamic objects elimination in SLAM based on image fusion](http://sci-hub.tw/https://linkinghub.elsevier.com/retrieve/pii/S0167865518308523) 去除动态物体
#### 82. 2018-10-24-[Distributed stereo vision‐based 6D localization and mapping for multi‐robot teams](https://onlinelibrary.wiley.com/doi/pdf/10.1002/rob.21812) 
#### 81. 2018-10-20-[Multi-scale Direct Sparse Visual Odometry for Large-Scale Natural Environment](https://ieeexplore.ieee.org/abstract/document/8490959) 把不同远近的pixel分开来用
#### 80. 2018-10-20-[Combining 2D to 2D and 3D to 2D Point Correspondences for Stereo Visual Odometry](http://www.scitepress.org/Papers/2018/66236/66236.pdf)
#### 79. 2018-10-20-[StructVIO : Visual-inertial Odometry with Structural Regularity of Man-made Environments](https://arxiv.org/pdf/1810.06796.pdf) 加line特征
#### 78. 2018-10-17-[RGB-D Inertial Odometry for Indoor Robot via Keyframe-based Nonlinear Optimization](https://ieeexplore.ieee.org/abstract/document/8484687)
#### 77. 2018-10-17-[A Combined RGB and Depth Descriptor for SLAM with Humanoids](https://www.hrl.uni-bonn.de/papers/sheikh18iros.pdf) 结合RGB与深度的描述子，[代码还未公布](https://github.com/ferasha/DLab)
#### 76. 2018-10-15-[Analysis of the Impact of Field of View on WideAngle Cameras in SLAM](http://www.diva-portal.org/smash/get/diva2:1253260/FULLTEXT01.pdf) 一篇分析视场角对SLAM影响的硕士论文
#### 75. 2018-10-15-[Direct Depth SLAM: Sparse Geometric Feature Enhanced Direct Depth SLAM System for Low-Texture Environments](https://www.mdpi.com/1424-8220/18/10/3339/htm) 只用深度图的SLAM
#### 74. 2018-10-11-[SE(2)-Constrained Visual Inertial Fusion for Ground Vehicles](http://sci-hub.tw/10.1109/jsen.2018.2873055) 贡献：This paper proposed a new visual inertial fusion framework for ground vehicles, based on an SE(2)-constrained pose parameterization.
#### 73. 2018-10-11-[A Structureless Approach for Visual Odometry](https://ywseo.github.io/files/structureless-approach-vo-iv-18.pdf) 三点改进： 1) the complexity of our solution is lower than those of the state-of-the-art methods, 2) no extra matrix operations required to eliminate map points, 3) no need guesses on map points’ initial locations.
#### 72. 2018-10-09-[Illumination Robust Monocular Direct Visual Odometry for Outdoor Environment Mapping](https://hal.archives-ouvertes.fr/hal-01876700/document) 增强室外光照鲁棒性
#### 71. 2018-10-08-[Review of Wheeled Mobile Robots’ Navigation Problems and Application Prospects in Agriculture](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8456505) 路径规划review
#### 70. 2018-09-28-[Visual Multimodal Odometry: Robust Visual Odometry in Harsh Environments](https://ieeexplore.ieee.org/abstract/document/8468653)
#### 69. 2018-09-28-[Real-time Graph-Based 3D Reconstruction of Sparse Feature Environments for Mobile Robot Applications](https://ieeexplore.ieee.org/abstract/document/8468658)
#### 68. 2018-09-26-[Linear SLAM: Linearising the SLAM Problems using Submap Joining ](https://arxiv.org/pdf/1809.06967.pdf) 创建大地图，有代码在openslam上，但是没找到
#### 67. 2018-09-26-[Gaze Selection for Enhanced Visual Odometry During Navigation](http://www.cim.mcgill.ca/~mrl/pubs/travism/travis_manderson_crv2018.pdf) 控制机器人“眼球”看向特征点多的地方
#### 66. 2018-09-26-[GPU-accelerated feature tracking for 3D reconstruction](http://sci-hub.tw/http://www.sciencedirect.com/science/article/pii/S003039921831096X) GPU 加速
#### 65. 2018-09-25-[Navion: A 2mW Fully Integrated Real-Time Visual-Inertial Odometry Accelerator for Autonomous Navigation of Nano Drones](https://arxiv.org/pdf/1809.05780.pdf) 能耗更小的VIO系统
#### 64. 2018-09-25-[Project AutoVision: Localization and 3D Scene Perception for an Autonomous Vehicle with a Multi-Camera System](https://arxiv.org/pdf/1809.05477.pdf)
#### 63. 2018-09-17-[Efficient 2D-3D Matching for Multi-Camera Visual Localization](https://arxiv.org/pdf/1809.06445.pdf) 已有地图时，做定位.
#### 62. 2018-09-17-[DSVO: Direct Stereo Visual Odometry](https://irvlab.dl.umn.edu/sites/g/files/pua3056/f/dsvo_paper.pdf)没有双目的matching，另一个摄像头的作用是优化尺度,[代码在此](https://github.com/jiawei-mo/dsvo).
#### 61. [CVPR 2018] [Unsupervised Learning of Monocular Depth Estimation and Visual Odometry with Deep Feature Reconstruction](https://arxiv.org/pdf/1803.03893.pdf) Ian Reid出品，[代码在此](https://github.com/Huangying-Zhan/Depth-VO-Feat)。
#### 60. [CVPR 2018] [InLoc: Indoor Visual Localization with Dense Matching and View Synthesis](https://arxiv.org/pdf/1803.10368v2.pdf) 已知3Dmap做定位
#### 59. [CVPR 2018] [Polarimetric Dense Monocular SLAM](https://www.cs.sfu.ca/~pingtan/Papers/cvpr18_pdms.pdf) 偏振光传感器SLAM，[传感器原理](http://thinklucid.cn/tech-briefs/polarization-explained-sony-polarized-sensor/)
#### 58. [CVPR 2018] [Semantic Visual Localization](https://arxiv.org/pdf/1712.05773.pdf)
#### 57. [CVPR 2018] [CodeSLAM — Learning a Compact, Optimisable Representation for Dense Visual SLAM](https://arxiv.org/pdf/1804.00874v1.pdf)
#### 56. [CVPR 2018] [Fast Monte-Carlo Localization on Aerial Vehicles usingApproximate Continuous Belief Representations](https://arxiv.org/pdf/1712.05507v3.pdf) 粒子滤波viusal+IMU
#### 55. [CVPR 2018] [ICE-BA: Incremental, Consistent and Efficient Bundle Adjustment for Visual-Inertial SLAM](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_ICE-BA_Incremental_Consistent_CVPR_2018_paper.pdf)新的优化库
#### 54. [CVPR 2018] [Benchmarking 6DOF Outdoor Visual Localization in Changing Conditions](https://arxiv.org/pdf/1707.09092v3.pdf) 针对于场景变化较大时，例如四季变换的SLAM数据集
#### 53. [ICRA 2018] [Online Initialization and Automatic Camera-IMU Extrinsic Calibration for Monocular Visual-Inertial SLAM](https://ieeexplore.ieee.org/document/8460206/) 单目IMU自动标定，老铁知道比VINS好在哪里么
#### 52. [ICRA 2018] [Semi-Dense Visual-Inertial Odometry and Mapping for Quadrotors with SWAP Constraints](https://ieeexplore.ieee.org/document/8463163/)
#### 51. [ICRA 2018] [Assigning Visual Words to Places for Loop Closure Detection](https://sci-hub.tw/https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8461146) 使用GNG clustering algorithm
#### 50. [ICRA 2018] [Online Safe Trajectory Generation for Quadrotors Using Fast Marching Method and Bernstein Basis Polynomial](https://ieeexplore.ieee.org/document/8462878/) 沈老师连续两篇路径规划
#### 49. [ICRA 2018] [Trajectory Replanning for Quadrotors Using Kinodynamic Search and Elastic Optimization](https://sci-hub.tw/https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8463188)
#### 48. [ICRA 2018] [Feature-constrained Active Visual SLAM for Mobile Robot Navigation](https://sci-hub.tw/https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8460721)路径规划时候考虑特征点数量,[代码在此](https://github.com/XinkeAE/Active-ORB-SLAM2)
#### 47. [ICRA 2018] [A Monocular SLAM System Leveraging Structural Regularity in Manhattan World](https://sci-hub.tw/https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8463165)国内慢慢也有实验室开源了[原理与code](http://cvrs.whu.edu.cn/projects/Struct-PL-SLAM/)
#### 46. [ICRA 2018] [Monocular Visual Odometry Scale Recovery using Geometrical Constraint](http://sci-hub.tw/https://ieeexplore.ieee.org/document/8462902)
#### 45. [ICRA 2018] [Detection and Resolution of Motion Conflict in Visual Inertial Odometry](https://sci-hub.tw/https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8460870) 解决视觉与IMU估计值之间冲突问题
#### ----------ECCV 2018【都无代码，可惜】----------
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
#### ----------ECCV 2018 ----------
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

#### 11. [ProSLAM: Graph SLAM from a Programmer's Perspective](https://arxiv.org/pdf/1709.04377.pdf): 改变数据结构，计算资源更少https://gitlab.com/srrg-software/srrg_proslam/tree/master

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

## 路径规划导航 
#### 9. 2018-12-28-[A Minimum-energy Trajectory Tracking Controller for Four-wheeled Omni-directional Mobile Robot](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8581387)
#### 8. 2018-12-28-[An improved Frontier-Based Approach for Autonomous Exploration](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8581245)自探索
#### 7. 2018-12-28-[Autonomous Indoor Exploration Via Polygon Map Construction and Graph-Based SLAM Using Directional Endpoint Features](https://sci-hub.tw/10.1109/tase.2018.2883587)
#### 6. 2018-12-03-[Fast UAV Trajectory Optimization using Bilevel Optimization with Analytical Gradients](https://arxiv.org/pdf/1811.10753.pdf) 
#### 5. 2018-11-13-[Safe Local Exploration for Replanning in Cluttered Unknown Environments for Micro-Aerial Vehicles](https://arxiv.org/abs/1710.00604)
#### 4. 2018-11-13-[Sparse 3D Topological Graphs for Micro-Aerial Vehicle Planning](https://arxiv.org/abs/1803.04345)
#### 3. 2018-11-12-[Autonomous navigation using visual sparse map](https://project.inria.fr/ppniv18/files/2018/10/paper17.pdf)
#### 2. 2018-10-24-[Global UGV Path Planning on Point Cloud Maps Created by UAV ](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8492584)
#### 1. 2018-10-08-[Path Planning for Mobile Agents Using a Genetic Algorithm with a Direction Guided Factor](https://www.mdpi.com/2079-9292/7/10/212/htm)

## 基础工具 Basic tools 
#### 28. 2018-12-29-[Viewpoint-tolerant Place Recognition combining 2D and 3D information for UAV navigation](https://www.research-collection.ethz.ch/handle/20.500.11850/308619) 回环检测 
#### 27. 2018-12-27-[Impact of light on augmented reality](https://liu.diva-portal.org/smash/get/diva2:1272321/FULLTEXT01.pdf) 光照对AR影响
#### 26. 2018-12-20-[An Extrinsic Calibration Method for Binocular Cameras and Swing 2D Laser Rangefinder](file:///home/eason/Downloads/An%20Extrinsic%20Calibration%20Method%20for%20Binocular%20Cameras%20and%20Swing%202D%20Laser%20Rangefinder.pdf) 相机与旋转2D激光标定
#### 25. 2018-12-10-[An Iterative Nonlinear Filter Using Variational Bayesian Optimization](https://www.mdpi.com/1424-8220/18/12/4222)
#### 24. 2018-12-07-[Two-pass K Nearest Neighbor Search for Feature Tracking](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8528423) 增强的ＫＮＮ特征匹配方法
#### 23. 2018-11-22-[RLDB: Robust Local Difference Binary Descriptor with Integrated Learning-based Optimization](http://itiis.org/digital-library/manuscript/2126)
#### 22. 2018-11-22-[A FAST-BRISK Feature Detector with Depth Information](http://sci-hub.tw/https://www.mdpi.com/1424-8220/18/11/3908) 融合深度的特征点提取方法
#### 21. 2018-11-12-[Second-Order Semi-Global Stereo Matching Algorithm Based on Slanted Plane Iterative Optimization](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8497046)
#### 20. 2018-11-12-[Try to Start It! The Challenge of Reusing Code in Robotics Research](http://sci-hub.tw/10.1109/lra.2018.2878604)
#### 19. 2018-10-20-[Accurate Sparse Feature Regression Forest Learning for Real-Time Camera Relocalization](https://ieeexplore.ieee.org/abstract/document/8491017) 机器学习与特征点的混合方法做重定位
#### 18. 2018-10-20-[Four- and Seven-Point Relative Camera Pose from Oriented Features](https://ieeexplore.ieee.org/abstract/document/8490972) 利用特征点方向信息计算相对位姿
#### 17. 2018-10-08-[An improved SIFT algorithm based on adaptive fractional differential](http://sci-hub.tw/10.1007/s12652-018-1055-1) 
#### 16. 2018-10-08-[A Tutorial on Quantitative Trajectory Evaluationfor Visual(-Inertial) Odometry](http://rpg.ifi.uzh.ch/docs/IROS18_Zhang.pdf) SLAM 误差专门评测方法，终于有大佬说清楚了。[代码在此](https://github.com/uzh-rpg/rpg_trajectory_evaluation)
#### 15. 2018-10-08-[A Review of Solutions for Perspective-n-Point Problem in Camera Pose Estimation](http://iopscience.iop.org/article/10.1088/1742-6596/1087/5/052009/pdf) PnP 方法对比
#### 14. 2018-09-25-[A Versatile Method for Depth Data Error Estimation in RGB-D Sensors](http://scholar.google.com.hk/scholar_url?url=http://www.mdpi.com/1424-8220/18/9/3122/pdf&hl=zh-CN&sa=X&d=12129107753992395518&scisig=AAGBfm0q9zuCD6ER7bvEAxqrxPkqLMWukw&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:9829349442900101321:AAGBfm3Ah2enR6Y-2I_2pUfaBiohQzvJcw) 判断RGBD深度信息准确性的方法
#### 13. 2018-09-25-[Lambda Twist: An Accurate Fast Robust Perspective Three Point (P3P) Solver.](http://openaccess.thecvf.com/content_ECCV_2018/papers/Mikael_Persson_Lambda_Twist_An_ECCV_2018_paper.pdf) 更快更准的P3P方法，[代码](https://github.com/midjji/lambdatwist-p3p)
#### 12. 2018-09-18-[Adding Cues to Binary Feature Descriptors for Visual Place Recognition](https://arxiv.org/pdf/1809.06690.pdf)

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
#### 15. 2018-12-28-[Three Dimensional Reconstruction of Botanical Trees with Simulatable Geometry](https://arxiv.org/pdf/1812.08849.pdf)
#### 14. 2018-12-18-[PlaneRCNN: 3D Plane Detection and Reconstruction from a Single Image](https://arxiv.org/pdf/1812.04072.pdf) 
#### 13. 2018-12-18-[SeFM: A Sequential Feature Point Matching Algorithm for Object 3D Reconstruction](https://arxiv.org/pdf/1812.02925.pdf) 
#### 12. 2018-12-18-[REAL-TIME INDOOR SCENE RECONSTRUCTION WITH RGBD AND INERTIA INPUT](https://arxiv.org/pdf/1812.03015.pdf) 
#### 11. 2018-12-16-[Mobile-based 3D Reconstruction of Building Environment ](https://repozitorium.omikk.bme.hu/bitstream/handle/10890/5798/CCC2018-136.pdf?sequence=1)
#### 10. 2018-12-11-[Fast and Accurate Reconstruction of Pan-Tilt RGB-D Scans via Axis Bound Registration](https://arxiv.org/pdf/1812.00240.pdf)
#### 9.2018-11-28-[Accurate, dense and shading-aware multi-view stereo reconstruction using metaheuritic optimization](http://sci-hub.tw/10.1007/s11042-018-6904-6)
#### 8.2018-10-19-[BundleFusion: Real-time Globally Consistent 3D Reconstruction using On-the-fly Surface Re-integration](https://arxiv.org/pdf/1604.01093.pdf)[深度学习+三维重建，有代码](https://github.com/niessner/BundleFusion)
#### 7.2018-09-17-[Building Dense Reflectance Maps of Indoor Environments using an RGB-D Camera](http://ais.informatik.uni-freiburg.de/publications/papers/krawez18iros.pdf) 去除光源条件对重建的影响.
#### 6.2018-09-15-[Real-time High-accuracy Three-Dimensional Reconstruction with Consumer RGB-D Cameras](http://sci-hub.tw/10.1145/3182157)加入了uncertaintyaware,and local-to-global RGB-D bundle adjustment strategy 
#### 5.Object Pose Estimation from Monocular Image using Multi-View Keypoint Correspondence

#### 4.Depth Super-Resolution Meets Uncalibrated Photometric Stereo (低分辨率depth+不同光照下，同一视角高分辨率RBG => 高分辨率深度图)

#### 3. Robust 3D Surface Reconstruction in Real-Time with Localization Sensor

#### 2. EchoFusion: Tracking and Reconstruction of Objects in 4D Freehand Ultrasound Imaging without External Trackers

#### 1. PSDF Fusion: Probabilistic Signed Distance Function for On-the-fly 3D Data Fusion and Scene Reconstruction

## 深度学习（DL）+SLAM
#### 41. 2018-12-28-[Learning to Fuse Multiscale Features for Visual Place Recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8585013) 回环检测
#### 40. 2018-12-28-[Simultaneous Localization and Mapping in the Epoch of Semantics: A Survey](https://sci-hub.tw/10.1007/s12555-018-0130-x) 语义SLAM综述
#### 39. 2018-12-28-[3D-SIS: 3D Semantic Instance Segmentation of RGB-D Scans](https://arxiv.org/pdf/1812.07003.pdf)RGBD 分割
#### 38. 2018-12-28-[Deep Global-Relative Networks for End-to-End 6-DoF Visual ocalization and Odometry](https://arxiv.org/pdf/1812.07869.pdf)端到端VO
#### 37. 2018-12-28-[MID-Fusion: Octree-based Object-Level Multi-Instance Dynamic SLAM](https://arxiv.org/pdf/1812.07976.pdf)分割出动态物体 ，Andrew Davison
#### 36. 2018-12-28-[SfMLearner++: Learning Monocular Depth & Ego-Motion using Meaningful Geometric Constraints](https://arxiv.org/pdf/1812.08370.pdf) sfmLearner加强版，加入了对极约束，减少参数和模型大小
#### 35. 2018-12-18-[Unsupervised Learning of Monocular Depth Estimation with Bundle Adjustment, Super-Resolution and Clip Loss](https://arxiv.org/pdf/1812.03368.pdf) CMU Michael Kaess高清深度图恢复
#### 34. 2018-12-18-[Self-Improving Visual Odometry](https://arxiv.org/pdf/1812.03245.pdf) magic leap出品，可以线上训练网络，自我提升vo性能，厉害了！
#### 33. 2018-12-11-[Inferring Point Clouds from Single Monocular Images by Depth Intermediation](https://arxiv.org/pdf/1812.01402.pdf)
#### 32. 2018-12-10-[BA-Net: Dense Bundle Adjustment Network](https://arxiv.org/pdf/1806.04807.pdf) 
#### 31. 2018-12-06-[Matching Features without Descriptors: Implicitly Matched Interest Points (IMIPs)](https://arxiv.org/pdf/1811.10681.pdf)Davide Scaramuzza Michael Bloesch 发表不需要描述子使用CNN就能匹配特征点方法
#### 30. 2018-12-06-[DeepMapping: Unsupervised Map Estimation From Multiple Point Clouds](https://arxiv.org/pdf/1811.11397.pdf)利用深度学习做激光点云匹配
#### 29. 2018-12-03-[Loop Closure Detection with RGB-D Feature Pyramid Siamese Networks](https://arxiv.org/pdf/1811.09938.pdf) 
#### 28. 2018-12-03-[MagicVO: End-to-End Monocular Visual Odometry through Deep Bi-directional Recurrent Convolutional Neural Network](https://arxiv.org/pdf/1811.10964.pdf)端到端VO
#### 27. 2018-11-06-[Semantic Mapping with Simultaneous Object Detection and Localization](https://arxiv.org/pdf/1810.11525.pdf)
#### 26. 2018-11-06-[Real-Time RGB-D Camera Pose Estimation in Novel Scenes using a Relocalisation Cascade](https://arxiv.org/pdf/1810.12163.pdf)[随机森林做重定位](https://github.com/torrvision/spaint)
#### 25. 2018-11-06-[Anytime Stereo Image Depth Estimation on Mobile Devices](https://arxiv.org/pdf/1810.11408.pdf) [代码](https://github.com/mileyan/AnyNet)
#### 24. 2018-10-20-[Reactive Obstacle Avoidance of Monocular Quadrotors with Online Adapted Depth Prediction Network](https://www.sciencedirect.com/science/article/pii/S0925231218312074)线上自适应CNN估计深度
#### 23. 2018-10-19-[Scene Coordinate Regression with Angle-Based Reprojection Loss for Camera Relocalization](https://arxiv.org/pdf/1808.04999.pdf)同下，合在一起读，可以加强理解
#### 22. 2018-10-19-[DSAC - Differentiable RANSAC for Camera Localization](http://www.nowozin.net/sebastian/papers/brachmann2017dsac.pdf) 深度学习重定位，[代码](https://github.com/cvlab-dresden/DSAC)
#### 21. 2018-10-19-[PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization](https://arxiv.org/pdf/1505.07427.pdf) 深度学习重定位，[代码](https://github.com/alexgkendall/caffe-posenet)
#### 20. 2018-10-17-[Semantic-only Visual Odometry based on dense class-level segmentation](https://hal.archives-ouvertes.fr/hal-01874544/document)
#### 19. 2018-10-15-[Learning to Solve Nonlinear Least Squares for Dense Tracking and Mapping](https://www.doc.ic.ac.uk/~sleutene/publications/Learning_to_Solve__ECCV_camera_ready.pdf) Andrew J. Davison 的 learned optimizer
#### 18. 2018-10-09-[DS-SLAM: A Semantic Visual SLAM towards Dynamic Environments](https://arxiv.org/pdf/1809.08379.pdf) 
#### 17. 2018-10-09-[Real-Time Monocular Object-Model Aware Sparse SLAM](https://arxiv.org/pdf/1809.09149.pdf) Ian Reid
#### 16. 2018-10-08-[Efficient Constellation-Based Map-Merging for Semantic SLAM](https://arxiv.org/pdf/1809.09646.pdf)
#### 15. 2018-10-08-[Learning to Fly by MySelf:A Self-Supervised CNN-based Approach for Autonomous Navigation](http://cas.ee.ic.ac.uk/people/alk15/files/IROS_2018_drone_nav.pdf)
#### 14. 2018-10-08-[Semi-dense Stereo Matching using Dual CNNs](https://arxiv.org/pdf/1810.01369.pdf)深度估计
#### 13. 2018-10-08-[Deep Learning Based Semantic Labelling of 3D Point Cloudin Visual SLAM ](http://iopscience.iop.org/article/10.1088/1757-899X/428/1/012023/pdf) SLAM 加上点云标签[代码在此](https://github.com/qixuxiang/orb-slam2_with_semantic_label)
#### 12. 2018-10-06-[CNN-SVO: Improving the Mapping in Semi-Direct Visual OdometryUsing Single-Image Depth Prediction](https://arxiv.org/pdf/1810.01011.pdf) 用CNN 减少深度估计误差 [代码在此](https://arxiv.org/pdf/1810.01011.pdf)
#### 11. 2018-09-26-[An Orientation Factor for Object-Oriented SLAM](https://arxiv.org/pdf/1809.06977.pdf) 
#### 10. 2018-09-25 [A Variational Observation Model of 3D Object for Probabilistic Semantic SLAM](https://arxiv.org/pdf/1809.05225.pdf)
#### 9. 2018-09-25 [GANVO: Unsupervised Deep Monocular Visual Odometry and Depth Estimation with Generative Adversarial Networks](https://arxiv.org/pdf/1809.05786.pdf)
#### 8. 2018-07-25 Deep Virtual Stereo Odometry: Leveraging Deep Depth Prediction for Monocular Direct Sparse Odometry.TUM DL+DSO大作
 
#### 7. Fusion++: Volumetric Object-Level SLAM

#### 6. UnDeepVO: Monocular Visual Odometry through Unsupervised Deep Learning github:https://github.com/drmaj/UnDeepVO

#### 5. Learning-based Image Enhancement for Visual Odometry in Challenging HDR Environments

#### 4. Graph-Based Place Recognition in Image Sequences with CNN Features

#### 3. VSO: Visual Semantic Odometry

#### 2. Real-time Dense Monocular SLAM with Online Adapted Depth Prediction Network 

#### 1. DeepTAM: Deep Tracking and Mapping 
































