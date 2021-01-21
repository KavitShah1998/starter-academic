---
title: Dynamic motion planning for autonomous and semi-autonomous mobile robot navigation
subtitle: "Directed Research"
date: "2021-01-15T22:52:08.395Z"
summary: Developing a dynamic motion planning approach with active obstacle avoidance for mobile robots by planning in velocity spaces
draft: false
featured: false
authors: []
tags:
  - Motion Planning
  - Computer Vision
  - Dynamic Obstacle Avoidance
  - Collision Avoidance
  - ROS
  - ORCA
  - OpenCV
  - C++
  - C++11
  - Cpp
external_link: 
links:
  - url: https://github.com/KavitShah1998/DynamicObstacleAvoidance
    name: Code
    icon_pack: fab
    icon: github
  - url: https://drive.google.com/file/d/1Do_gSt6SoaLU6DM2C7sr9fxBgGQeQxEQ/view?usp=sharing
    name: Slides
    icon_pack: fas
    icon: presentation
  - url: Directed_Research-report.pdf 
    name: PDF
    icon_pack: fas
    icon: file-pdf
image:
  filename: Dynamic obstacle avoidance for nursing robots in hospitals
  focal_point: Smart
  preview_only: false
---
Course : Directed Research

Problem Statement : To develop a novel dynamic obstacle avoidance approach for assistive-autonomy of autonomous and tele-operated mobile robots with dynamic collision and obstacle avoidance

Application : Tele-operated nursing robots to serve quarantined patients in hosppitals

Approach : 
 * Developed a dynamic motion planning approach based on planning in velocity spaces instead of conventional path planning.

 * Employed the use of Optimal Reciprocal Collision Avoidance (ORCA) for velocity planning. The algorithm, rather than giving a set of points for navigation, gives instantaneous robot velocity close to the desired velocity which if followed by the robot avoids collisions with all obstacles around it.

 * Generated static environment info by employing SLAM and image processing to generate obstacle and edge data.

 * Using Kalman filter based approach for object detection and motion estimation with 2d LiDAR sensors generated dynamic obstacle data

* Achieved robust and complete static obstacle avoidance in different environments and currently working to achieve dynamic obstacle avoidance