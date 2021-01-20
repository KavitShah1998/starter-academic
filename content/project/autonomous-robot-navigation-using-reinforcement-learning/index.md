---
title: RoboNav - Autonomous robot navigation using reinforcement Learning
subtitle: "Course : Reinforcement Learning"
date: "2021-01-15T22:52:08.395Z"
summary: Trained robot agent on DQN and DDPG to autonomously navigate in an indoor dynamic environment
draft: false
featured: false
authors: []
tags:
  - Motion Planning
  - Reinforcement Learning
  - DQN
  - DDPG
  - PyTorch
  - Python
  - Autonomous Navigation
  - Obstacle Avoidance
  - Git
  - ROS
external_link: 
links:
  # - url: https://github.com/KavitShah1998/Combined_Astar_with_RRTstar_in_ROS
  #   name: Code
  #   icon_pack: fab
  #   icon: github
  - url: RoboNav-Final-Presentation.pptx
    name: Slides
    icon_pack: fas
    icon: presentation
  - url: RoboNav-Poster-Presentation.pptx
    name: Poster
    icon_pack: fas
    icon: presentation
  - url: RL__Project_Proposal.pdf 
    name: PDF
    icon_pack: fas
    icon: file-pdf
image:
  filename: Robot autonomously navigating in indoor spaces
  focal_point: Smart
  preview_only: false
---
Course : Reinforcement Learning

Problem Statement : To train an agent to autonomously navigate in an indoor dynamic environment for reaching a desired goal

Application : Autonomous robot navigation for indoor service robots

Approach : 
 * Trained the robot agent using reinforcement learning algorithms of Deep Q Network and Deep Deterministic Policy Gradient in ROS to compare the effectiveness of the two & benchmarked them with the move_base package of ROS Navigation Stack.

* The input to the agent is a laser range data around the robot and its current position & orientation which on passing through a deep network gives most feasible robot action (go straight , take a slight/steep left, take a slight/steep right).

 * Achieved 70% success rate for DQN & 90% success rate for DDPG.