# ydlidar_g2_ros

## Overview
This package launches YDlidar G2 and Rviz to show laserscan topic(**/scan**) and TF(**/tf**) based on ydlidar_ros_driver

## Prerequisite

### YDLidar SDK
This file is based on ydlidar_ros_driver, thus it also depends on YDLidar-SDK library.  
Manual for installation is on [YDLidar-SDK](https://github.com/YDLIDAR/YDLidar-SDK).  
If you already have the library, you can skip this part.

## Dependencies
- Ubuntu 20.04 LTS (Focal Fossa)
- Robotic Operating System([ROS](http://wiki.ros.org/ROS/Installation)) noetic

## Installation
```
$ cd ~/catkin_ws/src/
$ git clone
$ cd ~/catkin_ws/
$ catkin_make

# Package environment Settings
$ source ./devel/setup.sh  

# Add permanent workspace environment variables
$ echo "source ~/catkin_ws/devel/setup.bash" >> ~/.bashrc
$ source ~/.bashrc
```
## How to start?
1. Make sure that YDLidar G2 is connected to power supply and development platform.  

2. In console,
```
$ roslaunch ydlidar_g2_ros G2_view.launch
```
## Reference
- **[YDLIDAR ROS Driver](https://github.com/YDLIDAR/ydlidar_ros_driver)**

