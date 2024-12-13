# Impedance Controller for Assembly Project

## Overview
This repository provides the implementation of an **Impedance Controller** designed for robotic systems to regulate interaction forces between the robot and its environment.
The controller ensures stable and compliant behavior by modulating forces and positions based on a dynamic impedance model. Therefore, we use this controller to make the inserting
action being stable and reliable.

## Use
First, you need to load the ros controller
```
roslaunch ee_cart_imped_launch load_ee_cart_imped.launch
```

Then you can actually run the controller.
```
roslaunch ee_cart_imped_launch ee_cart_imped.launch
```

For more details about the api, please check ee_cart_imped_msgs.
