# ROS2-Nav2

### Following Steps
- Install Nav2 on ROS2 Humble
- Generate a map with SLAM
- Make a robot navigate from point A to point B using the map

### Requirement
- Install ROS2 Humble on Ubuntu 22.04
- No need to buy any hardware
- Gazebo simulation

### Steps
- Install Navigation2 and TurtleBot3
    ```bash
    sudo apt install ros-humble-navigation2 ros-humble-nav2-bringup ros-humble-turtlebot3*
    ```
- Specify the TurtleBot3 model by opening bashrc via `gedit ~/.bashrc` and save it by adding this line
  ```bash
  export TURTLEBOT3_MODEL=waffle
  ```
  
  
