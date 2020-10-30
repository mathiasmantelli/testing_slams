Checking how the parameters of GMapping and Hector SLAM impact their performance.
To execute this whole project, you need 5 terminal windows:
1 - roscore
2 - roslaunch jackal_gazebo jackal_world.launch
3 - roslaunch jackal_viz view_robot.launch
4 - roslaunch jackal_navigation gmapping_demo.launch
5 - roslaunch jackal_navigation odom_navigation_demo.launch

It's important to execute "source /devel/setup.bash" before roslaunch. 
To change the map resolution in Gmapping, it's necessary to edit the 'delta' param at jackal_navigation/launch/include/gmapping.launch 
