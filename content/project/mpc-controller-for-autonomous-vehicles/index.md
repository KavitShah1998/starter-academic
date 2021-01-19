---
title: MPC controller for ADAS applications
subtitle: "Course : Robot Controls"
date: "2021-01-15T22:52:08.395Z"
summary: Developed an MPC-based trajectory tracking controller for combined velocity and steering control.
draft: false
featured: false
authors: []
tags:
  - Trajectory Controller
  - Closed-loop control
  - MPC
  - MATLAB
external_link: 
links:
  - url: RBE502_Robot_Control_Report.pdf
    name: PDF
    icon_pack: fas
    icon: file-pdf
image:
  filename: ''
  focal_point: Smart
  preview_only: false
---

Course : Robot Controls

Problem Statement : To develop a robust controller module to control velocity and steering angle of a vehicle. 

Application : Using the developed MPC module for lane-keeping, lane-changing and many other ADAS applications.

About the project:
* Generated a trajectory to be followed by the vehicle.

* Developed from scratch our implementation of a closed-loop trajectory tracking MPC controller in MATLAB tp track the trajectory

* Also rendered it on Automated Driving Toolbox for a real-time visualization of vehicle following the required trajectory

* Currently trying to implement it using C++ in CARLA where it could be used as a module for the autonomous driving applications. 
