# ROS odom spin  
Use ROS odometry messages to control accurate turns e.g. 180 deg on Irobot Create, can be used as a building block for navigations of autnomous vehicles. 


**[Autonomous Robotics Lab](http://campusrover.org.s3-website-us-west-2.amazonaws.com)** 

@ Celi Sun  @ Nov, 2017  @ Brandeis University

Running scripts in the package manipulates irobot to **go forward and turn 180 deg** if any obstacle detected at front (by bumper IR sensors on irbot)

This package also contains **a node that converts odometry from quaternion to euler form**, and publish to topic /odom_euler. 

## Dependencies

* ros kinetics
* [create autonomy](https://github.com/AutonomyLab/create_autonomy)
* math
* python


<img src="https://raw.githubusercontent.com/celisun/ROS_odom_spin_Irobot_Create/master/src/create-overview.png" width="180">
