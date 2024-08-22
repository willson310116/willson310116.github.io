---
title: "Particle Filter SLAM"
excerpt: "Implement SLAM with sampling based method (particle filter) on occupancy log-odds map<br/><img src='/images/slam.png' width='480'>"
collection: portfolio
---

*ECE276A Sensing and Estimation in Robotics @ UCSD, March 2023*

SLAM (Simultaneous Localization and Mapping) is a technique used in robotics and computer vision to create a map of an unknown environment while at the same time keeping track of the robot’s position within that environment. It is a challenging problem because it involves estimating both the position of the robot and the location of landmarks in the environment simultaneously, and dealing with the uncertainty that arises from sensor noise and imperfect knowledge of the environment.

In this project, with datasets (encoder, LiDAR scan, IMU) generated from a differential-drive robot, I implemented particle filter SLAM on 2D occupancy grid map with log odds. The result should be better after some hyperparameter tuning (prone to noise). Click [here](/files/particle_filter_report.pdf) for project document, and [link](https://github.com/willson310116/Particle-Filter-SLAM) for repo!

| Scene 1    | Scene 2 |
| :--------: | :-------: |
| ![test](/gifs/parslam20.gif){: width="400px"}  | ![test](/gifs/parslam21.gif){: width="400px"}    |
