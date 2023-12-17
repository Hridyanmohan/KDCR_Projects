This repo contains a ROS driver and ROS configuration files (URDF description, Gazebo launch files, 
    config, launch files) for the Custom Made Mobile robots.
Created a custom robot named as Explorer Bot .Two wheel Differential Drive type , 
    created from scratch using URDF containing joints, links, Visual, Collission, Inertia.
    Once the robot has been created add Gazebo Plugins into it  ( Differential Drive and Laser Scanner ) into URDF of the robot. 
    This will lead to driving the robot and reading laser scan values from inside of simulation.
    After understanding all the basics of with a Custom mobile Robot, move to a very well 
    known ROS package SLAM which contains multiple nodes for mapping a environment , THen Utilize 
    Gmapping Node with lidar sensor as a source. 
    After that create a room for Autonomous Navigation using Gazebo Model Builder tool. 
    THe robot will perform Autonomous driving using Navigation Stack and Path Planning algorithms from Navigation Stack.
    Rviz and Gazebo used for Visualization
