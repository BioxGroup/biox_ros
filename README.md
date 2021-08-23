# biox_ros intro and dependencies
This repository contains the needed software to get the Biox armband into the ROS environment. Packages with armband compatibility will be shared here. The code in this repository has been tested on a UR3e with software version 5.8 as well as in ROS Noetic Gazebo.  

Dependencies include: 
- Ubuntu 20.04 with ROS Noetic
- Python 3.x
- Universal robots driver that can be found in this link(https://github.com/UniversalRobots/Universal_Robots_ROS_Driver) installing this will be shown further down.
# Biox_read
This is a simple package made to send the messages coming from the Biox Armband into ROS topics.

# Universal robots interface

## Setup
First step of the setup is to clone this repository.

`ǵit clone https://github.com/BioxGroup/biox_ros.git`

Since Noetic is not officially supported by Universal_Robots_ROS_Driver we have to build our workspace from source. 



## Simulation

## Real robot
