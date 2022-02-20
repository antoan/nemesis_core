# nemesis_core

![Mapping Session](/docs/images/nemesis_mapping.gif)

This repository is part of Nemesis Robot. A high level overview of this project can be found in this post https://antoan.github.io/Nemesis/

It covers primarily the perception, simultaneous navigation and navigation components of the Nemesis Robot stack, with some very early  stage autonomous navigation support with `move_base`, on ROS Melodic. 

Lauch files for Intel D435i depth and T256 Visual Intertial tracking cameras used for the project are included in the `nemesis_navigation package`. `rtabmap_ros` is used for mapping with odometry input from the T265. Librealsense, the underlying sensors driver is setup via the Realsense distribution install (2) method.




