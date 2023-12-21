# Installation

```
mkdir -p ares_bot_ws/src
cd ares_bot_ws/src
git clone https://github.com/TeamARES/ares_bot.git
cd ..
colcon build --symlink-install
```


# Launch
```
source install/setup.bash
ros2 launch ares_bot launch_sim.launch.py
```
