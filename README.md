# PupBot

![](https://img.shields.io/badge/ROS-Melodic-brightgreen.svg)

<img src="https://github.com/Alpaca-zip/PupBot/blob/main/PupBot.png">

You can see the walking algorithm of my quadruped robot. This is recommended for ROS Melodic. 

## Launch Gazebo

```
roslaunch quadruped_robot quadruped_robot_empty_world.launch
```

## Launch Walking Simulation

```
roslaunch quadruped_robot move_quadruped_robot.launch
```

q : Startup,Shutdown  
w : Increases the value of direction in the x axis (+0.25)  
a : Increases the value of turn (+0.25)  
s : Decreases the value of direction in the x axis (-0.25)  
d : Decreases the value of turn (-0.25)
