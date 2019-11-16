# The Null Terminators Simulated Robot Project
> Our final project for CSE 468: Robotics Algorithms Fall 2019

This ROS package allows the user to create a differential drive robot with a two jointed arm in Gazebo. With rviz, you can move the robot around and tell it to pick up certain objects. You can then tell it to drop off the object somewhere else. 

## Installation

OS X & Linux:

```sh
git clone https://github.com/jreneew2/cse468_final.git
source /opt/ros/kinetic/setup.bash 
#or sh or zsh if you are using diff shell
cd ~/cse468_final/
catkin_make
```

## To run

```sh
source ~/cse468_final/devel/setup.sh
#or sh or zsh if you are using diff shell
roslaunch cse468_final_bot main.launch
```

## Blog Post Updates

Drew Williams – drewwill@buffalo.edu \
Sarah Schwartz – seschwar@buffalo.edu