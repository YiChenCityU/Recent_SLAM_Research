# Recent_SLAM_Research
【回馈社区】跟踪SLAM前沿动态(2019), [2018版](https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/README_2018.md) 技术更新太快，开启paper暴走模式，精选paper包括纯视觉SLAM，三维重建，基础数学工具，导航路径规划，深度学习SLAM，激光与视觉融合等类别。

## SLAM 能力图 

<img src="https://github.com/YiChenCityU/Recent_SLAM_Research/blob/master/SLAM%E8%83%BD%E5%8A%9B%E5%9B%BE.png" width ="300" height="550" />


### VSLAM

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
#### 2. 2019-01-25-[Towards Building the Semantic Map from a Monocular Camera with a Multi-task Network](https://arxiv.org/pdf/1901.05807.pdf) 中山大学通过多任务CNN生成单目深度图与并分割，重建出有语义信息的地图
#### 1. 2019-01-22-[DF-SLAM: A Deep-Learning Enhanced Visual SLAM System based on Deep Local Features](https://arxiv.org/pdf/1901.07223.pdf)

### 3D Reconstruction

#### 2. 2019-01-12-[Real-time Monocular Dense Mapping of Small Scenes with ORB Features](https://sci-hub.tw/https://ieeexplore.ieee.org/document/8610747) 单目ORB SLAM重建 
#### 1. 2019-01-12-[NRMVS: Non-Rigid Multi-View Stereo](https://arxiv.org/pdf/1901.03910.pdf) 根据不同视角RGB图像对变形物体三维重建

### Auto driving

#### 2. 2019-01-25-[Sensor fusion for localization of automated vehicles](https://d-nb.info/1173898506/34) 德国Bonn大学自动驾驶多传感器融合博士论文
#### 1. 2019-01-24-[Self-Driving Cars: A Survey](https://arxiv.org/pdf/1901.04407.pdf)

### Path Planning 

#### 1. 2019-01-25-[Planning Algorithms for Multi-Robot Active Perception](http://scholar.google.com/scholar_url?url=https://ses.library.usyd.edu.au/bitstream/2123/19781/3/Graeme%2520Best%2520thesis.pdf&hl=zh-CN&sa=X&d=8591620865467554452&scisig=AAGBfm3-S44J8_MVtxhXZOgRqUDfvDig7g&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:7683124594916984709:AAGBfm07xRT6Xkv3-NQLydsk2iShtnUYcA) 悉尼大学多机器人主动感知路径规划

### Others
#### 1. 2019-01-25-[Ultra-wideband-based Navigation for Unmanned Aerial Vehicles](http://scholar.google.com.hk/scholar_url?url=https://dr.ntu.edu.sg/bitstream/handle/10220/47471/THESIS_GUO%2520KEXIN_G1400180L.pdf%3Fsequence%3D1&hl=zh-CN&sa=X&d=7665655280644322246&scisig=AAGBfm0njtXltv-cbMLcxfW5K85Ixk-XSg&nossl=1&oi=scholaralrt&hist=3Pwx2kMAAAAJ:8091854961068759592:AAGBfm2trGFRZKGhbBitzOqs-u-1ftqAhA) 南洋理工UWB定位博士论文





























