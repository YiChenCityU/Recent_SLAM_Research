
# Recent_SLAM_Research_2020
【回馈社区】跟踪SLAM前沿动态[2019](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM_Research_2019.md), [2018版](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM_Research_2018.md) .去年大概收录了500篇关于SLAM的论文，因为本人在企业重点研究的是VSLAM以及多传感器融合，所以并没有把全部论文精读，难免有漏的或者差的。今年重点是求精以及做好分类，继续做好本圈儿的服务工作。
欢迎在Issues里发布招聘信息。
### ------------ ICRA 2020 
### ------------ ICRA 2020 终止线 ----------
### ------------ CVPR 2020 
### ------------ CVPR 2020 终止线 ----------
### ------------ ECCV 2020 
### ------------ ECCV 2020 终止线 ----------
### ------------ IROS 2020 
### ------------ IROS 2020 终止线 ----------
### ------------ ICCV 2020 
### ------------ ICCV 2020 终止线 ----------

### SLAM
#### 1. [Semantic SLAM] 2020-01-13-[Visual Semantic SLAM with Landmarks for Large-Scale Outdoor Environment](https://arxiv.org/pdf/2001.01028.pdf)  Only label the point clouds with semantic segmentation info, no improvement in accuarcy. [code](https://github.com/1989Ryan/Semantic_SLAM/)
#### 2. [Calibration] 2020-01-13-[A Generalized Framework for Autonomous Calibration of Wheeled Mobile Robots](https://arxiv.org/pdf/2001.01555.pdf) 
#### 3. [VSLAM] 2020-01-13-[Trained Trajectory based Automated Parking System using Visual SLAM](https://arxiv.org/pdf/2001.02161.pdf) 
#### 4. [Deep SLAM] 2020-01-13-[AD-VO: SCALE-RESILIENT VISUAL ODOMETRY USING ATTENTIVE DISPARITY MAP](https://arxiv.org/pdf/2001.02090.pdf)  Learned based frame to frame VO with the input as disparity map.
#### 5. [Lidar Deep SLAM] 2020-01-13-[CAE-LO: LiDAR Odometry Leveraging Fully Unsupervised Convolutional Auto-Encoder for Interest Point Detection and Feature Description](https://arxiv.org/pdf/2001.01354.pdf) Auto-Encoder based LiDAR Odometry (CAE-LO) that detects interest points from spherical ring data using 2D CAE and extracts features from multi-resolution voxel model using 3D CAE.  [code](https://github.com/SRainGit/CAE-LO) 
#### 6. [VSLAM] 2020-01-13-[Good Feature Matching: Towards Accurate, Robust VO/VSLAM with Low Latency](https://arxiv.org/pdf/2001.00714.pdf) Introduction of an efficient good feature selection algorithm using the Max-logDet metric, which is an order of magnitude faster than state-of-the-art feature selection approaches. [code](https://github.com/ivalab/GF_ORB_SLAM)  
#### 7. [VSLAM] 2020-01-13-[Direct Sparse Visual-Inertial Odometry with Stereo Cameras](https://candyguo.github.io/files/1.pdf) Quantitative evaluation demonstrates that the proposed Stereo VI-DSO is superior to Stereo DSO both in terms of tracking accuracy and robustness. But the result is worse than VINS.
#### 8. [VSLAM] 2020-01-14-[Accurate Line Reconstruction for Point and Line-Based Stereo Visual Odometry](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8936964) 
#### 9. [VSLAM] 2020-01-14-[A Stereo Visual-Inertial SLAM Approach for Indoor Mobile Robots in Unknown Environments Without Occlusions](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8937551) Use one-circle feature-matching method, which refers to a sequence of the circle matching for the time after space (STCM), and an STCM-based visual-inertial simultaneous localization and mapping (STCM-SLAM) technique.
#### 10. [Lidar Seg] 2020-01-14-[Multi-Scale Point-Wise Convolutional Neural Networks for 3D Object Segmentation From LiDAR Point Clouds in Large-Scale Environments](https://ieeexplore.ieee.org/abstract/document/8943956/authors#authors) 
#### 11. [Review] 2020-01-14-[Multi-Sensor Fusion in Automated Driving: A Survey](https://sci-hub.tw/10.1109/ACCESS.2019.2962554) 
#### 12. [Lidar Deep SLAM] 2020-01-14-[SLOAM: Semantic Lidar Odometry and Mapping for Forest Inventory](https://arxiv.org/pdf/1912.12726.pdf) 
#### 13. [Deep SLAM] 2020-01-22-[Learning Topometric Semantic Maps from Occupancy Grids](https://arxiv.org/pdf/2001.03676.pdf) 2D laser semantic map. 
#### 14. [VSLAM] 2020-01-22-[Temporal Delay Estimation of Sparse Direct Visual Inertial Odometry for Mobile Robots](https://sci-hub.tw/https://doi.org/10.1016/j.jfranklin.2019.11.075) Calibrate the time offset between IMU and Camera.
#### 15. [IMU] 2020-02-06-[A Lightweight and Accurate Localization Algorithm Using Multiple Inertial Measurement Units](https://sci-hub.tw/10.1109/LRA.2020.2969146) The overall performance of SLAM can be further improved by using multiple IMUs. 
#### 16. [Lidar SLAM] 2020-02-10-[Localization of Map Changes by Exploiting SLAM Residuals](https://link.springer.com/chapter/10.1007/978-3-030-40605-9_27) identify changes in maps constructed by SLAM.
#### 17. [VSLAM] 2020-02-10-[Bidirectional Trajectory Computation for Odometer-Aided Visual-Inertial SLAM](https://arxiv.org/pdf/2002.00195.pdf) not only solves the problem of the unobservability of accelerometer bias and extrinsic parameters before the first turning, but also results in more accurate trajectories in comparison with the state-of-the-art approaches.
#### 18. [EKF] 2020-02-10-[A Code for Unscented Kalman Filtering on Manifolds (UKF-M)](https://arxiv.org/pdf/2002.00878.pdf) a novel methodology for Unscented Kalman Filtering (UKF) on manifolds that extends our previous work about UKF on Lie groups.
#### 19. [New sensor] 2020-02-10-[Corners positioning for binocular ultra-wide angle long-wave infrared camera calibration](https://www.sciencedirect.com/science/article/abs/pii/S0030402619313397) calibrating binocular ultra-wide angle long-wave infrared camera.
#### 20. [VSLAM] 2020-02-12-[Kimera: an Open-Source Library for Real-Time Metric-Semantic Localization and Mapping](https://arxiv.org/pdf/1910.02490.pdf) VIO + Dense mapping + Semantic 
#### 21. [Semantic] 2020-02-12-[Edge Assisted Mobile Semantic Visual SLAM](http://tns.thss.tsinghua.edu.cn/~jingao/papers/infocom20_edgeSLAM.pdf) edgeSLAM leverages the state-of-the-art semantic segmentation algorithm to enhance localization and mapping accuracy, and speeds up the computation-intensive SLAM and semantic segmentation algorithms by computation offloading.
#### 22. [lidar SLAM] 2020-02-12-[Online LiDAR-SLAM for Legged Robots with Robust Registration and Deep-Learned Loop Closure](https://arxiv.org/pdf/2001.10249.pdf)In this paper, we present a factor-graph LiDARSLAM system which incorporates a state-of-the-art deeply learned feature-based loop closure detector to enable a legged robot to localize and map in industrial environments. 
#### 23. [Semantic] 2020-02-14-[Tightly Coupled Semantic RGB-D Inertial Odometry for Accurate Long-Term Localization and Mapping](https://ieeexplore.ieee.org/abstract/document/8981658) utilize semantically enhanced feature matching and visual inertial bundle adjustment to improve the robustness of odometry especially in feature-sparse environments.
#### 24. [VIO] 2020-02-14-[Visual-Inertial Ego-Motion Estimation using Rolling-Shutter Camera in autonomous driving](https://pdfs.semanticscholar.org/3c90/940d1572789aa6459e443bede87fdfcb8b86.pdf) interpolate the IMU pose between consecutive poses and set up a novel feature measurement error model to cover the time delay issues. 
#### 25. [VIO] 2020-02-14-[EIP-VIO: Edge-Induced Points Based Monocular Visual-Inertial Odometry](https://ieeexplore.ieee.org/abstract/document/8982582) propose an improved and practical monocular visual-inertial odometry method based on selective edge points.
#### 26. [Event camera] 2020-02-14-[Sepia, Tarsier, and Chameleon: A Modular C++ Framework for Event-Based Computer Vision](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6960268/) A framework to process Event camera.  [code]( https://github.com/neuromorphic-paris/tutorials)
#### 27. [Multimodal localization] 2020-02-14-[Multimodal localization: Stereo over LiDAR map](https://sci-hub.tw/https://doi.org/10.1002/rob.21936) Visual localization in lidar map. 
#### 28. [2D SLAM] 2020-02-15-[x A Triangle Feature Based Map-to-map Matching and Loop Closure for 2D Graph SLAM](https://sci-hub.tw/10.1109/ROBIO49542.2019.8961777)  We propose a geometric environment descriptor called a Triangle Feature (TF). It exploits the Euclidean distance constraint any three feature points in a submap can form.
#### 29. [Doctor paper] 2020-02-15-[Enabling Robust State Estimation through Covariance Adaptation ](https://www.researchgate.net/profile/Ryan_Watson7/publication/338595333_Enabling_Robust_State_Estimation_through_Covariance_Adaptation/links/5e1ec497299bf136303af241/Enabling-Robust-State-Estimation-through-Covariance-Adaptation.pdf) 
#### 30. [Multirobots] 2020-02-15-[Statistical Outlier Identification in Multi-robot Visual SLAM using Expectation Maximization](https://arxiv.org/pdf/2002.02638.pdf) This paper presents a probabilistic approach for detecting incorrect orientation measurements prior to pose graph optimization by checking the geometric consistency of rotation measurements. 
#### 31. [Math] 2020-02-15-[New approach to calculating the fundamental matrix](https://search.proquest.com/openview/7a8ffa8ef7031b50a8b9b2a7fe041f6b/1?pq-origsite=gscholar&cbl=1686344)
#### 32. [Math] 2020-02-16-[IMPROVING THE APPLICABILITY OF VISUAL SLAM WITH SUBMODULAR SUBMATRIX SELECTION](https://smartech.gatech.edu/bitstream/handle/1853/62276/ZHAO-DISSERTATION-2019.pdf) 
#### 33. [VSLAM] 2020-02-16-[DeepFactors: Real-Time Probabilistic Dense Monocular SLAM](https://arxiv.org/pdf/2001.05049.pdf) use of a learned compact depth map representation and reformulating three different types of errors: photometric, reprojection and geometric, which we make use of within standard factor graph software. [code](https://github.com/jczarnowski/DeepFactors)
#### 34. [VSLAM] 2020-02-16-[Direct Visual-Inertial Ego-Motion Estimationv via Iterated Extended Kalman Filter](https://arxiv.org/pdf/2001.05215.pdf)
#### 35. [VSLAM] 2020-02-16-[Multi-object Monocular SLAM for Dynamic Environments](https://arxiv.org/pdf/2002.03528.pdf)
#### 36. [LOOP] 2020-02-16-[Hierarchical Multi-Process Fusion for Visual Place Recognition](https://arxiv.org/pdf/2002.03895.pdf)
#### 37. [2D LSLAM] 2020-02-21-[GP-SLAM: laser-based SLAM approach based on regionalized Gaussian process map reconstruction](https://sci-hub.tw/https://doi.org/10.1007/s10514-020-09906-z)
#### 38. [RGBD SLAM] 2020-02-21-[Accurate and Robust RGB-D Dense Mapping with Inertial Fusion and Deformation-Graph Optimization](https://ieeexplore.ieee.org/abstract/document/8995400/authors#authors)
#### 39. [VSLAM] 2020-03-02-[Dynamic SLAM: The Need For Speed](https://arxiv.org/pdf/2002.08584.pdf)feature-based, model-free, object-aware dynamic SLAM algorithm that exploits semantic segmentation to allow estimation of motion of rigid objects in a scene without the need to estimate the object poses or have any prior knowledge of their 3D models.
#### 40. [VSLAM] 2020-03-04-[Monocular Direct Sparse Localization in a Prior 3D Surfel Map](https://arxiv.org/pdf/2002.09923.pdf) tracking the pose of a monocular camera in a prior surfel map.
#### 41. [Semantic slam] 2020-03-04-[Comparing View-Based and Map-Based Semantic Labelling in Real-Time SLAM](https://arxiv.org/pdf/2002.10342.pdf) 
#### 42. [Math] 2020-03-04-[Least Squares Optimization: from Theory to Practice](https://arxiv.org/pdf/2002.11051.pdf) a unified methodology to design and develop efficient Least-Squares Optimization algorithms, focusing on the structures and patterns of each specific domain.[code](https://github.com/srrg-sapienza/srrg2_solver)
#### 43. [RGBD] 2020-03-04-[Perception in the Dark—Development of a ToF Visual Inertial Odometry System](https://www.mdpi.com/1424-8220/20/5/1263)  [code](https://github.com/HKPolyU-UAV/TOF-VIO)
#### 44. [Event Camera] 2020-03-04-[Robust Feature Tracking in DVS Event Stream using Bezier Mapping](http://openaccess.thecvf.com/content_WACV_2020/papers/Seok_Robust_Feature_Tracking_in_DVS_Event_Stream_using_Bezier_Mapping_WACV_2020_paper.pdf) 
#### 45. [Deep SLAM] 2020-03-05-[Self-Supervised Deep Pose Corrections for Robust Visual Odometry](https://arxiv.org/pdf/2002.12339.pdf) uses data-driven learning to regress pose corrections that account for systematic errors due to violations of modelling assumptions. [code](https://github.com/utiasSTARS/ss-dpc-net)
#### 46. [Doctor thesis] 2020-03-05-[Custom hardware architectures for embedded high-performance and low-power SLAM](https://spiral.imperial.ac.uk/bitstream/10044/1/76491/1/Boikos-K-2019-PhD-Thesis.pdf)
#### 47. [VSLAM] 2020-03-05-[Visual Camera Re-Localization from RGB and RGB-D Images Using DSAC](https://arxiv.org/pdf/2002.12324.pdf)
#### 48. [Deep SLAM] 2020-03-09-[D3VO: Deep Depth, Deep Pose and Deep Uncertainty for Monocular Visual Odometry](https://arxiv.org/pdf/2003.01060.pdf)
#### 49. [VSLAM] 2020-03-09-[Closed-Loop Benchmarking of Stereo Visual-Inertial SLAM Systems: Understanding the Impact of Drift and Latency on Tracking Accuracy](https://arxiv.org/pdf/2003.01317.pdf)
#### 50. [Deep SLAM] 2020-03-09-[MVP: Unified Motion and Visual Self-Supervised Learning for Large-Scale Robotic Navigation](https://arxiv.org/pdf/2003.00667.pdf)
#### 51. [LOOP] 2020-03-09-[Augmenting Visual Place Recognition with Structural Cues](https://arxiv.org/pdf/2003.00278.pdf)
#### 52. [VSLAM] 2020-03-09-[Robust tightly coupled pose estimation based on monocular vision, inertia, and wheel speed](https://arxiv.org/pdf/2003.01496.pdf)
#### 53. [VSLAM] 2020-03-09-[Plug-and-Play SLAM: A Unified SLAM Architecture for Modularity and Ease of Use](https://arxiv.org/pdf/2003.00754.pdf) [code](https://github.com/srrg-sapienza/srrg2_slam_interfaces)
#### 54. [VSLAM] 2020-03-09-[MiniVO: Minimalistic Range Enhanced Monocular System for Scale Correct Pose Estimation](https://www.researchgate.net/publication/339629457_MiniVO_Minimalistic_Range_Enhanced_Monocular_System_for_Scale_Correct_Pose_Estimation) [code](https://gitlab.com/Giubilato/alti-cam-calib)
#### 55. [VSLAM] 2020-03-09-[Robust Visual-Inertial Integrated Navigation System  Aided by Online Sensor Model Adaption for  Autonomous Ground Vehicles in Urban Areas](https://www.preprints.org/manuscript/202003.0018/v1)
#### 56. [VSLAM] 2020-03-16-[StereoNeuroBayesSLAM: A Neurobiologically Inspired Stereo Visual SLAM System Based on Direct Sparse Method](https://arxiv.org/pdf/2003.03091.pdf)
#### 57. [Math] 2020-03-16-[Bundle Adjustment on a Graph Processor](https://arxiv.org/pdf/2003.03134.pdf)
#### 58. [VSLAM] 2020-03-16-[Voxel Map for Visual SLAM](https://arxiv.org/pdf/2003.02247.pdf)
#### 59. [LSLAM] 2020-03-16-[LiDAR Inertial Odometry Aided Robust LiDAR Localization System in Changing City Scenes](https://songshiyu01.github.io/pdf/LIO_W.Ding_S.Song_ICRA2020.pdf)
#### 60. [VSLAM] 2020-03-16-[Redesigning SLAM for Arbitrary Multi-Camera Systems](https://arxiv.org/pdf/2003.02014.pdf)
#### 61. [VSLAM] 2020-03-19-[DymSLAM:4D Dynamic Scene Reconstruction Based on Geometrical Motion Segmentation](https://arxiv.org/pdf/2003.04569.pdf)
#### 62. [LSALM] 2020-03-19-[Tightly-coupled Fusion of Global Positional Measurements in Optimization-based Visual-Inertial Odometry](https://arxiv.org/pdf/2003.04159.pdf)
#### 63. [VSLAM] 2020-03-19-[FlowFusion: Dynamic Dense RGB-D SLAM Based on Optical Flow](https://arxiv.org/pdf/2003.05102.pdf)
#### 64. [VSLAM] 2020-03-19-[Inertial-Only Optimization for Visual-Inertial Initialization](https://arxiv.org/pdf/2003.05766.pdf)
#### 65. [VSLAM] 2020-03-19-[Extrinsic Calibration of Multiple RGB-D Cameras Based on Descriptor-based Patterns](https://arxiv.org/pdf/1807.07856v2.pdf)
#### 66. [VSLAM] 2020-03-19-[SD-VIS: A Fast and Accurate Semi-Direct Monocular Visual-Inertial Simultaneous Localization and Mapping (SLAM)](https://www.mdpi.com/1424-8220/20/5/1511/htm)
#### 67. [Calibration] 2020-03-19-[A fast calibration approach for onboard LiDAR-camera systems](https://journals.sagepub.com/doi/pdf/10.1177/1729881420909606)
#### 68. [Edge SLAM] 2020-03-24-[Robust Monocular Edge Visual Odometry through Coarse-to-Fine Data Association](https://www.researchgate.net/publication/336056167_Robust_Monocular_Edge_Visual_Odometry_through_Coarse-to-Fine_Data_Association?_esc=publicationCoverPdf&el=1_x_3&enrichId=rgreq-82bc69ebf992513f26edb9e73f9e23eb-XXX&enrichSource=Y292ZXJQYWdlOzMzNjA1NjE2NztBUzo4Njk4NTc1Mjg2NTU4NzJAMTU4NDQwMTYwNDEyNQ%3D%3D)
#### 69. [Math] 2020-03-24-[Learning 2D–3D Correspondences To Solve The Blind Perspective-n-Point Problem](https://arxiv.org/pdf/2003.06752.pdf)
#### 70. [LSLAM] 2020-03-24-[An Experimental Evaluation of Robustness and Precision for Long-term LiDAR-based Localization in Highly Changing Environments](https://arxiv.org/pdf/2003.07726.pdf)
#### 71. [AR] 2020-03-24-[A novel augmented reality framework based on monocular semi-dense simultaneous localization and mapping](https://sci-hub.tw/https://doi.org/10.1002/cav.1922)
#### 72. [VSLAM] 2020-04-03-[OmniSLAM: Omnidirectional Localization and Dense Mapping for Wide-baseline Multi-camera Systems](https://arxiv.org/pdf/2003.08056.pdf)
#### 73. [VSLAM] 2020-04-03-[Monocular Visual–Inertial SLAM Algorithm Combined with Wheel Speed Anomaly Detection](https://arxiv.org/pdf/2003.09901.pdf)
#### 74. [VSLAM] 2020-04-07-[Removing Dynamic Objects for Static Scene Reconstruction using Light Fields](https://arxiv.org/pdf/2003.11076.pdf)
#### 75. [VSLAM] 2020-04-07-[Multi-camera visual SLAM for off-road navigation](https://www.sciencedirect.com/science/article/pii/S0921889019308711)
#### 76. [VSLAM] 2020-04-07-[Long-Term Loop Closure Detection through Visual-Spatial Information Preserving Multi-Order Graph Matching](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-GaoP.6907.pdf)
#### 77. [VSLAM] 2020-04-13-[Coupling of localization and depth data for mapping using Intel RealSense T265 and D435i cameras](https://arxiv.org/pdf/2004.00269.pdf)
#### 78. [Calibration] 2020-04-13-[On-the-Fly Camera and Lidar Calibration](https://www.mdpi.com/2072-4292/12/7/1137/pdf)
#### 79. [Event Camera] 2020-04-13-[Single Image Optical Flow Estimation with an Event Camera](https://arxiv.org/pdf/2004.00347.pdf)
#### 80. [VSLAM] 2020-04-13-[Monocular Camera Localization in Prior LiDAR Maps with 2D-3D Line Correspondences](https://arxiv.org/pdf/2004.00740.pdf) [code](https://github.com/levenberg/2D-3D-pose-tracking)
#### 81. [Fusion] 2020-04-13-[Scene-Aware Error Modeling of LiDAR/Visual Odometry for Fusion-based Vehicle Localization](https://arxiv.org/pdf/2003.13109.pdf)
#### 82. [Dataset] 2020-04-13-[TartanAir: A Dataset to Push the Limits of Visual SLAM](https://arxiv.org/pdf/2003.14338.pdf)
#### 83. [VSLAM] 2020-04-13-[ClusterVO: Clustering Moving Instances and Estimating Visual Odometry for Self and Surroundings](https://arxiv.org/pdf/2003.12980.pdf)
#### 84. [DeepSLAM] 2020-04-13-[DeepSLAM: A Robust Monocular SLAM System with Unsupervised Deep Learning](https://ieeexplore.ieee.org/abstract/document/9047170)
#### 85. [Fusion] 2020-04-13-[Tightly-coupled Fusion of Global Positional Measurements in Optimization-based Visual-Inertial Odometry](https://arxiv.org/pdf/2003.04159.pdf)
#### 86. [GPU] 2020-04-13-[Faster than FAST: GPU-Accelerated Frontend for High-Speed VIO](https://arxiv.org/pdf/2003.13493.pdf) [code](https://github.com/uzh-rpg/vilib)
#### 87. [Descriptor] 2020-04-27-[BEBLID: Boosted Efficient Binary Local Image Descriptor](https://sci-hub.tw/https://doi.org/10.1016/j.patrec.2020.04.005) [code](https://github.com/iago-suarez/BEBLID)
#### 88. [Doctor thesis] 2020-04-27-[Robust Visual SLAM in Challenging Environments with low-texture and Dynamic Illumination](https://riuma.uma.es/xmlui/bitstream/handle/10630/19479/TD_GOMEZ_OJEDA_Ruben.pdf?sequence=1&isAllowed=y)
#### 89. [LSLAM] 2020-04-27-[CAE-LO: LiDAR Odometry Leveraging Fully Unsupervised Convolutional Auto-Encoder for Interest Point Detection and Feature Description](https://arxiv.org/pdf/2001.01354.pdf) [code](https://github.com/SRainGit/CAE-LO)
#### 90. [VSLAM] 2020-04-27-[Object-oriented SLAM using Quadrics and Symmetry Properties for Indoor Environments](https://arxiv.org/pdf/2004.05303.pdf)
#### 91. [VSLAM] 2020-04-27-[Online Initialization and Extrinsic Spatial-Temporal Calibration for Monocular Visual-Inertial Odometry](https://arxiv.org/pdf/2004.05534.pdf)
#### 92. [VSLAM] 2020-04-27-[Latency Compensated Visual-Inertial Odometry for Agile Autonomous Flight](https://www.researchgate.net/publication/340650710_Latency_Compensated_Visual-Inertial_Odometry_for_Agile_Autonomous_Flight)
#### 93. [Descriptor] 2020-04-27-[Visual Descriptor Learning from Monocular Video](https://arxiv.org/pdf/2004.07007.pdf)

### 3D Reconstruction
#### 1. [Automatically explore] 2020-01-14-[Plan3D: Viewpoint and Trajectory Optimization for Aerial Multi-View Stereo Reconstruction](https://sci-hub.tw/https://doi.org/10.1145/3233794)
#### 2. [laser reconstruction] 2020-02-14-[Real-Time 3D Reconstruction of Thin Surface Based on Laser Line Scanner](https://www.researchgate.net/publication/338707435_Real-Time_3D_Reconstruction_of_Thin_Surface_Based_on_Laser_Line_Scanner) 
#### 3. [Deep Reconstruction] 2020-04-03-[Atlas: End-to-End 3D Scene Reconstruction from Posed Images](https://arxiv.org/pdf/2003.10432.pdf) from magicleap

### Path Planning
#### 1. [UAV] 2020-01-14-[Robust Real-time UAV Replanning Using Guided Gradient-based Optimization and Topological Paths](https://arxiv.org/pdf/1912.12644.pdf)Replanning method based on GTO.[code](https://github.com/HKUST-Aerial-Robotics/Fast-Planner)
#### 2. [Auto exploration] 2020-01-14-[3D Exploration and Navigation with Optimal-RRT Planners for Ground Robots in Indoor Incidents](https://www.researchgate.net/publication/338367746_3D_Exploration_and_Navigation_with_Optimal-RRT_Planners_for_Ground_Robots_in_Indoor_Incidents)
#### 3. [End-to-end navi] 2020-02-20-[BADGR: An Autonomous Self-Supervised Learning-Based Navigation System](https://arxiv.org/pdf/2002.05700.pdf) an end-to-end learning-based mobile robot navigation system. [code](https://sites.google.com/view/badgr)

### Others.

## SLAM 能力图 

<img src="https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM%E8%83%BD%E5%8A%9B%E5%9B%BE.png" width ="300" height="550" />





























