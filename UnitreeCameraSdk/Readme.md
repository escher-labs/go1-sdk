Introduction{#mainpage}
---
Unitree Robotics is a energetic start-up company that focuses on the development, production and sales of high-performance quadruped robots. It has been interviewed by BBC and CCTV, and is one of the earliest company to publicly sell quadruped robots.

The company has an outstanding leadership in developing robot core components, motion control, robot perception, etc.

We attaches great importance to research and development, and thus independently developed the motors, reducers, controllers, and even some sensors of the quadruped robot.

1.Overview
---
UnitreeCameraSDK 1.0 is a cross-platform library for unitree depth cameras

The SDK allows depth and color streaming, and provides intrinsic calibration information. The library also offers pointcloud, depth aligned to color and vise-versa.

2.Dependencies
---

OpenCV, version: equal or lager than 4
Cmake, version: 


2.Build
---

```
cd UnitreeCameraSDK;
mkdir build; cd build;
cmake ..; make
```

3.Run Examples
---

Get Camera Raw Frame:
```
cd UnitreeCameraSDK ; 
./bin/example_getRawFrame 
```
Get Point Cloud:
```
cd UnitreeCameraSDK ; 
./bin/example_getPointCloud
```
