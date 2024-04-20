# JetBot Track Racing Project

Welcome to the JetBot Track Racing project! In this collaborative endeavor, an open-source robot powered by NVIDIA Jetson Nano was utilized to complete the task. The NVIDIA jetbo website that we used is provided here, [https://jetbot.org/master/](https://jetbot.org/master/). 

# Beginning the Project

To begin, the jetbot first had to be put to a series of tests and different tunings. A few of the tunings included, 
- **Basic Motion**: Understand programmatic motor control.
- **Teleoperation**: Learn to control JetBot remotely using a gamepad controller.
- **Collision Avoidance**: Train your JetBot to avoid obstacles.
- **Road Following**: Train your JetBot to follow a predefined path.
- **Object Following**: Teach your JetBot to track and follow objects.



## Task 1: Manual Controlled Racing

For the first task, the goal is to complete three loops around the racetrack using manual control. The ultimate goal of this portion of the project solely relied on the ability of driver to manouver through the obstacle course without leaving the predefined road. 
 To accomplish this, we connected a gaming controller and tuned it so that the controller would have the capability of controlling speed with one joystick, and motion with the other. The steps to set up this controller can be found under the "Teleoperation" folder, or the tab provided. 
[Teleoperation](JetBot/Controller/Teleoperation)
 
## Task 2: Automatic Controlled Racing using the Camera

In the second task, we were to use the JetBot to autonomously complete three loops using only the onboard camera feedback input. The objective was to navigate the track while adhering to traffic lights, avoiding obstacles, and staying within track boundaries.

To achieve this, we needed to consider training models for road following and collision avoidance separately before integrating them for the test runs.
All data, and further description, can be found under [Autonomous Drive](JetBot/Autonomy/src/Recorded_data) folder tab. 

If the you wish to acquire the code that was utilized, along with steps from the JetBot website, please see [Code & Walk Through](JetBot/src)

## Summary:
This project has taught the group the power of teaching an AI to operate under certain circumstances and have the ability of controlling actuation from a camera input. It highlighted the potential for AI to navigate complex environments autonomously while continually scanning for certain digital outputs, such as stoplights for our project. By recording various images such as [BLOCKED](JetBot/Autonomy/src/Recorded_data/Blocked) and  [FREE](JetBot/Autonomy/src/Recorded_data/Free) images, we basically "teach" the jetbot where the desired path is and how it should navigate itself through the obstacles.

This showed us the basics of how AI works and how it can be implemented into a real world scenario. Cars with autonomous driving have these capabilites, and as autonomy continues to grow, robotic vision and the many uses such as object detection will continue to be the object that spearheads the advancement of autonomy.

## About the Team
- ## Frank Zachman ##: Spring 2024 graduate in Mechanical Engineering. Minoring in Math & Electrical/Mechatronics engineering.
- ## Elijah Weddle ##: Spring 2024 graduate in Mechanical Engineering. Minoring in Math & Mechatronics engineering.
- ## Zechariah Georgian ##: Fall 2024 graduate in Mechatronics/Robotics Engineering. Minoring in Math.

![image](https://github.com/RoboticsZ12/JetBot_Project/assets/142946153/f478ea38-f1e8-4bee-9aa3-173c3a1f17bb)

