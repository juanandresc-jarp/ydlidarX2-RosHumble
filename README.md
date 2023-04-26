# ydlidarX2-RosHumble
Made changes to ydlidar repo for using the x2 lidar in Ros Humble
For using this modifications, follow the instructions of https://github.com/YDLIDAR/ydlidar_ros2_driver.

Create your workspace and under build folder install: https://github.com/YDLIDAR/YDLidar-SDK

After installing it:

cd src

git clone https://github.com/juanandresc-jarp/ydlidarX2-RosHumble.git

cd ..

colcon build --symlink-install

ros2 launch ydlidar_ros2_driver ydlidar_launch.py

!Not everything is functional, I've just made some changes on the original repo for using ydlidar x2 on Ros Humble