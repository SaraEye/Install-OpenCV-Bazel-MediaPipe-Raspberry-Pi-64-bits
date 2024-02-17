# Install-OpenCV-Bazel-MediaPipe-Raspberry-Pi-64-bits
<img src="https://sarakit.saraai.com/images/_mainboard/SaraKIT_MainboardBig.png" width="600">

## OpenCV, Bazel, MediaPipe installation script for a Raspberry Pi with 64-bits OS

[![License](https://img.shields.io/badge/license-Apache%202-blue)](https://opensource.org/licenses/Apache-2.0)<br/>

This is a simplified way to install OpenCV, Bazel and MediaPipe for Raspberry Pi 4 64 bit (5.15.84-v8+, 6.1.21-v8+)<br/>
For more information see [SaraKIT for Raspberry Pi](https://sarakit.saraai.com/getting-started/software)

------------

## Installing OpenCV.
for OpenCV 4.5.1 version:
```
$ wget --backups=1 https://saraai.com/_SaraKIT/opencv/4.5.1/opencv_4.5.1_install.sh
$ sudo chmod +x opencv_4.5.1_install.sh
$ ./opencv_4.5.1_install.sh

```
------------

## Installing Bazel.
for Bazel 4.2.1 version:
```
$ wget --backups=1 https://saraai.com/_SaraKIT/bazel/4.2.1/bazel_4.2.1_install.sh
$ sudo chmod +x bazel_4.2.1_install.sh
$ ./bazel_4.2.1_install.sh

```
for Bazel 5.0.0 version ("find_cpp_toolchain" problem with mediapipe):
```
$ wget --backups=1 https://saraai.com/_SaraKIT/bazel/5.0.0/bazel_5.0.0_install.sh
$ sudo chmod +x bazel_5.0.0_install.sh
$ ./bazel_5.0.0_install.sh

```
for Bazel 5.2.0 version (compatible with the current version of mediapipe):
```
$ wget --backups=1 https://saraai.com/_SaraKIT/bazel/5.2.0/bazel_5.2.0_install.sh
$ sudo chmod +x bazel_5.2.0_install.sh
$ ./bazel_5.2.0_install.sh

```
------------

## Installing MediaPipe.
for Face Detection and Face Mesh
```
$ wget --backups=1 https://saraai.com/_SaraKIT/mediapipe/mediapipe_install.sh
$ sudo chmod +x mediapipe_install.sh
$ ./mediapipe_install.sh

```
------------

## See more

### SaraKIT - Self Balancing Robot
Example of use, demonstration of the speed and power of BLDC motors<br>
<div align="center">
  <a href="https://saraai.com/_SaraKIT/video/SaraKIT_Self_Balancing_Robot_with_Raspberry_Pi4.mp4"><img src="https://saraai.com/_SaraKIT/images/sbr.jpg" width=50% alt="IMAGE ALT TEXT"></a>
</div>
<br>

## Video with a ready example using Lego bricks:
<div align="center">
  <a href="https://saraai.com/_SaraKIT/video/SaraKIT_Lego_RC_Car.mp4"><img src="https://saraai.com/_SaraKIT/images/LegoRCCar.jpg" width=50% alt="IMAGE ALT TEXT"></a>
</div>

### SaraKIT - Color Tracking:

![SaraKIT_ColorTracking](https://github.com/SaraEye/SaraKIT-Face-Tracking-MediaPipe-Raspberry-Pi-64bit/assets/35704910/7120ee8a-7612-4d82-8a3c-8cf38c451009)

[Video Link](https://saraai.com/_SaraKIT/video/SaraKIT_ColorTracking.mp4)

### SaraKIT - Face Detection, Face Mesh:

![SaraKIT_Face](https://github.com/SaraEye/SaraKIT-Face-Tracking-MediaPipe-Raspberry-Pi-64bit/assets/35704910/5aebf67d-e821-4c28-b48f-2b3540df5b75)

[Video Link](https://saraai.com/_SaraKIT/video/SaraKIT_Face.mp4)

### SaraKIT - Object Detection:

![SaraKIT_Object_Detection](https://github.com/SaraEye/SaraKIT-Face-Tracking-MediaPipe-Raspberry-Pi-64bit/assets/35704910/e76bcf47-3d1c-4179-a330-c69601f94a8a)

[Video Link](https://saraai.com/_SaraKIT/video/SaraKIT_Object_Detection.mp4)

## SaraAI LLC

Website: [https://SaraAI.com](https://SaraAI.com)<br>
Project Page: [https://SaraKIT.SaraAI.com](https://SaraKIT.SaraAI.com)

