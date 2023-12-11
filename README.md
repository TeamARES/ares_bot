# Installation

```
mkdir -p ares_bot_ws/src
cd ares_bot_ws/src
git clone https://github.com/SaumyaRaj188/ares_bot.git
cd ..
colcon build --symlink-install
```


# Launch

  1. Launching Robot Model with Robot State Publisher:
  ```
  source install/setup.bash
  ros2 launch ares_bot launch_sim.launch.py
  ```

  2. Launching Robot Model with ROS2 Control:
  ```
  source install/setup.bash
  ros2 launch ares_bot launch_sim.launch.py
  ```
