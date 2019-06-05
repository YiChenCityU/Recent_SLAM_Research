
# Recent_SLAM_Research
【回馈社区】跟踪SLAM前沿动态(2019), [2018版](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/README_2018.md) 技术更新太快，开启paper暴走模式，精选paper包括纯视觉SLAM，三维重建，基础数学工具，导航路径规划，深度学习SLAM，激光与视觉融合等类别。如果你发现我遗漏了本年度比较优秀的论文，请开issue留言，不胜感激。

### 招聘
即将上市机器人独角兽广招SLAM算法工程师。
欢迎wechat骚扰：sinnature
邮箱：easonjianghk@gmail.com
## SLAM 能力图 

<img src="https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM%E8%83%BD%E5%8A%9B%E5%9B%BE.png" width ="300" height="550" />


### SLAM
#### 76. 2019-06-05-[A Simultaneous Localization and Mapping (SLAM) Framework for 2.5D Map Building Based on Low-Cost LiDAR and Vision Fusion](https://www.researchgate.net/publication/333315015_A_Simultaneous_Localization_and_Mapping_SLAM_Framework_for_25D_Map_Building_Based_on_Low-Cost_LiDAR_and_Vision_Fusion) 激光与视觉融合SLAM
#### 75. 2019-06-05-[eSLAM: An Energy-Efficient Accelerator for Real-Time ORB-SLAM on FPGA Platform](http://sci-hub.tw/10.1145/3316781.3317820)
#### 74. 2019-05-28-[Robust simultaneous localization and mapping in low-light environment](https://onlinelibrary.wiley.com/doi/abs/10.1002/cav.1895) 提取两种特征点解决光照问题
#### 73. 2019-05-28-[An Extensive Approach to Features Detection and Description for 2D Range Data using Active B-splines](https://ieeexplore.ieee.org/abstract/document/8716503)
#### 72. 2019-05-28-[Low-latency Visual SLAM with Appearance-Enhanced Local Map Building](https://arxiv.org/pdf/1905.07797.pdf)
#### 71. 2019-05-28-[Characterizing SLAM Benchmarks and Methods for the Robust Perception Age](https://arxiv.org/pdf/1905.07808.pdf)
#### 70. 2019-05-24-[RGBD-Inertial Trajectory Estimation and Mapping for Ground Robots](https://www.researchgate.net/publication/333125503_RGBD-Inertial_Trajectory_Estimation_and_Mapping_for_Ground_Robots)RGBD+IMU,基于VINS_MONO
#### 69. 2019-05-24-[A Novel Approach for Lidar-Based Robot Localization in a Scale-Drifted Map Constructed Using Monocular SLAM](https://www.mdpi.com/1424-8220/19/10/2230) 基于单目产生的有尺度漂移的地图,用激光定位,感觉没多大用
#### 68. 2019-05-24-[Visual Inertial Odometry At the Edge: A Hardware-Software Co-design Approach for Ultra-low Latency and Power](https://ieeexplore.ieee.org/abstract/document/8714921) 低功耗 VINS
#### 67. 2019-05-24-[Explorations and Lessons Learned in Building an Autonomous FormulaSAEa Car from Simulations](https://arxiv.org/pdf/1905.05940.pdf)学生方程式赛车学习
#### 66. 2019-05-24-[Low-cost IMU Data Denoising using Savitzky-Golay Filters](https://ieeexplore.ieee.org/abstract/document/8713728)IMU数据降噪
#### 65. 2019-05-20-[AMZ Driverless: The Full Autonomous Racing System](https://arxiv.org/pdf/1905.05150.pdf) ETH赛车
#### 64. 2019-05-20-[ROS-based localization of a race vehicle at high-speed using LIDAR](https://www.e3s-conferences.org/articles/e3sconf/pdf/2019/21/e3sconf_icpeme2018_04002.pdf)TUM赛车
#### 63. 2019-05-20-[An Open Source and Open Hardware Deep Learning-powered Visual Navigation Engine for Autonomous Nano-UAVs](https://arxiv.org/pdf/1905.04166.pdf)ETH最小无人机自动导航
#### 62. 2019-05-20-[DeepICP: An End-to-End Deep Neural Network for 3D Point Cloud Registration](https://arxiv.org/pdf/1905.04153.pdf)百度无人车团队DeepICP
#### 61. 2019-05-20-[3D Keypoint Repeatability for Heterogeneous Multi-Robot SLAM](http://act.usc.edu/publications/Boroson_ICRA2019.pdf)南加州大学基于3D点云的特征点
#### 60. 2019-05-14-[Monocular Semidirect Visual Odometry for Large-scale Outdoor Localization](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8703146)
#### 59. 2019-05-14-[CREAK descriptor evaluation for visual odometry](http://sci-hub.tw/https://ieeexplore.ieee.org/document/8704807) CREAK 描述子测试
#### 58. 2019-05-05-[Humanoid Robot Dense RGB-D SLAM for Embedded Devices*](https://www.researchgate.net/profile/Stylianos_Piperakis3/publication/332686387_Humanoid_Robot_Dense_RGB-D_SLAM_for_Embedded_Devices/links/5cc341654585156cd7b4518e/Humanoid-Robot-Dense-RGB-D-SLAM-for-Embedded-Devices.pdf) 使用RGBD+IMU+Encoder做Nao机器人状态估计
#### 57. 2019-04-29-[Structure Aware SLAM using Quadrics and Planes](https://www.researchgate.net/profile/Yasir_Latif/publication/324745171_Towards_Semantic_SLAM_Points_Planes_and_Objects/links/5caaa871a6fdcca26d065630/Towards-Semantic-SLAM-Points-Planes-and-Objects.pdf)
#### 56. 2019-04-29-[VITAMIN-E: VIsual Tracking And MappINg with Extremely Dense Feature Points](https://arxiv.org/pdf/1904.10324.pdf) 很鲁棒的单目三维重建
#### 55. 2019-04-26-[Are State-of-the-art Visual Place Recognition Techniques any Good for Aerial Robotics?](https://arxiv.org/pdf/1904.07967.pdf) 关于回环检测的综述
#### 54. 2019-04-23-[An Improved Hector SLAM Algorithm based on Information Fusion for Mobile Robot](https://ieeexplore.ieee.org/abstract/document/8691198)
#### 53. 2019-04-23-[Robust RGB-D Visual Odometry Based on the Line Intersection Structure Feature in Low-Textured Scenes](https://ieeexplore.ieee.org/abstract/document/8691213)
#### 52. 2019-04-23-[Object Recognition and Simultaneous Indoor Localization Algorithm with Stereo Camera](https://ieeexplore.ieee.org/abstract/document/8691211)
#### 51. 2019-04-23-[Learning Whole-Image Descriptors for Real-time Loop Detection and Kidnap Recovery under Large Viewpoint Difference](https://arxiv.org/pdf/1904.06962.pdf) 港科大弱监督(NetVLAD)下的重定位恢复
#### 50. 2019-04-23-[Visual-Inertial Mapping with Non-Linear Factor Recovery](https://arxiv.org/pdf/1904.06504.pdf)
#### 49. 2019-04-23-[Direct Sparse Mapping](https://arxiv.org/pdf/1904.06577.pdf) 带有回环检测的稀疏直接法
#### 48. 2019-04-23-[Gyroscope-aided Relative Pose Estimation for Rolling Shutter Cameras](https://arxiv.org/pdf/1904.06770.pdf) 使用IMU解决卷帘快门图像问题
#### 47. 2019-04-17-[Adaptive SLAM with synthetic stereo dataset generation for real-time dense 3D reconstruction](https://hal.archives-ouvertes.fr/hal-02086843/document)提出在直线行走时降低图像帧率,节省计算资源以及减少误差
#### 46. 2019-04-17-[Robust Legged Robot State Estimation Using Factor Graph Optimization](https://arxiv.org/pdf/1904.03048.pdf) Anymal 四足机器人定位算法
#### 45. 2019-04-11-[Stereo camera visual odometry for moving urban environments](https://content.iospress.com/articles/integrated-computer-aided-engineering/ica190598) 
#### 44. 2019-04-11-[Online IMU Self-Calibration for Visual-Inertial Systems](https://www.mdpi.com/1424-8220/19/7/1624)
#### 43. 2019-04-02-[KO-Fusion: Dense Visual SLAM with Tightly-Coupled Kinematic and Odometric Tracking](https://www.imperial.ac.uk/media/imperial-college/research-centres-and-groups/dyson-robotics-lab/chouseago_etal_icra2019.pdf)Dyson 和 Imprial college 研发的RGBD融合底盘dense slam
#### 42. 2019-04-02-[SlamCraft: Dense Planar RGB Monocular SLAM](https://www.researchgate.net/publication/331832804_SlamCraft_Dense_Planar_RGB_Monocular_SLAM)
#### 41. 2019-03-29-[Learning 3D Semantic Reconstruction on Octrees](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/332863/1/Wang_Xiaojuan.pdf)ETH wang xiaojuan三维语义重建硕士论文
#### 40. 2019-03-29-[An Efficient Schmidt-EKF for 3D Visual-Inertial SLAM](https://arxiv.org/pdf/1903.08636.pdf)
#### 39. 2019-03-29-[Levelling the Playing Field: A Comprehensive Comparison of Visual Place Recognition Approaches under Changing Conditions](https://arxiv.org/pdf/1903.09107.pdf)关于回环检测的综述
#### 38. 2019-03-29-[Wheelchair robot navigation in different weather conditions using deep learning and evolved neural controller](https://www.emeraldinsight.com/doi/abs/10.1108/IR-08-2018-0176)
#### 37. 2019-03-29-[Pragma-Oriented Parallelization of the Direct Sparse Odometry SLAM Algorithm](https://ieeexplore.ieee.org/abstract/document/8671561)
#### 36. 2019-03-25-[FMD Stereo SLAM: Fusing MVG and Direct Formulation Towards Accurate and Fast Stereo SLAM](https://www.researchgate.net/publication/281217090_Stereo_Parallel_Tracking_and_Mapping_for_robot_localization) 
#### 35. 2019-03-21-[Spatiotemporal Decoupling Based LiDARCamera Calibration under Arbitrary Configurations](https://arxiv.org/pdf/1903.06141.pdf)
#### 34. 2019-03-21-[An Accurate Localization Scheme for Mobile Robots Using Optical Flow in Dynamic Environments](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8664893/)
#### 33. 2019-03-16-[2-Entity RANSAC for robust visual localization in changing environment](https://arxiv.org/pdf/1903.03967.pdf)
#### 32. 2019-03-16-[A Unified Formulation for Visual Odometry](https://arxiv.org/pdf/1903.04253.pdf) 综合直接法和间接法
#### 31. 2019-03-13-[Nonparametric Statistical and Clustering Based RGB-D Dense Visual Odometry in a Dynamic Environment](https://sci-hub.tw/https://link.springer.com/article/10.1007/s13319-019-0220-4)多帧残差模型处理动态物体
#### 30. 2019-03-13-[3D Reconstruction and Texture Optimization Using a Sparse Set of RGB-D Cameras](https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8658571/)
#### 29. 2019-03-13-[EGO-SLAM: A Robust Monocular SLAM for Egocentric Videos](https://www.cse.iitd.ac.in/~chetan/papers/wacv19-egoslam.pdf)
#### 28. 2019-03-11-[Real-Time Visual Odometry Covariance Estimation or Unmanned Air Vehicle Navigation](https://arc.aiaa.org/doi/pdfplus/10.2514/1.G004000)
#### 27. 2019-03-11-[Ground Plane based Absolute Scale Estimation for Monocular Visual Odometry](https://arxiv.org/pdf/1903.00912.pdf)单目估计尺度
#### 26. 2019-03-11-[Incremental Visual-Inertial 3D Mesh Generation with Structural Regularities](https://www.mit.edu/~arosinol/research/struct3dmesh.html)出自MIT，在VIO中根据三角剖分加入结构化特征
#### 25. 2019-03-08-[ROVO: Robust Omnidirectional Visual Odometry for Wide-baseline Wide-FOV Camera Systems](https://arxiv.org/pdf/1902.11154.pdf)多目鱼眼SLAM
#### 24. 2019-03-08-[Robust RGB-D Odometry under Depth Uncertainty for Structured Environments](https://search.proquest.com/openview/d9b6a8efb6fd8075cfe7aeed663085c7/1?pq-origsite=gscholar&cbl=2026366&diss=y) 博士论文处理RGBD深度误差
#### 23. 2019-03-08-[Stereo Visual Inertial LiDAR Simultaneous Localization and Mapping](https://arxiv.org/pdf/1902.10741.pdf)激光在山洞容易失效，双目可以增强某些场景
#### 22. 2019-03-08-[Double-Layer Cubature Kalman Filter for Nonlinear Estimation](https://sci-hub.tw/https://www.mdpi.com/1424-8220/19/5/986)
#### 21. 2019-03-08-[A Vertex-to-Edge Weighted Closed-Form Method for Dense RGB-D Indoor SLAM ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8649628) 
#### 20. 2019-02-28-[Vision Sensor Aided Navigation for Ground Vehicle Applications](https://sci-hub.tw/https://prism.ucalgary.ca/handle/1880/109478) Liu Zhenbo 博士毕业论文讲的很仔细
#### 19. 2019-02-28-[GSLAM: A General SLAM Framework and Benchmark](https://arxiv.org/pdf/1902.07995.pdf) 兼容多种框架的框架。。。
#### 18. 2019-02-26-[A lightweight and scalable visual‑inertial motion capture system using fducial markers](https://sci-hub.tw/10.1007/s10514-019-09834-7)二维码加IMU
#### 17. 2019-02-21-[Robust 3D Indoor Map Building via RGB-D SLAM with Adaptive IMU Fusion on Robot](https://www.mdpi.com/1424-8220/16/10/1589/pdf) 简单直接的融合方式
#### 16. 2019-02-18-[UcoSLAM: Simultaneous Localization and Mapping by Fusion of KeyPoints and Squared Planar Markers](https://arxiv.org/pdf/1902.03729.pdf)融合视觉与二维码标签SLAM，[代码](https://sourceforge.net/projects/ucoslam/)
#### 15. 2019-02-14-[Visual SLAM: Why Bundle Adjust?](https://arxiv.org/pdf/1902.03747.pdf)Ian Reid的改进版BA
#### 14. 2019-02-14-[A real-time visual-inertial mapping and localization method by fusing unstable GPS](https://ieeexplore.ieee.org/abstract/document/8630513) 根据GPS信号可信度调整优化方法
#### 13. 2019-02-14-[Comparison and Analysis of Feature Method and Direct Method in Visual SLAM Technology for Social Robots](https://ieeexplore.ieee.org/abstract/document/8630714)对比直接法与特征点法
#### 12. 2019-01-30-[Multi-objective Mapping and Path Planning using Visual SLAM and Object Detection](https://uwspace.uwaterloo.ca/bitstream/handle/10012/14386/Woo_Ami.pdf?sequence=3&isAllowed=y) 一篇硕士论文
#### 11. 2019-01-30-[Extrinsic Calibration of Lidar and Camera with Polygon](https://ram-lab.com/papers/2018/liao_robio2018.pdf) 利用已知多边形板子获得激光与视觉传感器外参，出自港科大刘明老师
#### 10. 2019-01-30-[Robust Photogeometric Localization over Time for Map-Centric Loop Closure](https://arxiv.org/pdf/1901.07660.pdf)解决map-centric slam回环问题
#### 9. 2019-01-25-[A Novel Method for Extrinsic Calibration of Multiple RGB-D Cameras Using Descriptor-Based Patterns](https://www.mdpi.com/1424-8220/19/2/349/htm) 多个RGBD相机外参标定
#### 8. 2019-01-25-[SLAM of Robot based on the Fusion of Vision and LIDAR](https://sci-hub.tw/10.1109/cbs.2018.8612212)RGBD 与lidar 融合，好像只是处理逻辑关系判断，没有深度融合
#### 7. 2019-01-25-[ADAPTIVE FILTERING FOR VISION-AIDED INERTIAL NAVIGATION](https://smartech.gatech.edu/bitstream/handle/1853/60806/LEE-DISSERTATION-2018.pdf?sequence=1&isAllowed=y) 佐治亚理工博士论文，关于自适应卡尔曼滤波
#### 6. 2019-01-25-[Loosely-Coupled Semi-Direct Monocular SLAM](https://arxiv.org/pdf/1807.10073.pdf) Javier Civera 直接法和特征法融合，也是我现在工作比较感兴趣的一个方向
#### 5. 2019-01-25-[Visual-Inertial SLAM Initialization: A General Linear Formulation and a Gravity-Observing Non-Linear Optimization](https://sci-hub.tw/10.1109/ismar.2018.00027) Javier Civera 关于视觉惯导初始化问题的研究
#### 4. 2019-01-11-[SDVL: Efficient and Accurate Semi-Direct Visual Localization](https://www.researchgate.net/publication/330379725_SDVL_Efficient_and_Accurate_Semi-Direct_Visual_Localization) 直接法与特征点法混合
#### 3. 2019-01-11-[A General Optimization-based Framework for Local Odometry Estimation with Multiple Sensors](https://arxiv.org/pdf/1901.03638.pdf) 双目VINS
#### 2. 2019-01-11-[A General Optimization-based Framework for Global Pose Estimation with Multiple Sensors](https://arxiv.org/pdf/1901.03642.pdf) 港科大多传感器融合
#### 1. 2019-01-09-[Factor Graphs for Flexible Inference in Robotics and Vision](https://smartech.gatech.edu/handle/1853/60646) Dellaert, Frank视频详解因子图，他也是牛逼的SKYDIO 的开发者之一

### Deep SLAM
#### 22. 2019-05-09-[EM-Fusion: Dynamic Object-Level SLAM with Probabilistic Data Association](https://arxiv.org/pdf/1904.11781.pdf)处理动态物体三维重建
#### 21. 2019-05-09[GN-Net: The Gauss-Newton Loss for Deep Direct SLAM](https://arxiv.org/pdf/1904.11932.pdf)Daniel Cremers 所作,在帧间tracking时replace the image I with a feature map computed by a deep neural network.
#### 20. 2019-04-26-[Deep Sensor Fusion between 2D Laser Scanner and IMU for Mobile Robot Localization](https://ieeexplore.ieee.org/abstract/document/8689068)
#### 19. 2019-04-26-[LO-Net: Deep Real-time Lidar Odometry](https://arxiv.org/pdf/1904.08242.pdf)
#### 18. 2019-04-23-[AI-IMU Dead-Reckoning](https://arxiv.org/pdf/1904.06064.pdf)只利用IMU做航迹推算,使用了卡尔曼滤波和神经网络
#### 17. 2019-04-23-[Localizing Discriminative Visual Landmarks for Place Recognition](https://arxiv.org/pdf/1904.06635.pdf)回环检测
#### 16. 2019-04-23-[Recurrent Neural Network for (Un-)supervised Learning of Monocular Video Visual Odometry and Depth](https://arxiv.org/pdf/1904.07087.pdf) 
#### 15. 2019-04-19-[Semantic Nearest Neighbor Fields for Monocular Edge Visual-Odometry](https://arxiv.org/pdf/1904.00738.pdf)带有语义信息的几何边融入到VO中
#### 14. 2019-04-17-[VISUAL LOCALIZATION USING SPARSE SEMANTIC 3D MAP](https://arxiv.org/pdf/1904.03803.pdf)
#### 13. 2019-04-17-[Discovering and Leveraging Deep Multimodal Structure for Reliable Robot Perception and Localization](https://www.researchgate.net/profile/Abhinav_Valada/publication/331247138_Discovering_and_leveraging_deep_multimodal_structure_for_reliable_robot_perception_and_localization/links/5c7d5679299bf1268d3903d5/Discovering-and-leveraging-deep-multimodal-structure-for-reliable-robot-perception-and-localization.pdf)  Wolfram Burgard 学生博士论文,主要讲述分割网络以及在SLAM中的应用
#### 12. 2019-04-11-[Beyond Tracking:Selecting Memory and Refining Poses for Deep Visual Odometry](https://arxiv.org/pdf/1904.01892.pdf) 商汤北大合作
#### 11. 2019-04-02-[Unsupervised Learning of Accurate Camera Pose and Depth From Video Sequences With Kalman Filter](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8666111) 
#### 10. 2019-03-25-[Pose Graph Optimization for Unsupervised Monocular Visual Odometry](https://arxiv.org/pdf/1903.06315.pdf)
#### 9. 2019-03-16-[Sparse Representations for Object and Ego-motion Estimation in Dynamic Scenes](https://arxiv.org/pdf/1903.03731.pdf)
#### 8. 2019-03-08-[DeepLO: Geometry-Aware Deep LiDAR Odometry](https://arxiv.org/pdf/1902.10562.pdf)基于深度学习的三维激光SLAM
#### 7. 2019-03-08-[A Generative Map for Image-based Camera Localization](https://arxiv.org/pdf/1902.11124.pdf)
#### 6. 2019-03-08-[GCNv2: Efficient Correspondence Prediction for Real-Time SLAM](https://arxiv.org/pdf/1902.11046.pdf) 网络生成ORB特征点，融合ORBSLAM里面去。[code](https://github.com/jiexiong2016/GCNv2_SLAM)
#### 5. 2019-02-15-[Semantic and 3D Understanding of a Scene for Robot Perception](https://sci-hub.tw/http://search.proquest.com/openview/3a5804693015d4d0b42f1e4089a02267/1?pq-origsite=gscholar&cbl=18750&diss=y) 硕士论文
#### 4. 2019-02-14-[VUNet: Dynamic Scene View Synthesis for Traversability Estimation using an RGB Camera](https://ieeexplore.ieee.org/document/8624332)估计机器人未来可通行区域
#### 3. 2019-02-13-[GEN-SLAM: Generative Modeling for Monocular Simultaneous Localization and Mapping](https://arxiv.org/pdf/1902.02086.pdf)
#### 2. 2019-01-25-[Towards Building the Semantic Map from a Monocular Camera with a Multi-task Network](https://arxiv.org/pdf/1901.05807.pdf) 中山大学通过多任务CNN生成单目深度图与并分割，重建出有语义信息的地图
#### 1. 2019-01-22-[DF-SLAM: A Deep-Learning Enhanced Visual SLAM System based on Deep Local Features](https://arxiv.org/pdf/1901.07223.pdf)

### 3D Reconstruction
#### 7. 2019-05-14-[ReFusion: 3D Reconstruction in Dynamic Environments for RGB-D Cameras Exploiting Residuals](https://arxiv.org/pdf/1905.02082.pdf) 
#### 6. 2019-04-02-[TAPA-MVS: Textureless-Aware PAtchMatch Multi-View Stereo](https://arxiv.org/pdf/1903.10929.pdf)
#### 5. 2019-03-25-[Robust and affordable localization and mapping for 3D reconstruction. Application to architecture and construction](http://uvadoc.uva.es/bitstream/10324/35078/1/Tesis1482-190314.pdf)
#### 4. 2019-02-18-[Improving 3D reconstruction via RGB-D camera registration and shading-based surface refinement]南阳理工邓腾博士论文
#### 3. 2019-02-13-[Comparative analysis of properties of LiDAR-based point clouds versus camerabased point clouds for 3D reconstruction using SLAM algorithms](http://scholar.google.com/scholar_url?url=https://www.doria.fi/bitstream/handle/10024/167410/bistrom_benjamin.pdf%3Fsequence%3D2&hl=de&sa=X&d=12452230042616813822&scisig=AAGBfm38puu_H5N8Tp62YkqQwuvZUVNXOw&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:13453396895897446987:AAGBfm2VmZLsOGwX0LAQ1scLkl9E22zpBQ)激光点云与RGBD点云对比
#### 2. 2019-01-12-[Real-time Monocular Dense Mapping of Small Scenes with ORB Features](https://sci-hub.tw/https://ieeexplore.ieee.org/document/8610747) 单目ORB SLAM重建 
#### 1. 2019-01-12-[NRMVS: Non-Rigid Multi-View Stereo](https://arxiv.org/pdf/1901.03910.pdf) 根据不同视角RGB图像对变形物体三维重建

### Auto driving
#### 10. 2019-05-14-[Trajectory Optimization of LiDAR SLAM Based on Local Pose Graph](http://sci-hub.tw/10.1007/978-981-13-7751-8_36) 优于LOAM的3D laser SLAM 
#### 9. 2019-05-09-[Automatic extrinsic calibration between a camera and a 3D Lidar using 3D point and plane correspondences](https://arxiv.org/pdf/1904.12433.pdf) 标定相机与三维激光雷达
#### 8. 2019-05-09-[A Novel Dual-Lidar Calibration Algorithm Using Planar Surfaces](https://arxiv.org/pdf/1904.12116.pdf) 标定双激光雷达
#### 7. 2019-05-09-[DeLiO: Decoupled LiDAR Odometry](https://arxiv.org/pdf/1904.12667.pdf) 把旋转和平移分开求解
#### 6. 2019-04-23-[Tightly Coupled 3D Lidar Inertial Odometry and Mapping](https://arxiv.org/pdf/1904.06993.pdf)港科大lidar融合IMU建图
#### 5. 2019-03-13-[Lidar-Monocular Visual Odometry with Genetic Algorithm for Parameter Optimization](https://arxiv.org/pdf/1903.02046.pdf)在线实时优化参数
#### 4. 2019-03-13-[An Interactive LiDAR to Camera Calibration](https://arxiv.org/pdf/1903.02122.pdf) 雷达相机外参标定
#### 3. 2019-03-13-[A Fuzzy-Innovation-Based Adaptive Kalman Filter for Enhanced Vehicle Positioning in Dense Urban Environments](file:///home/eason/Downloads/sensors-19-01142-v2.pdf)
#### 2. 2019-01-25-[Sensor fusion for localization of automated vehicles](https://d-nb.info/1173898506/34) 德国Bonn大学自动驾驶多传感器融合博士论文
#### 1. 2019-01-24-[Self-Driving Cars: A Survey](https://arxiv.org/pdf/1901.04407.pdf)

### Path Planning 
#### 12. 2019-04-29-[Continuous Occupancy Map Fusion with Fast Bayesian Hilbert Maps](https://www.researchgate.net/profile/Weiming_Zhi/publication/332550322_Continuous_Occupancy_Map_Fusion_with_Fast_Bayesian_Hilbert_Maps/links/5cbc7fc1299bf12097765677/Continuous-Occupancy-Map-Fusion-with-Fast-Bayesian-Hilbert-Maps.pdf)
#### 11. 2019-04-26-[Deep Local Trajectory Replanning and Control for Robot Navigation](http://iliad.stanford.edu/pdfs/publications/pokle2019deep.pdf)
#### 10. 2019-04-23-[A new optimization-driven path planning method with probabilistic completeness for wheeled mobile robots](https://journals.sagepub.com/doi/full/10.1177/0020294019836127)
#### 9. 2019-04-19-[Confidence random tree-based algorithm for mobile robot path planning considering the path length and safety](http://scholar.google.com.hk/scholar_url?url=https://journals.sagepub.com/doi/pdf/10.1177/1729881419838179&hl=zh-CN&sa=X&d=10415875195647299755&scisig=AAGBfm2HyeooIJxniSvIoXqUnJVBbOgqrg&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:13322782094633563195:AAGBfm3BsU2dft4hdsGEGWT6jrVBOBGCUA)
#### 8. 2019-04-19-[Safe, Aggressive Quadrotor Flight via Reachability-based Trajectory Design](https://arxiv.org/pdf/1904.05728.pdf)更激进且安全的路径规划
#### 7. 2019-04-15-[Online Trajectory Generation of a MAV for Chasing a Moving Target in 3D Dense Environments](https://arxiv.org/pdf/1904.03421.pdf)
#### 6. 2019-03-08-[Autonomous Robotic Exploration by Incremental Road Map Construction](http://eeyxsun.people.ust.hk/docs/TASE2019_autonomous.pdf)港中文港科大合作出品
#### 5. 2019-02-18-[Efficient Autonomous Exploration Planning of Large Scale 3D-Environments](https://www.ida.liu.se/divisions/aiics/publications/RAL-2019-Efficient-Autonomous-Exploration.pdf). Frontier Exploration planning (FEP) 与 Receding Horizon Next-Best-View planning (RH-NBVP)方法融合做自主探索
#### 4. 2019-02-15-[Motion Planning for Micro Aerial Vehicles](https://sci-hub.tw/http://search.proquest.com/openview/3ddcfedc312ef40732797bfbc416ed59/1?pq-origsite=gscholar&cbl=18750&diss=y)宾大liu sikang博士论文，导师Kumar
#### 3. 2019-02-14-[A Novel GRU-RNN Network Model for Dynamic Path Planning of Mobile Robot](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8625490) 全名Gated Recurrent Unit-Recurrent Neural Network (GRU-RNN) 
#### 2. 2019-02-13-[Improving the Hybrid A* method for a non-holonomic wheeled robot](https://journals.sagepub.com/doi/full/10.1177/1729881419826857)增强混合A星算法
#### 1. 2019-01-25-[Planning Algorithms for Multi-Robot Active Perception](http://scholar.google.com/scholar_url?url=https://ses.library.usyd.edu.au/bitstream/2123/19781/3/Graeme%2520Best%2520thesis.pdf&hl=zh-CN&sa=X&d=8591620865467554452&scisig=AAGBfm3-S44J8_MVtxhXZOgRqUDfvDig7g&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:7683124594916984709:AAGBfm07xRT6Xkv3-NQLydsk2iShtnUYcA) 悉尼大学多机器人主动感知路径规划

### Others.

#### 9. 2019-04-29-[MapperBot / iSCAN: Open-Source Integrated Robotic Platform and Algorithm for 2D Mapping](https://www.researchgate.net/profile/Akram_Al-Hourani/publication/332413257_MapperBot_iSCAN_Open-Source_Integrated_Robotic_Platform_and_Algorithm_for_2D_Mapping/links/5cb3fc5a4585156cd7992888/MapperBot-iSCAN-Open-Source-Integrated-Robotic-Platform-and-Algorithm-for-2D-Mapping.pdf)
#### 8. 2019-04-29-[Contact-Aided Invariant Extended Kalman Filtering for Robot State Estimation*](https://arxiv.org/pdf/1904.09251.pdf)
#### 7. 2019-04-19-[An Orthogonal Weighted Occupancy Likelihood Map with IMU-Aided Laser Scan Matching for 2D Indoor Mapping](https://www.mdpi.com/1424-8220/19/7/1742/pdf)
#### 6. 2019-03-25-[Distributed Kalman-filtering: Distributed optimization viewpoint](https://arxiv.org/pdf/1903.07807.pdf)
#### 5. 2018-03-08-[UCSD ECE276A: Sensing & Estimation in Robotics (Winter 2019)](https://natanaso.github.io/ece276a/schedule.html) UC 圣地亚哥大学机器人感知运动估计课程
#### 4. 2018-02-25-[Robust Harris Detector Corresponding and Calculates the Projection Error Using the Modification of the Weighting Function](http://www.ijmlc.org/vol9/766-M025.pdf)多层权重函数增强本质矩阵计算准确度
#### 3. 2019-02-25-[MC2SLAM: Real-Time Inertial Lidar Odometry Using Two-Scan Motion Compensation](https://sci-hub.tw/10.1007/978-3-030-12939-2_5) 激光IMU紧耦合方案，声称KITTI数据集top5，且放出了数据集。
#### 2. 2019-02-18-[GPS/LiDAR Sensor Fusion Integrity: A Top-Down Approach](http://gracegao.ae.illinois.edu/publications/journal/2018_Navigation_GPSLidar%20integrity_Ashwin%20Kanhere.pdf) GPS 激光融合
#### 1. 2019-01-25-[Ultra-wideband-based Navigation for Unmanned Aerial Vehicles](http://scholar.google.com.hk/scholar_url?url=https://dr.ntu.edu.sg/bitstream/handle/10220/47471/THESIS_GUO%2520KEXIN_G1400180L.pdf%3Fsequence%3D1&hl=zh-CN&sa=X&d=7665655280644322246&scisig=AAGBfm0njtXltv-cbMLcxfW5K85Ixk-XSg&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:8091854961068759592:AAGBfm2trGFRZKGhbBitzOqs-u-1ftqAhA) 南洋理工UWB定位博士论文





























