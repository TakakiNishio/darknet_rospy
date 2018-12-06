# darknet_ros

## Requirements
- Ubuntu 16.04
- ROS kinetic
- GPU (NVIDIA GTX1070 is confirmed)
- CUDA 8.0 (or higher)
- CuDNN 6 (or higer)
- OpenCV 3.3.1 (or higer)

## Initial build of this repository
Clone this repository using SSH.
```
$ cd <your_workspace>/src
$ git clone --recursive git@github.com:TakakiNishio/darknet_ros.git
$ cd darknet_ros/darknet && make -j4
$ cd <your_workspace>
$ catkin build
```

## Downloading weight files

Weight files can be downloaded from [this site](https://drive.google.com/open?id=1zRExBBo0Mwwq5hEcr_9zDHb7ZAPK2P-H).
Place them inside the `darknet` directory.

## Running an Example
```
$ rosrun darknet_ros darknet_webcam.py
```

