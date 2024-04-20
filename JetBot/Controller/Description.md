## Teleoperation

The teleoperation file consists of setting up the external controller for the jetbot. Due to the first part of the project requiring us to control the jetbot via a gaming controller, we needed to utilize the provided library provided by the jetbot website to link the controller to the jetbot. All code is as the default code of given by jetbot, however, my group did change the characteristics of the controller a bit. 

The default setup utilizes the controller in a way that makes it incredibly difficult to drive. Basically, both controller knobs controlled both the speed and direction of the jetbot. In other words, we needed to push both knobs forward at the same speed and position in oder to move the robot where we intend. This setup made the controller incredibly sensitive and not feasible for acccurate driving communication. 

To compensate for this, we ended up scowering Github for sample jetbot code to change the knob functionality. We desired to have one knob control speed, and the second knob to control the direction of the jetbot. This proved to lower the sensitivity of the controller and lead to more accurate driving when implenting on the demo board seen in the main README file. 
