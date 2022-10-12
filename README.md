# Rosping

ROS package containing a node (rosping) publishing ping or delay in ms to a certain IP address.

*This package is a fork of [jsk_3rdparty](https://github.com/jsk-ros-pkg/jsk_3rdparty/tree/master/rosping) package*

## Installation

Clone this repository:
```bash
git clone https://github.com/julesberhault/rosping.git
```

## Compiling

Compile package
```bash
catkin_make rosping
```

## Runing

Run the node with rosrun:
```bash
rosrun rosping rosping <HOSTNAME>
```
with **HOSTNAME** the IP address or hostname you wish to ping
