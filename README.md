# CosmoDeepLearningGrasper
A refined solution to perform pick and place operations using deep learning algorithms GPD and YOLO with the Aubo Robotic Arm.

## Prequisite Installations
Softwares and libraries required along with their respective installation links are provided.

- Ubuntu 16.04
- ROS Kinetic
- Python 2.7
- Darknet_ros - YOLOv4
- OpenCV >= 3.4
- GPD
- gpd_ros
- Moveit
- PCL >= 1.7
- Aruco_Ros
- Aubo_I5_Driver
- Aubo I5 Model

## Hardware Requirements
- Asus Xtion Pro RGB-D Camera
- Aubo I5 Robot
- Robotiq 85 Gripper

## Steps to Run the Programs
This section includes steps to run all the required programs along with their respective commands in sequence. It also includes steps to run object detection through darknet_ros and filter out all point cloud data except the object that was chosen using the provided commands. There are specific instructions to execute the Aubo Driver and pick and place the object.

Along with this, it provides a detailed explanation of the inner workings of various sections like camera calibration, ROS coordinate frames, object detection, cloud clustering and much more. It also lists out the Installation of CUDA and CUDNN for running programs on GPU for faster execution.

Lastly, it provides a list of common error users might face in these setups along with their solutions in detail.

Feel free to create issues or contribute to the repository owned by 'Cosmosec'.