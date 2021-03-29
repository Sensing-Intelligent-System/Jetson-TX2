# Jetson-TX2

# Making ros docker image
*You should run this code on a **Jetson device** (Nano, TX, Xavier, etc.)*

dependencies: 
- CUDA 10.1
- Python X.X
- Pytorch 1.X.0
- ROS(Melodic)
- Librealsense

## How to build docker image:
```
tx2 $ cd [your Dockerfiles/ path]
tx2 $ source docker_build.sh
```

## How to run
```
tx2 $ cd [your Jetson-TX2/ path]
tx2 $ source docker_run.sh
```
***If you want to enter same container, run this.***
```
tx2 $ source docker_join.sh
```
