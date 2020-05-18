<p align="center">
<img src="https://github.com/ivanseibel/assets/blob/master/img/trackface/tracjface-with-trackingjs/trackface-with-trackingjs-01.png?raw=true" width="250px">
</p>

# Facetracking with tracking.js library

## Description

This is a simple project to experiment with face tracking using the [tracking.js library](https://trackingjs.com/).

In particular, this first example takes a picture of the webcam and crops the image using the face track with reference. This can be useful if you have an application that needs to capture user photos and you want to avoid capturing unnecessary spaces to keep images small.

## Notes

While developing this simple example I observed that it (apparently) have no option to set camera resolution and this could cause troubles in some kinds of applications. To change camera resolution I had to apply the configurations through getUserMedia method and because this, browser will ask you 2 times to allow video stream :disappointed:.

I have intention to fork the original component project to improve this question in a near future.
