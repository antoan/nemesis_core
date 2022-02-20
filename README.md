# nemesis_core

![Mapping Session](/docs/images/nemesis_mapping.gif)

This repository is part of Nemesis Robot. A high level overview of this project can be found in this post https://antoan.github.io/Nemesis/

It covers the perception, simultaneous navigation and navigation components of the Nemesis Robot stack, with some very early  stage autonomous navigation support with `move_base`, on ROS Melodic. 

Lauch files for Intel D435i depth and T256 Visual Intertial tracking cameras used for the project are included in the `nemesis_navigation package`. `rtabmap_ros` is used for mapping with odometry input from the T265. Librealsense, the underlying sensors driver is setup via the Realsense distribution install (2) method.

<p align="center">
  <img src="/docs/images/20220204_164520.jpg" width="200">
  <img src="/docs/images/2021-11-09 23-06-32.jpg" width="200">
  <img src="/docs/images/2021-12-06 14-20-24.jpg" width="200">
  <img src="/docs/images/2021-12-11 01-37-28.jpg" width="200">
  <img src="/docs/images/2021-12-11 21-59-10.jpg" width="200">
  <img src="/docs/images/2021-12-14 21-38-54.jpg" width="200">
  <img src="/docs/images/2021-12-14 22-58-22.jpg" width="200">
</p>

- nemesis_navigation : perception & navigation.
- nemesis_viz : Visualization (rviz) configuration.
