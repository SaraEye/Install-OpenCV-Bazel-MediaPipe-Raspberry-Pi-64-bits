# Install-OpenCV-Bazel-MediaPipe-Raspberry-Pi-64-bits
<img src="https://sarakit.saraai.com/images/_mainboard/SaraKIT_MainboardBig.png" width="600">

## OpenCV, Bazel, MediaPipe installation script for a Raspberry Pi with 64-bits OS

[![License](https://img.shields.io/badge/license-Apache%202-blue)](https://opensource.org/licenses/Apache-2.0)<br/>

This is a simplified way to install OpenCV, Bazel and MediaPipe for Raspberry Pi 4 64 bit (5.15.84-v8+)<br/>
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
