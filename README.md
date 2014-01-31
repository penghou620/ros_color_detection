ros-color-detection
===============

OpenCV and ROS Color Detection

This package depends on [ros-groovy-camera-umd](http://wiki.ros.org/camera_umd) package.

## Installation

1. Install camera-umd package

		sudo apt-get install ros-groovy-camera-umd
	
2. Install ros_color_detection

		mkdir -p ~/ros/
		export ROS_PACKAGE_PATH=~/ros/:$ROS_PACKAGE_PATH
		cd ~/ros/
		git clone https://github.com/dustsnow/ros_color_detection.git
		rospack profile

## Configuration

	cd ~/ros/ros_color_detection
	source setup.sh
	rosmake
	
## Run

	roslaunch ros_color_detection color_detection.launch
