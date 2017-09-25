---
layout: post
title: Review of "Multi-View 3D Object Detection Network for Autonomous Driving"
permalink: /3D-object-detection-network-for-autonomous driving
published: true
---
## Introduction
The following is an attempt to summarize and make an easy to digest review of the paper "Multi-View 3D Object Detection Network 
for Autonomous Driving" by Xiaozhi Chen, Huimin Ma, Ji Wan, Bo Li and Tian Xia.
The paper was submitted 23rd Nov 2016 and can be found in the following [link](https://arxiv.org/abs/1611.07759)

The paper touches upon the subject of Object detection by fusing different sensor signals using Deep Learning methods.
The sensors which are being used is the LIDAR and RGB Stereo camera. Thereby taking the best from two worlds: 
the LIDAR perceiving the depth information of the setting and the RGB images perceiving detailed semantic information of the setting.

## Keywords:
* Object Detection
* Sensor Fusion
* Deep Learning

## Content:
### The LIDAR Sensor:
![LIDAR on top of a vehicle](https://raw.githubusercontent.com/SimonBuusJensen/SimonBuusJensen.github.io/master/images/lidar-example.jpg =50x50)
![High-end LIDAR from Velodyne](https://raw.githubusercontent.com/SimonBuusJensen/SimonBuusJensen.github.io/master/images/lidar-velodyne.png =50x50)
Let's dig a bit deeper into the LIDAR sensor. The LIDAR ("**Li**ght **D**etection **A**nd **R**anging" or "**L**ight **I**maging,
**D**etection **A**nd **R**anging" go ahead and pick the acronym you like the best) is essentially a tool used for measuring distance 
to a target. 

## Results:
The proposed sensory-fusion network is evaluated on the [KITTI data set](http://www.cvlibs.net/datasets/kitti/). 
Back when the paper was published the network had a 25% and 30% better Average Precision rate (AP) than the current state-of-the-art systems for 3D localization and 3D detection.
Further, it had a 10.3% better AP than the current state-of-the-art 2D detection systems.
