# ROS_LaneFollowerBot

## Overview
`ROS-LaneFollowerBot` is a project about lane following robot using ROS, simulation a vision-based DAS developed as part of the Driving Assistance Systems Lab IV course. 
Aim: To implement a lane-following robot using ROS, simulating a vision-based driving assistance system. Utilizing both simulated environments and real Turtlebot platforms, the project integrates sensor data processing with motion control to enable a robot to follow a specific lane, detect obstacles, and adjust its path accordingly.

## Features
- **Vision-Based Lane Following:** Utilizes camera feed to detect and follow a lane with a specific color.
- **Obstacle Detection and Avoidance:** Implements Lidar sensor data to detect obstacles and halt the robot to avoid collisions.
- **ROS Integration:** Fully integrated with ROS for efficient message passing and modular architecture.
- **Ease of Use and Extendibility:** Designed with simplicity in mind, making it easy for users to understand, use, and extend the functionality.

## Getting Started

### Prerequisites
- Ubuntu (Preferably 18.04 or 20.04)
- ROS (Robot Operating System), Melodic or Noetic
- Python 2.7 or Python 3.x (depending on your ROS version)
- Access to a Turtlebot3 or a simulation environment like Gazebo
