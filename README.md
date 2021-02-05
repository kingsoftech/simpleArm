# simple_arm_01
# simple_arm_01
A mini-project for RoboND's ROS Basics Module, Lesson 02.

```
git clone this repo inside your src folder in your workspace
open a terminal

navigate to your workspace

catkin_make 

source devel/setup.bash

roslaunch simple_arm robot_spawn.launch
open another terminal

navigate to your workspace 

run source devel/setup.bash

to run the simple_mover node

rosrun simple_arm simple_mover

to run the look_away node 
roslaunch simple_arm robot_spawn.launch

rqt_image_view /rgb_camera/image_raw

rosservice call /arm_mover/safe_move "joint_1: 0 joint_2: 0"
see what happens
