**ZYBERG - Autonomous Mobile Robot using ROS2 Humble**

Welcome to the ZYBERG project, an autonomous mobile robot powered by ROS2 Humble. This project aims to create a versatile and intelligent robot capable of navigating its environment using cutting-edge technologies. Below, you'll find essential information on the hardware setup, software components, and how to replicate and contribute to this exciting venture.
Table of Contents

    Introduction
    Hardware
    Software Components
    Installation
    Usage
    Contributing
    License

Introduction

ZYBERG is an autonomous mobile robot developed using ROS2 Humble on Ubuntu 22.04. The project integrates the power of ROS2 with the capabilities of the Raspberry Pi 4 (8 GB), RPLidar A1, Arduino Nano, Cytron MDD10A Motor Driver, and Cytron 12V Encoder Motor. The robot is equipped with ROS2 packages such as nav2 for navigation and SLAM for simultaneous localization and mapping.
Hardware

The ZYBERG robot incorporates the following hardware components:

    Raspberry Pi 4 (8 GB)
    RPLidar A1
    Arduino Nano
    Cytron MDD10A Motor Driver
    Cytron 12V Encoder Motor

Software Components

The software stack of ZYBERG includes various ROS2 packages, ensuring a robust and intelligent autonomous system:

    nav2: ROS2 navigation stack for robot navigation.
    slam_toolbox: Toolbox for developing SLAM-based applications in ROS2.

Additionally, external packages used in the project are:

   [ babakhani/rplidar_ros2: ROS2 driver for RPLidar A1.](https://github.com/babakhani/rplidar_ros2.git)
[    joshnewans/serial_motor_demo: Demo for serial motor control.](https://github.com/joshnewans/serial_motor_demo.git)
