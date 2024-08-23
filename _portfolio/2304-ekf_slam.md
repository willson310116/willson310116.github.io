---
title: "EKF SLAM"
excerpt: "Implement SLAM using EKF with visual data from real-world road data<br/><img src='/images/vislam.png' width='360'>"
collection: portfolio
---
*ECE276A Sensing and Estimation in Robotics @ UCSD, April, 2023*

Previously, I worked on SLAM problem with [Particle Filter Slam](/portfolio/2303-particle_filter_slam), but it's sensitive to noise and requires extensive hyperparameter tuning.

In this project, with datasets (IMU data, landmark feature points from stereo camera) generated from road data of vehicle, I implemented Extended Kalman filter (EKF) for visual-inertial SLAM and got fine results without much hyperparameter tuning. Due to computational time on landmark mapping, I only selected a portion of the features for our EKF-SLAM. The result could be better if all the features are used. Click [here](/files/vislam_report.pdf) for project document and [link](https://github.com/willson310116/ECE276A_PR3/tree/master) for repo!

| Scene 1    | Scene 2 |
| :--------: | :-------: |
| ![test](/gifs/vislam03.gif){: width="400px"}  | ![test](/gifs/vislam10.gif){: width="400px"}    |