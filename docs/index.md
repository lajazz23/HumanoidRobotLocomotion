# Reinforcement Learning in Isaac Lab

You can find my forked repository on [GitHub](https://github.com/lajazz23/Unitree-G1-IsaacLab-Locomotion/tree/main).

This resource is used to document my edits to the original Isaac Lab repository for my project.

## Project overview

The Isaac Lab VR project is my project for the Summer 2025 SULI internship at Brookhaven National Lab. In this project, we build on top of the original Isaac Lab repository to create a trained Reinforcement Learning model using the [Unitree G1 robot](https://www.unitree.com/g1/) and [RL Games](https://github.com/Denys88/rl_games). We implement Virtual Reality as a method of evaluation and interaction with the robots in the simulation.

## Why Humanoid Robots?

Humanoid robots excel in human-centric environments. With little need for additional accommodations, humanoid robots exist as a practical tool for performing tasks that are unsafe, repetitive, or impractical for humans.​

### Unitree G1 Robot

The [Unitree G1](https://www.unitree.com/g1) robot was developed by Unitree Robotics, a Chinese company based in Hangzhou, China in 2024. Standing at 12.7 m tall, this humanoid robot is optimal for research and development due to its open-source SDK. Due to its compatibility with Isaac Lab, it is a great candidate for research in reinforcement learning with minimal transfer cost. Furthermore, the robot is compatible with virtual reality and teleoperation. In our project, the G1 robot has 37 joint motors, allowing for the performance of flexible tasks. 

### Unitree H1 Robot

The [Unitree H1](https://www.unitree.com/h1/) is a bigger and more powerful robot compared to the G1. It is able to perform similar tasks, and excels in stability while performing locomotion tasks. The SDK is open-source, in C++, Python, and ROS2, easily allowing it to be worked on in research. 

### Fourier GR-1

The [Fourier GR-1](https://www.fftai.com/products-gr1) was developed by Fourier as a humanoid robot standing at 16.5 m tall. With built-in emotional systems, it mimics humans and can hold a proper human-robot conversation. It uses the Fourier Smart Actuator to integrate all movements into a single module. The GR1 has been deployed into industry to perform service tasks. While teleoperation is possible, it is not fully supported.

## How Do We Train the Robot?


## Author

Jasmin Lin