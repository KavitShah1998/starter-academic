---
title: Combining A* and RRT* for autonomous indoor navigation of mobile robots
subtitle: "Course : Motion Planning"
date: "2021-01-15T22:52:08.395Z"
summary: Developed a motion planning stack by combining multiple algorithms for effective indoor navigation.
draft: false
featured: false
authors: []
tags:
  - Motion Planning
  - Collision Avoidance
  - OpenCV
  - ROS
  - PID Controller
  - C++
  - C++14
  - A* 
  - RRT*
  - D*
  - Dijkstra
  - Planning under uncertainty
  - Git
  - Autonomous Navigation
  - Cpp
external_link: 
links:
  - url: https://github.com/KavitShah1998/Combined_Astar_with_RRTstar_in_ROS
    name: Code
    icon_pack: fab
    icon: github
  - url: https://drive.google.com/file/d/1M0RBCfp3IGdTZ2xd5zykxhKqTN1T0fAr/view?usp=sharing
    name: Slides
    icon_pack: fas
    icon: presentation
  - url: RBE550-final-report.pdf 
    name: PDF
    icon_pack: fas
    icon: file-pdf
image:
  filename: Robot autonomously navigating in indoor spaces
  focal_point: Smart
  preview_only: false
---
Course : Motion Planning

Problem Statement : To develop a new motion planning algorithm with quick replanning capabilities to succesfully navigate in indoor uncertain static environments

Application : Motion planning & autonomous robot navigation stack for indoor service robots

Approach : 
 * Formulated a highly-scalable complex system design for robot motion planning consisting of global planners, local planners, controllers, obstacle detection, trajectory estimation modules from scratch.

* Employed the use of A* as global planner for achieving optimality and RRT* as local planner for quick replanning in case of potential collisions.

* Added new plug-and-play feature to add new algorithms of choice for global &/or local planner which could be easily integrated. 

* Increased the algorithm database by added DFS, BFS and Dijkstra

* Developed a production quality software capable of new feature-integration with ease using C++14 in Robot Operating System with Git for CI.