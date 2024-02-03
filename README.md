# ROS2-Nav2

### Following Steps
- Install Nav2 on ROS2 Humble
- Generate a map with SLAM
- Make a robot navigate from point A to point B using the map

### Requirement
- Install ROS2 Humble on Ubuntu 22.04
- No need to buy any hardware
- Gazebo simulation

### Pre-requirement Steps
- Install Navigation2 and TurtleBot3
    ```bash
    sudo apt install ros-humble-navigation2 ros-humble-nav2-bringup ros-humble-turtlebot3*
    ```
- Specify the TurtleBot3 model by opening bashrc via `gedit ~/.bashrc` and save it by adding this line
  ```bash
  export TURTLEBOT3_MODEL=waffle
  ```
---------------------------

### Following Steps
1. Create `ros2_nav2_ws` folder, and go to the folder by `cd ros2_nav2_ws/`
2. Create `src` folder, and go to the folder by `cd src`
3. `ros2 pkg create --build-type ament_cmake --node-name my_node my_pkg`
4. `cd my_pkg/`
5. `code .`
6. Create `urdf` folder, and make a file named `my_robot.urdf`
7. Write the urdf code
8. `ros2 launch urdf_tutorial display.launch.py model:=/home/mahfuz/ros2_nav2_ws/src/my_pkg/urdf/my_robot.urdf`
