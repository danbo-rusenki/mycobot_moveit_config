# sixdofarm_moveit_config2

参考にしているロボット
https://shop.elephantrobotics.com/products/mycobot-pi-worlds-smallest-and-lightest-six-axis-collaborative-robot

## Installation

### Build from source

```sh
# download
mkdir -p ~/mycobot_ws/src
cd ~/mycobot_ws/src
git clone https://github.com/danbo-rusenki/sixdofarm_moveit_config2.git

# build
cd ~/mycobot_ws
colcon build --symlink-install

```

## Quick Start
```sh
source ~/mycobot_ws/install/setup.bash
ros2 launch sixdofarm_moveit_config2 demo.launch.py 
```

<img src=https:https://github.com/danbo-rusenki/sixdofarm_moveit_config2/blob/main/image1.png width=400px/>
