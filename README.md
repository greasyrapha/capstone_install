

# Install Script for ROS Melodic with dependencies

Tested in ubuntu 18.04.06 LTS  

```
$ sudo git clone https://github.com/greasyrapha/capstone_install

$ cd capstone_install

$ ./first.sh

$ sudo reboot
```
Rebooting..
```
$ cd capstone_install

$ ./second.sh
```
Run Gazebo (no roscore needed)
```
$ roslaunch turtlebot3_gazebo turtlebot3_world.launch
```
Run SLAM with gmapping
```
$ roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping
```
Control Turtlebot with Keyboard (using WASDX)
```
$roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```
ggs
