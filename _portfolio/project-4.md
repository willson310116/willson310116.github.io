---
title: "Collision detection & Path planning"
excerpt: "Performance comparision of algorithms for path planning with collision detection<br/><img src='/images/path_planning.png' width='480'>"
collection: portfolio
---
*ECE276B Planning and Learning in Robotics @ UCSD, May, 2023*

Path planning in robotics refers to the process of determining an optimal path or trajectory for a robot to navigate from its current location to a desired goal location while avoiding obstacles and adhering to certain constraints. It is a crucial component of robotic systems, enabling them to autonomously navigate and accomplish tasks in complex and dynamic environments. The goal of path planning is to generate a collision-free and efficient path that minimizes costs such as distance, time, or energy consumption.

In this project, I implemented the A-star and collision detection algorithm, and compared A-star with RRT series algorithm on seven different environments and discussed their advantages and disadvantages. Click [here](/files/motion_report.pdf) for project document to see more results, and [link](https://github.com/willson310116/Path-planning) for repo!

| Algorithm    | Visualization | Time (sec)
| :--------: | :-------: | :-------: |
| A-star w/ epsilon=1  | ![test](/images/Astar1.png){: width="600px"}    | 45.52 |
| A-star w/ epsilon=5  | ![test](/images/Astar5.png){: width="600px"}    | 0.72 |
| RRT  | ![test](/images/RRT.png){: width="600px"}    | 0.13 |
| RRT Connect	  | ![test](/images/RRTc.png){: width="600px"}    | 2.13 |
| RRT-Star  | ![test](/images/RRTstar.png){: width="600px"}    | 0.22 |