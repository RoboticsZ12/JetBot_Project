# JetBot Track Racing Project

Welcome to the JetBot Track Racing project! In this collaborative endeavor, an open-source robot powered by NVIDIA Jetson Nano was utilized to complete the task. 

# Beginning the Project

To begin, the jetbot first had to be put to a series of tests and different tunings. A few of the tunings included, 
- **Basic Motion**: Understand programmatic motor control.
- **Teleoperation**: Learn to control JetBot remotely using a gamepad controller.
- **Collision Avoidance**: Train your JetBot to avoid obstacles.
- **Road Following**: Train your JetBot to follow a predefined path.
- **Object Following**: Teach your JetBot to track and follow objects.

## Task 1: Manual Controlled Racing

For the first task, the goal is to complete three loops around the racetrack using manual control. The ultimate goal of this portion of the project solely relied on the ability of driver to manouver through the obstacle course without leaving the predefined road. 
 To accomplish this, we connected a gaming controller and tuned it so that the controller would have the capability of controlling speed with one joystick, and motion with the other. 
 
## Task 2: Automatic Controlled Racing using the Camera

In the second task, we were to use the JetBot to autonomously complete three loops using only the onboard camera feedback input. The objective was to navigate the track while adhering to traffic lights, avoiding obstacles, and staying within track boundaries.

To achieve this, we needed to consider training models for road following and collision avoidance separately before integrating them for the test runs.
All data can be found under [Autonomous Drive](JetBot/Autonomy/) folder tab. 
