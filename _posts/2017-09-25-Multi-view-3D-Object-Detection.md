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

The paper touches upon the subject of Object detection by fusing different sensor signals. 
More specifically LIDAR point clouds and RGB images. Thereby taking the best from two worlds: 
the LIDAR perceiving the depth information of the setting and the RGB images perceiving detailed semantic information.

## Keywords:
* Object Detection
* Sensor Fusion
* Deep Learning

## Content:
* 

## Results:
The proposed sensory-fusion network is evaluated on the [KITTI data set](http://www.cvlibs.net/datasets/kitti/). 
Back when the paper was published the network had a 25% and 30% better Average Precision rate (AP) than the current state-of-the-art systems for 3D localization and 3D detection.
Further, it had a 10.3% better AP than the current state-of-the-art 2D detection systems.
