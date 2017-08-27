# Traffic Sign Classifier

## Overview

A simple deep convolutional neural network to classify traffic signs.

[//]: # (Image References)

[image1]: ./test-images/turn-left-ahead.jpg "Traffic Sign 1"
[image2]: ./test-images/speed-limit-70.jpg "Traffic Sign 2"
[image3]: ./test-images/priority-road.jpg "Traffic Sign 3"
[image4]: ./test-images/bumpy-road.jpg "Traffic Sign 4"
[image5]: ./test-images/speed-limit-50.jpg "Traffic Sign 5"
[image6]: ./test-images/general-caution.jpg "Traffic Sign 6"
[image7]: ./test-images/double-curve.jpg "Traffic Sign 7"
[image8]: ./test-images/slippery-road.jpg "Traffic Sign 8"

![alt text][image1] ![alt text][image2] ![alt text][image3]
![alt text][image4] ![alt text][image5] ![alt text][image6]
![alt text][image7] ![alt text][image8]

## Dependencies

 * TensorFlow >= 1.2
 * Numpy
 * Pandas
 * Matplotlib
 * scikit-learn
 * OpenCV
 * glob

## Notes

 * The dataset is [German Traffic Sign dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). Download from [here](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/581faac4_traffic-signs-data/traffic-signs-data.zip).
 * The network architecture is a extension of [LeNet-5](http://yann.lecun.com/exdb/lenet/)
 * Test accuracy ≒ 93
 
## Usage

```
jupyter notebook Traffic_Sign_Classifier.ipynb
```
