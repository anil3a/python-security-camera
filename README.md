Motion-detection-OpenCV
=======================

Python/OpenCV script that detect motion on webcam and allow record it to a file.

## The simple way ##

[![https://www.youtube.com/watch?v=-RUu3EcielI](https://img.youtube.com/vi/-RUu3EcielI/0.jpg)](https://www.youtube.com/watch?v=-RUu3EcielI)

Compare video frames, checking how many pixels changed.

## The smart way ##

[![https://www.youtube.com/watch?v=sRIdyfh3054](https://img.youtube.com/vi/sRIdyfh3054/0.jpg)](https://www.youtube.com/watch?v=sRIdyfh3054)

Find the contours of the moving objects and calculate the area of all of them. Then the average of the surface changing is compared with the total surface of the image and the alarm is triggered if it exceed the given threshold

## More info ##

* webcams usually need about 5 seconds to start up
* initRecorder is where video output codec can be changed
* processImage is where the cool stuff happens
* somethingHasMoved: pixel comparison
