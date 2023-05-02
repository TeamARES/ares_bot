# Installation

```
mkdir ares_bot_ws
cd ares_bot_ws
mkdir src
cd src
git clone https://github.com/SaumyaRaj188/ares_bot.git
cd ..
colcon build --symlink-install
```


# Launch

```
source install/setup.bash
ros2 launch ares_bot rsp.launch.py
```
