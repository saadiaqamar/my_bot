## Robot Package Template

This is a robot package adapted from articulated robotics https://github.com/joshnewans/articubot_one.

To run:

ros2 launch my_bot launch_sim.launch.py world:=src/my_bot/worlds/obstacles.world 
ros2 launch slam_toolbox online_async_launch.py params_file:=./src/my_bot/config/mapper_params_online_async.yaml use_sim_time:=true
ros2 launch nav2_bringup navigation_launch.py use_sim_time:=true
ros2 run rviz2 rviz2


