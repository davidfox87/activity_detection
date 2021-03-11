


# Activity Recognition from a Single Chest-Mounted Accelerometer



## Table of contents

* [General info](#general-info)

* [Setup](#setup)



# General info

The dataset collects data from a wearable accelerometer mounted on the chest. Uncalibrated Accelerometer Data are collected from 15 participants performing 7 activities.

The dataset is intended for Activity Recognition research purposes. It provides challenges for identification and authentication of people using motion patterns.



In this mini-project, I apply a convolutional neural network model (Tensorflow/Keras) to classify windows of x, y, z time series accelerometer data.

Although, this was a labeled dataset, I also attempted to automatically reproduce these labels by clustering small windows of x, y, z data through 

automatic feature learning using convolutional autoencoders. This is still a work in progress and I am currently learning how to do this.


The csv dataset contains data from a wearable accelerometer mounted on the chest:
* Sampling frequency of the accelerometer: 52 Hz
* Accelerometer Data are Uncalibrated
* Number of Participants: 15
* Number of Activities: 7

Dataset Information
* Data are separated by participant
* Each file contains the following information
       ---- sequential number, x acceleration, y acceleration, z acceleration, label 
* Labels are codified by numbers
  - Working at Computer
  - Standing Up, Walking and Going up\down stairs
  - Standing
  - Walking
  - Going Up\Down Stairs
  - Walking and Talking with Someone
  - Talking while Standing


I uploaded these codes to demostrate the following abilities:



* Excellent understanding of Deep Learning methodologies for time series classification.

* Experience with deep neural network architectures and software frameworks like TensorFlow.

* Programming skills in Python and familiarity with python libraries like numpy, scikit-learn, pandas etc.







# Setup



### Prerequisites



What things you need to install the software and how to install them



```

Give examples

```



## Authors



* **David Fox** - *Initial work* - [David Fox github profile](https://github.com/davidfox87)
