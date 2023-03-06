# Machine-Learning-associated-Motion-Sensing-App
This repository contains the development of a Machine Learning associated motion sensing app. The basic software tool used to develop the app is Android Studio.

This app that could classify the motion of a mobile device into 7 different motion classes as, 
1. walking forward
2. walking backward
3. tuning left
4. turning right
5. driving forward
6. driving backward
7. standing still

The mobile device's motion was classified using an accelerometer, a gyroscope, and a support vector machine. For each time the position of the device changes get the linear acceleration along Y-axis and rotational acceleration around Z-axis using the accelorometer and the gyroscope and test the data with the model.

I first developed the app without SVM and then included SVM for better classification and smoothness of output.
I trained the model using 100 data samples.

I used the library "libsvm" to implement the ML model easily.

SVM parameters used are,
  1. Kernel = linear
  2. Type = C-Support Vector Classification 
  3. C parameter of C-SVC = 10
  4. Gamma  = 0.5

## The output result is as follows.

https://user-images.githubusercontent.com/56619402/223022967-2737aba1-df19-4154-a3f1-bf770002edc7.mp4

