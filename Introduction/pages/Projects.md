# Projects

[TOC]

This page describes the projects briefly, and more detailed description can be found in [statement](Statement.md).

### The International Genetically Engineered Machine Competition(iGEM) 2018

* 2017.09 - 2018.10
* find more information in [our wiki](http://2018.igem.org/Team:Tsinghua-A)

[![Tsinghua-A at Jiant Jamboree with poster](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/igem/Tsinghua-A--Team-photo.jpg) ]( http://2018.igem.org/Team:Tsinghua-A )

*  attribution:  Designed and constructed the hardware ([Detail](http://2018.igem.org/Team:Tsinghua-A/Hardware ))
*  sponsored by *Academic Research Promotion Plan for Undergraduate Student*

<img src="https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/igem/hardware printer.jpg" alt="Hardware Printing" style="zoom:50%;" />

<img src="https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/igem/developing.png" alt="developing" style="zoom:50%;" />

### Baxter

* 2018.09-2019.05
* sponsored by *Academic Research Promotion Plan for Undergraduate Student*

#### Play Gobang with human

[Video](https://cloud.tsinghua.edu.cn/d/a54c26b100784447b8f3/files/?p=%2Fbaxter%2Ffollower.mp4)

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/baxter/gobang.png)

Here, we rolled out a project able to play gobang with human, without any help from developer.

This project mainly includes image processing, gobang AI, objects recognition, picking and placing.

#### Arm movement simulation

[Video](https://cloud.tsinghua.edu.cn/d/a54c26b100784447b8f3/files/?p=%2Fbaxter%2Ffollower.mp4)

We capture human skeleton using Kinect SDK and map it into the pose of robot, achieving a pose following effect.

#### Experimental Guide Book for Baxter

Since there's little reference material for students in Tsinghua to use Baxter and develop project on it. We write a manual about how to setup a workspace, run "hello baxter" program, and more advanced manipulation.

### Footroller: Game shoes for the handicapped

2018.07 - 2019.07

- sponsored by *College Students' Innovative Entrepreneurial Training Plan Program*
- https://github.com/RLi43/Footroller 
- Third Prize in 2019 China-US Young Maker Competition in Beijing

How disable people enjoy nowadays colorful digital life? Can they use the smart device as easily as normal people? Focus on the interaction between the handicapped and smart devices, we designed Footroller, game shoes able to control smart device through actions of feet.

![prototype](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/footroller/prototype.jpg)

This system connects PC through wireless network, sends sensor data to program runs on PC which can analysis the actions the user taking and respond with corresponding operation.

### Exploration and Implementation of Motion Planning Algorithm with Specified Optimization Goal

2020.07.01-2020.08.31

A summer intern in [Aqrose Technology]( http://www.aqrose.com/ ), a company major in AI for robotics and automation. During the summer of 2019, I worked on planning algorithm of the robot. 

Since a 6-axis Fanuc robot doesn’t give enough detail about its manipulation algorithms, we don’t know the accurate trajectory that robot will take, which makes it dangerous to operate in industry site. Therefore, I worked on a planning algorithm that have enough distance away from the obstacles to make sure that the robot won’t hit them in case the deviation happened.(Meanwhile, there’s another colleague worked on experiments to conjecture the algorithm in black box. Unfortunately, he haven't got the right answer until the end of the summer.)

I learned about planning algorithm by [Planning Algorithms]( http://planning.cs.uiuc.edu/ ). After reading some papers, algorithms, finally I decided to use BIT* as the main algorithm. I set some penalization for short distance to obstacles and got a positive output. And modified the algorithm and speed up it.

What's more, I explored the bi-directional BIT\* and concluded that a simple bi-directional adaption will not benefit BIT* much since it has taken the heuristic information about goal state into consideration.

![biBITstar](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/aqrose/biBITstar.png)

Here’s the [detailed report.pdf(Chinese)](https://cloud.tsinghua.edu.cn/d/a54c26b100784447b8f3/files/?p=%2Faqrose%2Freport%20of%20summer%20intern(Chinese).pdf) and [PPT]( https://cloud.tsinghua.edu.cn/f/decae61280884d46948e/ ) and a [essential version PPT]( https://cloud.tsinghua.edu.cn/f/a575d20f2ca749b0b7c3/ ). [Python Demos for biBIT*]( https://github.com/RLi43/RRTs/blob/master/BiBITstar.py )

### Internship in Future Lab

2019.09 - Present

Working in the LEGO Group with [Dr. Meng Wang](http://thfl.tsinghua.edu.cn/info/post-doctoral/507), I participate in several projects about Modular TUI. Mostly deal with models, circuits, codes. Sometimes severed as a soldering android :laughing:.​

This is a desk robot I finished in 2020.01, consist of 3 replaceable parts of different functions, able to communicate with one another through IR signals.

<img src="https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/flab/mr.png" style="zoom:30%;" /><img src="https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/flab/lego.png" style="zoom:30%;" />

The Lego blocks in the background is for the following project about a modular Lego desk robot. I just finished one block served as "Head" in November and I'm working on the other blocks.

### A Gloves-based Joint Pose Sensing System

2020.07-2020.09

A summer research project focus on improving [form system](https://ieeexplore.ieee.org/document/8206575/). Due to the COVID-19, This project which would have been taken in *UCLA Center for Vision, Cognition, Learning, and Autonomy (VCLA) at Statistics Department*, was taken in my home.

The former project has these problems: 1) the force sensor is neither accurate or sustainable. 2) lots of wires are used making user inconvenient. 3) connected with a raspberry pi, the system is huge as for a glove and movements are constricted by the power wire.

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/former.png)

Therefore, in this project we, 1) give up the force sensors. 2) replace raspberry pi with ESP32(a MCU) with WiFi module. 3) replace wires and PCB with FPC

This project is not fully completed. Here’s some designs during project.

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/Hub.png)![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/Hub_design.png)

The design for hub deal with 8-channel IIC signal.

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/IMU_pcb.png)![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/IMU_design.png)

The test PCB for IMU. (Soldering this tiny board kills me…)

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/web_data.png)![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/reconstruction.png)

read sensor’ data through wireless network and reconstruct the pose of joints.

![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/main.png)![](https://cloud.tsinghua.edu.cn/thumbnail/a54c26b100784447b8f3/1024/glove/fpc.png)

The development board and the FPC.