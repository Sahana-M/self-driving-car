This project of Self driving car has been broken down into sections where in each section I have got to learn many things.

Started with these topics ,
___
## *Computer vision -*

![Before](https://github.com/Sahana-M/Images/raw/master/test_image.jpg)

![After](https://github.com/Sahana-M/Images/raw/master/lane_detected.png)

- Detecting lanes using OpenCV
- covering algorithms like, Canny algorithm , Hought transform 
- link - https://github.com/Sahana-M/self-driving-car/tree/master/finding-lanes
___
## *Perceptron -*
- Learnt how a perceptron works and how to build a model using Keras
- Which factors decide the efficiency of a model
- learnt sigmoid activation function , Adam optimizer, Binary  cross entropy for binary classification
- Solved a simple prediciting a diabetic patient or not use case using this model 
- Used only a single hidden layer
- link - https://github.com/Sahana-M/Keras-implementations-DNN-CNN/blob/master/perceptron23.ipynb
___
## *Keras classification -* 
- This time working on a difficult data set which is a non linear data set
- Used Keras to classify this dataset
- This time with more layers of DNN , 2 Hidden layers
- link - https://github.com/Sahana-M/Keras-implementations-DNN-CNN/blob/master/deep_neural_network.ipynb
___
## *Multiclass classification using Keras -* 
- Implemented multiclass classification using Keras
- This time used One hot encoding, softmax activation function , and categorical cross entropy as it is multiclass classification
- link - https://github.com/Sahana-M/Keras-implementations-DNN-CNN/blob/master/multiclass_classification.ipynb
___
## *DNN MNIST Image Recognition -*
- Used Deep Neural networks on MNIST data set to recognise Handwritten digits using Keras
- Used relu and softmax activation functions
- Model obtained an accuracy of ~93%
- link - https://github.com/Sahana-M/Keras-implementations-DNN-CNN/blob/master/MNIST%20Deep%20learning.ipynb
___
## *CNN MNIST Image Recognition -*
- Used Convolutional neural networks this time on MNIST data set to recognise Handwritten digits
- This time did a bit of image preprocessing, One hot encoding
- Used LenNet based model to classify our MNIST data set
- accuracy ~99%, better than DNN
- link - https://github.com/Sahana-M/Handwriting-recognition-using-Convolutional-neural-network-using-Keras
___
## *Classifying Road signs -*
- dataset - https://bitbucket.org/jadslim/german-traffic-signs
- Used modified LeNet based model
- Used various measures to improve the accuracy -
  - fine tuning
  - dropout layers
  - fit generator
  - data augmentation
- link - https://github.com/Sahana-M/self-driving-car/tree/master/identifying%20traffic%20signs
___
## *Polynomial Regression -*
- A simple implementation of polynomial regression using Keras which is very much necessary for Self driving car concepts
- link - https://github.com/Sahana-M/self-driving-car/blob/master/Polynomial_regression.ipynb

___
## *Behavioural Cloning -* 
- The most important part of self driving car
- Did required image preprocessing
- data augmentation using Batch generator
- Fine tuning the model
- Used NVIDIA Neural model
- depolyed the model n Udacity self driving car simulator 
- link - https://github.com/Sahana-M/self-driving-car/tree/master/Behavioural%20cloning%20-%20Nvidia%20neural%20model



