## SpiNNaker-ROS messages

This repository contains custom ROS-messages for the communication between the Robot Operating System (ROS) and the SpiNNaker neuromorphic hardware. 

The **Pop_List** message type is used in

https://github.com/Erzcoder/spinn_ros_msgs

and in

https://github.com/Roboy/LSM_SpiNNaker_MyoArm.git

It can hold the spike rates of mulitple neurons as an array of 32-bit integer values. 

Additionally, this repository contains the custom message types **Myo_Joint_Angle.msg** and **Myo_Two_Motors.msg** which have been used in the above LSM_SpiNNaker_MyoArm project for the communication with the physical and virtual robot.  
