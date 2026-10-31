# Mit-Odometry-Maker-Portfolio
Maker Portfolio for Mit documenting the codebase

#What is Odometry
Odometry is a 2d position tracking algorithm created for the VEX V5 Robotics Competition

#Basic code structure
Since this project is limited to VEXcode V5, there is no feasible way to demo it besides videos of it working.
Because of these limitations, there is only one main file.

Odometry Algorithm Section: https://github.com/kadenarichardson/Mit-Odometry-Maker-Portfolio/blob/e78173f36243c4e03da22bb29f3dd783571f81bf/Main%20System%20Code#L268
Sensor declaration: 



Sensors used:
2 Rotary encoders perpendicular to each other. 1 horizontal encoder and 1 vertical encoder. Tracks motion based on how much the encoder has moved
1 Inertial sensor to track the current heading of the robot.

The Math
 1 main loop that updates every 20 ms
 Calculates change in encoder movement
 Finds the arc based on the change in angle
 Calculates the chord based on this arc
 
 
 

