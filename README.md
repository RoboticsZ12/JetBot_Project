# JetBot Track Racing Project

Welcome to the JetBot Track Racing project! In this collaborative endeavor, you'll be working with JetBot, an open-source robot powered by NVIDIA Jetson Nano. JetBot provides an exciting platform to explore various robotics concepts, from basic motor control to advanced AI training for tasks like collision avoidance and road following. Through this project, you'll not only gain proficiency with JetBot but also delve into neural network data collection and training, expanding the horizons of your robotics knowledge.

## Getting Started

To begin your journey with the JetBot Track Racing project, visit the [JetBot website](https://jetbot.org/master/) where you can find comprehensive resources and documentation. While the website covers various tutorials, since you'll be provided with a pre-built JetBot, you can skip sections related to assembly and basic setup.

However, to ensure compatibility with your project's specific requirements, it's recommended to set up the software using the Jetson Nano (4GB) image provided on the website.

### Examples

Explore the provided Jupyter notebooks, including:

- **Basic Motion**: Understand programmatic motor control.
- **Teleoperation**: Learn to control JetBot remotely, potentially using a gamepad controller.
- **Collision Avoidance**: Train your JetBot to avoid obstacles.
- **Road Following**: Train your JetBot to follow a predefined path.
- **Object Following**: Teach your JetBot to track and follow objects.

Additionally, there are more community-contributed examples you can explore to enhance your understanding.

## Task 1: Manual Controlled Racing

For the first race, your goal is to complete three loops around the racetrack using manual control. Your racing score will be based on various criteria, including total time, staying within track boundaries, avoiding obstacles, and minimizing penalties.

You have two options for manual control:
1. **Control Buttons on Screen**: Create on-screen buttons for directional control.
2. **Gamepad Controller (recommended)**: Connect a gamepad controller for intuitive motion control.

Feel free to explore alternative control methods, but ensure you understand the associated code.

## Task 2: Automatic Controlled Racing using the Camera

In the second race, your JetBot must autonomously complete three loops using only onboard camera input. The objective is to navigate the track while adhering to traffic lights, avoiding obstacles, and staying within track boundaries.

To achieve this, consider training models for road following and collision avoidance separately before integrating them for the race. Utilize the provided notebooks for data collection, training, and testing.
