---
layout: archive
title: "Research Experience"
permalink: /Research_Experience/
author_profile: true
---

## At Xiamen University (From 2021 to Now)

### * A Formal Control Framework of Autonomous Vehicle for Signal Temporal Logic Tasks and Obstacle Avoidance
This research topic revolves around the development of a controller framework for signal temporal logic (STL) tasks incorporating obstacle avoidance. In this study, we successfully formulated and addressed a motion planning problem that encompasses both STL goal-reaching and obstacle avoidance objectives. We achieved this by integrating control barrier function (CBF) and artificial potential field methods. 

For more details, please refer to the published paper by clicking this [link](https://ieeexplore.ieee.org/abstract/document/10144389). 

<!-- <details>
  <summary><span style="font-size:18px;"><b>点击展开折叠内容</b></span></summary>

  这里是可以折叠的内容，可以包含多行文字、列表、图片等。

</details> -->

### * Online-tuning Control Barrier Function Approach for Signal Temporal Logic Tasks and Unknown Obstacle Avoidance
This research topic centers around the development of a CBF online parameter tuning method. 
The primary objective of this work is to construct an online control barrier function that improves system performance in the presence of unknown environments, system inaccuracies, or delays, with the aim of achieving STL tasks. 
Additionally, the concept behind this research has enhanced the performance of the system described in the first topic.
To validate the effectiveness of our proposed CBF parameter update algorithm, we have successfully implemented it in ROS/Gazebo within the PX4 firmware. Please click this [link](https://github.com/hzy-ui/ROS_APF_CBF) for the details of the semi-physical simulation.
Furthermore, we have implemented this algorithm on UAVs in our laboratory, enabling real-world experimentation and evaluation
Please click this [link](https://github.com/hzy-ui/APF_CBF_EXPERIMENT) for the details of physical experiments and videos of this work.

### * Project 1 (Motion planning of UAV in GPS-denying environment)
<video controls>
  <source src="../images/Research Experience/competition.mp4" type="video/mp4">
  您的浏览器不支持视频播放。
</video>

## At Qingdao University (From 2018 to 2021)
During my undergraduate studies, I had the privilege of working and collaborating with researchers at the [Institute for Future (IFF)](https://iff.qdu.edu.cn/index.htm#), led by Prof. [Shuzhi Sam Ge](https://cde.nus.edu.sg/ece/staff/ge-shuzhi-sam/). 
Moreover, the lab's advanced equipment, including robotic arms, 3D printers, AR/VR systems, drones, and SLAM robots, provided me with a remarkable opportunity for interdisciplinary learning. 
Those invaluable experiences allowed me to delve into the realms of robot control and machine learning, significantly enhancing my programming and English communication skills. 
Overall, those unique experiences ignited my enthusiasm for scientific research.

### * Project 1 
To address the factory's cloth transportation needs, we successfully developed autonomous guided vehicles (AGVs) that efficiently transported materials to different stations. 
My primary responsibility in this project was to develop and debug the control algorithm based on sensing data, ensuring the smooth operation of the AGVs along a magnetic track.

为解决服装厂运送物料的需求，我们自主研发了一种自主无人运货小车（AGV），其能够实现不同输送点的物料有效运输。
我主要负责基Aduino的PID算法的编写和小车的调试，最终实现小车沿磁轨的高效稳定运行。

<img src="../images/Research Experience/AGV.jpg" alt="This is an alt text." style="width:500px;height:300px;">


### * Project 2
We have designed an elevator climbing robot specifically aimed at detecting the misalignment of the guiderail. 
Additionally, we have developed effective methods for detecting misalignments using the robot.

我们自主研发并改进了一种电梯导轨爬行机器人，基于此机器人，我们研发了一种电梯导轨质量检测方法。

<img src="../images/Research Experience/Elevator climbing.jpg" alt="This is an alt text." style="width:500px;height:200px;">

For details:

[1] A. Nemati, D. Zhao, S. S. Ge, **Z. Huang**, and F. Gholami, “[An elevator guide rail quality detection device and method](https://patents.google.com/patent/CN111170121A/zh?oq=CN111170121A),” China Patent, CN111170121A.

 阿里纳玛提, 赵东杰, 葛树志, **黄致远**, 法里纳兹·戈拉米.	一种电梯导轨质量检测装置和方法.申请公布号：CN111170121A.

[2] A. Nemati, D. Zhao, C. Sun, F. Gholami, **Z. Huang**, and Z. Gong, “[A device and method for detecting the distortion of single elevator guide rail](https://patents.google.com/patent/CN114018172A/zh?oq=CN114018172A),” CN114018172A

阿里纳玛提, 赵东杰, 孙常亮, 法里纳兹·戈拉米, **黄致远**, 宫兆隆. 一种单电梯导轨扭曲变形的检测装置和方法. 申请公布号：CN114018172A.

### * Project 3
We design a SLAM robot for efficient indoor mapping by rotation of its Lidar sensor.

For details:

[1] A. Nemati, D. Zhao, S. S. Ge, **Z. Huang**, and F. Gholami, “[A SLAM robot with rotating Lidar for indoor mapping and localization](https://patents.google.com/patent/CN111251271B/zh?oq=CN111251271B),” China Patent, CN111251271B.

阿里纳玛提, 赵东杰, 葛树志, **黄致远**, 法里纳兹·戈拉米.	一种旋转激光雷达及室内地图构建和定位的SLAM机器人.申请公布号：CN111251271B.

### * Project 4
Based on the STC89S52 microcontroller, we design a dormitory smart anti-theft and fire alarm system by integrating microcontroller and sensor technologies.
The system achieves alarm functionality by detecting indoor smoke levels and human presence signals, continuously recording entries and exits, and providing a door lock reminder when no one is inside. 
The system is composed of the microcontroller core, smoke detection module, human presence detection module, LCD display module, alarm indicator module, and counter module. Through microcontroller control, each module is effectively integrated to achieve the intended functionality. 
I am the leader of the desinger team and in responsible for hardware system debugging and software C coding.

<img src="../images/Research Experience/microcontroller.jpg" alt="This is an alt text." style="width:700px;height:300px;">

For details:

<!-- [Download file](https://hzy-ui.github.io/zhiyuan-huang.github.io/files/stc89s52.pdf) -->
[Download file](https://hzy-ui.github.io/zhiyuan-huang.github.io/files/paper1.pdf)


### Acknowledgement
I would like to express my sincere gratitude to the supervisors and collaborators during my time at the IFF. In particular, I would like to extend my special thanks to Dr. [Alireza Nemati](https://www.linkedin.com/in/alireza-nemati-8116b390/), Prof. [Yinhua Liu](https://ieeexplore.ieee.org/author/37088988810), Prof. [Dongjie zhao](https://iff.qdu.edu.cn/info/1046/1082.htm), and Prof. [Wanyue Jiang](https://iff.qdu.edu.cn/info/1046/1081.htm). 

I would also like to extend my heartfelt appreciation to the professors from the School of Automation at QDU, particularly Prof. [Jihui Zhang](https://ieeexplore.ieee.org/author/37281465500), Prof. [Lin Zhao](https://ieeexplore.ieee.org/author/37089267176), Prof. [Zhijian Ji](https://www.researchgate.net/profile/Zhijian-Ji), and Prof. [Zhongsheng Hou](https://en-assc.qdu.edu.cn/info/1022/1007.htm). Their unwavering support and guidance have been invaluable to me throughout my academic journey, starting from my bachelor's degree and continuing to the present day.

