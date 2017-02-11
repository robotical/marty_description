# marty_description
ROS package containing the description of Marty the Robot (Visual, URDF, Meshes)

## Instalation
Before this ROS package is properly setup as an official ROS package (i.e. sudo apt-get install ros-$ROS_DISTRO-marty-description), follow this guide to install:

`mkdir -p ~/inst_ws/src && cd ~/inst_ws/src`

`catkin_init_workspace`

`git clone https://github.com/robotical/marty_description`

After authentification, you need sudo rights to install in /opt/ros

`sudo su` (Enter sudo password)

`source /opt/ros/$ROS_DISTRO/setup.bash && cd ..`

`catkin_make install -DCMAKE_INSTALL_PREFIX=/opt/ros/$ROS_DISTRO`

Check files are properly installed in `/opt/ros/$ROS_DISTRO/share/marty_description`, then delete inst_ws if necessary.
