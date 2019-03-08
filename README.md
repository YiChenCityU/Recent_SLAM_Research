# Recent_SLAM_Research
【回馈社区】跟踪SLAM前沿动态(2019), [2018版](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/README_2018.md) 技术更新太快，开启paper暴走模式，精选paper包括纯视觉SLAM，三维重建，基础数学工具，导航路径规划，深度学习SLAM，激光与视觉融合等类别。如果你发现我遗漏了本年度比较优秀的论文，请开issue留言，不胜感激。

### 招聘
即将上市机器人独角兽广招SLAM算法工程师。
欢迎wechat骚扰：sinnature
邮箱：easonjianghk@gmail.com
## SLAM 能力图 

<img src="https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM%E8%83%BD%E5%8A%9B%E5%9B%BE.png" width ="300" height="550" />


### VSLAM
#### 25. 2019-03-08-[ROVO: Robust Omnidirectional Visual Odometry for Wide-baseline Wide-FOV Camera Systems](https://arxiv.org/pdf/1902.11154.pdf)多目鱼眼SLAM
#### 24. 2019-03-08-[Robust RGB-D Odometry under Depth Uncertainty for Structured Environments](https://search.proquest.com/openview/d9b6a8efb6fd8075cfe7aeed663085c7/1?pq-origsite=gscholar&cbl=2026366&diss=y) 博士论文处理RGBD深度误差
#### 23. 2019-03-08-[Stereo Visual Inertial LiDAR Simultaneous Localization and Mapping](https://arxiv.org/pdf/1902.10741.pdf)激光在山洞容易失效，双目可以增强某些场景
#### 22. 2019-03-08-[Double-Layer Cubature Kalman Filter for Nonlinear Estimation](https://sci-hub.tw/https://www.mdpi.com/1424-8220/19/5/986)
#### 21. 2019-03-08-[A Vertex-to-Edge Weighted Closed-Form Method for Dense RGB-D Indoor SLAM ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8649628) 
#### 20. 2019-02-08-[Vision Sensor Aided Navigation for Ground Vehicle Applications](https://sci-hub.tw/https://prism.ucalgary.ca/handle/1880/109478) Liu Zhenbo 博士毕业论文讲的很仔细
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
#### 8. 2019-03-08-[DeepLO: Geometry-Aware Deep LiDAR Odometry](https://arxiv.org/pdf/1902.10562.pdf)基于深度学习的三维激光SLAM
#### 7. 2019-03-08-[A Generative Map for Image-based Camera Localization](https://arxiv.org/pdf/1902.11124.pdf)
#### 6. 2019-03-08-[GCNv2: Efficient Correspondence Prediction for Real-Time SLAM](https://arxiv.org/pdf/1902.11046.pdf) 网络生成ORB特征点，融合ORBSLAM里面去。[code](https://github.com/jiexiong2016/GCNv2_SLAM)
#### 5. 2019-02-15-[Semantic and 3D Understanding of a Scene for Robot Perception](https://sci-hub.tw/http://search.proquest.com/openview/3a5804693015d4d0b42f1e4089a02267/1?pq-origsite=gscholar&cbl=18750&diss=y) 硕士论文
#### 4. 2019-02-14-[VUNet: Dynamic Scene View Synthesis for Traversability Estimation using an RGB Camera](https://ieeexplore.ieee.org/document/8624332)估计机器人未来可通行区域
#### 3. 2019-02-13-[GEN-SLAM: Generative Modeling for Monocular Simultaneous Localization and Mapping](https://arxiv.org/pdf/1902.02086.pdf)
#### 2. 2019-01-25-[Towards Building the Semantic Map from a Monocular Camera with a Multi-task Network](https://arxiv.org/pdf/1901.05807.pdf) 中山大学通过多任务CNN生成单目深度图与并分割，重建出有语义信息的地图
#### 1. 2019-01-22-[DF-SLAM: A Deep-Learning Enhanced Visual SLAM System based on Deep Local Features](https://arxiv.org/pdf/1901.07223.pdf)

### 3D Reconstruction
#### 4. 2019-02-18-[Improving 3D reconstruction via RGB-D camera registration and shading-based surface refinement](file:///home/eason/Downloads/Thesis_final_submit.pdf)南阳理工邓腾博士论文
#### 3. 2019-02-13-[Comparative analysis of properties of LiDAR-based point clouds versus camerabased point clouds for 3D reconstruction using SLAM algorithms](http://scholar.google.com/scholar_url?url=https://www.doria.fi/bitstream/handle/10024/167410/bistrom_benjamin.pdf%3Fsequence%3D2&hl=de&sa=X&d=12452230042616813822&scisig=AAGBfm38puu_H5N8Tp62YkqQwuvZUVNXOw&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:13453396895897446987:AAGBfm2VmZLsOGwX0LAQ1scLkl9E22zpBQ)激光点云与RGBD点云对比
#### 2. 2019-01-12-[Real-time Monocular Dense Mapping of Small Scenes with ORB Features](https://sci-hub.tw/https://ieeexplore.ieee.org/document/8610747) 单目ORB SLAM重建 
#### 1. 2019-01-12-[NRMVS: Non-Rigid Multi-View Stereo](https://arxiv.org/pdf/1901.03910.pdf) 根据不同视角RGB图像对变形物体三维重建

### Auto driving

#### 2. 2019-01-25-[Sensor fusion for localization of automated vehicles](https://d-nb.info/1173898506/34) 德国Bonn大学自动驾驶多传感器融合博士论文
#### 1. 2019-01-24-[Self-Driving Cars: A Survey](https://arxiv.org/pdf/1901.04407.pdf)

### Path Planning 
#### 6. 2019-03-08-[Autonomous Robotic Exploration by Incremental Road Map Construction](http://eeyxsun.people.ust.hk/docs/TASE2019_autonomous.pdf)港中文港科大合作出品
#### 5. 2019-02-18-[Efficient Autonomous Exploration Planning of Large Scale 3D-Environments](https://www.ida.liu.se/divisions/aiics/publications/RAL-2019-Efficient-Autonomous-Exploration.pdf). Frontier Exploration planning (FEP) 与 Receding Horizon Next-Best-View planning (RH-NBVP)方法融合做自主探索
#### 4. 2019-02-15-[Motion Planning for Micro Aerial Vehicles](https://sci-hub.tw/http://search.proquest.com/openview/3ddcfedc312ef40732797bfbc416ed59/1?pq-origsite=gscholar&cbl=18750&diss=y)宾大liu sikang博士论文，导师Kumar
#### 3. 2019-02-14-[A Novel GRU-RNN Network Model for Dynamic Path Planning of Mobile Robot](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8625490) 全名Gated Recurrent Unit-Recurrent Neural Network (GRU-RNN) 
#### 2. 2019-02-13-[Improving the Hybrid A* method for a non-holonomic wheeled robot](https://journals.sagepub.com/doi/full/10.1177/1729881419826857)增强混合A星算法
#### 1. 2019-01-25-[Planning Algorithms for Multi-Robot Active Perception](http://scholar.google.com/scholar_url?url=https://ses.library.usyd.edu.au/bitstream/2123/19781/3/Graeme%2520Best%2520thesis.pdf&hl=zh-CN&sa=X&d=8591620865467554452&scisig=AAGBfm3-S44J8_MVtxhXZOgRqUDfvDig7g&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:7683124594916984709:AAGBfm07xRT6Xkv3-NQLydsk2iShtnUYcA) 悉尼大学多机器人主动感知路径规划

### Others
#### 5. 2018-03-08-[UCSD ECE276A: Sensing & Estimation in Robotics (Winter 2019)](https://natanaso.github.io/ece276a/schedule.html) UC 圣地亚哥大学机器人感知运动估计课程
#### 4. 2018-02-25-[Robust Harris Detector Corresponding and Calculates the Projection Error Using the Modification of the Weighting Function](http://www.ijmlc.org/vol9/766-M025.pdf)多层权重函数增强本质矩阵计算准确度
#### 3. 2019-02-25-[MC2SLAM: Real-Time Inertial Lidar Odometry Using Two-Scan Motion Compensation](https://sci-hub.tw/10.1007/978-3-030-12939-2_5) 激光IMU紧耦合方案，声称KITTI数据集top5，且放出了数据集。
#### 2. 2019-02-18-[GPS/LiDAR Sensor Fusion Integrity: A Top-Down Approach](http://gracegao.ae.illinois.edu/publications/journal/2018_Navigation_GPSLidar%20integrity_Ashwin%20Kanhere.pdf) GPS 激光融合
#### 1. 2019-01-25-[Ultra-wideband-based Navigation for Unmanned Aerial Vehicles](http://scholar.google.com.hk/scholar_url?url=https://dr.ntu.edu.sg/bitstream/handle/10220/47471/THESIS_GUO%2520KEXIN_G1400180L.pdf%3Fsequence%3D1&hl=zh-CN&sa=X&d=7665655280644322246&scisig=AAGBfm0njtXltv-cbMLcxfW5K85Ixk-XSg&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:8091854961068759592:AAGBfm2trGFRZKGhbBitzOqs-u-1ftqAhA) 南洋理工UWB定位博士论文





























