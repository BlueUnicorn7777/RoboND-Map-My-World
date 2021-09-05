# RoboND-Map-My-World
To run -
- cd /RoboND-Map-My-World/catkin_ws 
- cd src && catkin_init_workspace
- cd ../catkin_ws 
- catkin_make
- source devel/setup.bash
- roslaunch my_robot world.launch
- 
-

- For Mapping open a new terminal
- cd /RoboND-Map-My-World/catkin_ws 
- source devel/setup.bash
- roslaunch roslaunch my_robot mapping.launch
-
-

- open a new terminal
- cd /RoboND-Map-My-World/catkin_ws 
- source devel/setup.bash
- rosrun teleop_twist_keyboard teleop_twist_keyboard.py 
-
-

- For Localization open a new terminal
- cd /RoboND-Map-My-World/catkin_ws 
- source devel/setup.bash
- roslaunch roslaunch my_robot Localization.launch
-
-
- To view the database rtabmap-databaseViewer
- rtabmap-databaseViewer /RoboND-Map-My-World/ScreenShots/rtabmap.db

-
-




