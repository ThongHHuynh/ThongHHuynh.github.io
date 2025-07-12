---
title: "Simulation of a Multi-Modal Robot"
excerpt: |
  Tools: PX4, MAVROS, ROS, Gazebo<br/>
  A robot capable of both walking and flying is simulated in Gazebo.<br/><img src='/images/Simulation.png' alt='Multi-modal' width='500' height='300'/>
collection: projects
---

I worked on simulating a multi-modal robot capable of both terrestrial and aerial mobility.

This robot integrates two modes:
- **Walking**, using a turtlebot3 base for ground traversal.
- **Flying**, using PX4 and MAVROS for stable drone control in Gazebo.

This robot uses a D435 RealSense plugin for object detection using point cloud. It can fly up when there's an object in front of it.


Below are some visuals from the simulation:

--------

<img src="/images/Simulation_1.png" alt="Simulation1" width="500" height="300">

--------

<img src="/images/Simulation_4.png" alt="Simulation4" width="500" height="300">

--------

<img src="/images/Simulation_3.png" alt="Simulation3" width="500" height="300">

--------
