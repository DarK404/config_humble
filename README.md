# ur3e_gripper_humble_moveit2
Create workspace and clone this repo:
````
source /opt/ros/humble/setup.bash
git clone https://github.com/DarK404/config_humble.git -b master
mv -T config_humble src 
cd src
git clone https://github.com/PickNikRobotics/robotiq_85_gripper.git
cd ..
colcon build --symlink-install
source install/setup.bash
ros2 launch moveit_config demo.launch.py
````

