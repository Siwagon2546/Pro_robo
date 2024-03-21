# Project robotic 2 
this project use ros2 distro is humble.
# Getting started
1.Clone the repo:
```
git clone https://github.com/Siwagon2546/Pro_robo.git
```
2.Navigate to your workspace:
```
cd /workspace

```
3.Compile
```
colcon build
```
# Operating Instructions
After you build, remember to source the proper install folder...
```
cd workspace/
source install/setup.bash
```
And then run the launch file...
```
ros2 launch articubot_one launch_sim.launch.py 
```
After that run the this file to control robot
```
ros2 run articubot_one robot_control.py
```
