---
title: "Turtlebot3 Navigation"
collection: projects
permalink: /projects/turtlebot3/
period: 2023.Jan - 2023.Feb
abstract: "Keywords: Dijkstra, A*, Cubic interpolation, PID control"
excerpt: "<img src='/images/turtlebot.png' width='300px'>"
date: 2023-01-05
category: "Path planning"
toc: false
---

{% include base_path %}

This is a course project for Autonomous Robot Systems at NUS. We used
- A* to find path to goals in the maze;
- Dijkstra to locate the closest free cell to the goal at the correct side of the wall;
- Cubic interpolation to smooth the trajectory;
- Weighted average of odometry and IMU to fuse the position data;
- Bidirection PID to control the turtlebot.

<div class="video_wrapper">
  <iframe src="https://www.youtube.com/embed/lsIKjBndsrU" frameborder="0" allowfullscreen></iframe>
</div>
