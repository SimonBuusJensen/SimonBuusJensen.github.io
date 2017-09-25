---
layout: post
title: Review of "Multi-View 3D Object Detection Network for Autonomous Driving"
permalink: /3D-object-detection-network-for-autonomous driving
published: false
---
## Task list
- [x] Write an introduction
- [ ] How does the reflection of the LIDAR work? How fast is it spinning? How big an area does it cover?
- [ ] Describe the Network

## Introduction
The following is an attempt to summarize and make an easy to digest review of the paper "Multi-View 3D Object Detection Network 
for Autonomous Driving" by Xiaozhi Chen, Huimin Ma, Ji Wan, Bo Li and Tian Xia.
The paper was submitted 23rd Nov 2016 and can be found in the following [link](https://arxiv.org/abs/1611.07759)

The paper touches upon the subject of Object Detection by fusing different sensor signals using Deep Learning methods.
The sensors which are being used are the LIDAR and the RGB Stereo camera. Thereby taking the best from two worlds: 
the LIDAR perceiving the depth information of the setting and the RGB images perceiving detailed semantic information of the setting.

## Keywords:
* Object Detection
* Sensor Fusion
* Deep Learning

## Content:
### The LIDAR Sensor:
<img src="https://raw.githubusercontent.com/SimonBuusJensen/SimonBuusJensen.github.io/master/images/lidar-example.jpg" alt="Drawing" style="width: 200px; height: 200px; float: left; margin-right: 1%; margin-bottom: 0.5em;"/>
<img src="https://raw.githubusercontent.com/SimonBuusJensen/SimonBuusJensen.github.io/master/images/lidar-velodyne.png" alt="Drawing" style="width: 200px; height: 200px; float: left; margin-right: 1%; margin-bottom: 0.5em;"/>
<img src="https://raw.githubusercontent.com/SimonBuusJensen/SimonBuusJensen.github.io/master/images/kitti-dataset-car.jpg" alt="Drawing" style="width: 200px; height: 200px; float: left; margin-right: 1%; margin-bottom: 0.5em;"/>
<p style="clear: both;">
Let's dig a bit into the LIDAR sensor. The LIDAR (Originally a portmanteau of *light* and *radar* but sometimes used as an acronym for "**Li**ght **D**etection **A**nd **R**anging") is essentially a tool used for measuring distances to objects. 
The above image shows an example of a high-end LIDAR sensor from Velodyne. Other producers of the LIDAR sensor are Continental, BOSCH and LeddarTech. LIDAR was invented back in the 1960's just shortly after the laser was invented. 
In short, it calculates the distance to an object by pulsing out laser light and then measuring the time it takes for the light to reflect back into the sensor part of the LIDAR. How does the reflection on object work however?   

## Results:
The proposed sensory-fusion network is evaluated on the [KITTI data set](http://www.cvlibs.net/datasets/kitti/). 
Back when the paper was published the network had a 25% and 30% better Average Precision rate (AP) than the current state-of-the-art systems for 3D localization and 3D detection.
Further, it had a 10.3% better AP than the current state-of-the-art 2D detection systems.
