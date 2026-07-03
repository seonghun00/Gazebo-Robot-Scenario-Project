# ROS2-Gazebo-Robot-Scenarios

#### English | [Korean](README.ko.md)

> This repository is for designing logistics robot and serving robot work scenarios,  
and recording the implementation process in a Gazebo simulation environment.

## Purpose

The goal of this project is to organize robot task flows for warehouse and restaurant environments,  
then implement them step by step in Gazebo.

The project will be expanded from basic navigation to obstacle avoidance, exception handling,  
and multi-robot cooperation.

## Checklist

### Common

- [ ] Set up ROS2 Humble development environment
- [ ] Build Gazebo simulation environment
- [ ] Create basic robot URDF model
- [ ] Add 2D LiDAR sensor
- [ ] Generate map using SLAM
- [ ] Implement Nav2-based waypoint navigation

### Logistics Robot

- [ ] Build warehouse Gazebo world
- [ ] Place storage, packing, waiting, and charging zones
- [ ] Create rack models
- [ ] Model lift-type robot structure
- [ ] Implement rack entry and lift-up motion
- [ ] Handle occupied destination exception
- [ ] Implement intersection traffic priority control

### Serving Robot

- [ ] Build restaurant Gazebo world
- [ ] Place kitchen, pickup station, tables, waiting, and charging zones
- [ ] Create serving robot URDF model
- [ ] Implement pickup station → table → return navigation
- [ ] Implement hallway obstacle avoidance scenario
- [ ] Handle delayed food pickup situation
- [ ] Implement collision detection and emergency stop scenario
