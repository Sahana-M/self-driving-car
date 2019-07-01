## Developed the self driving car model using Nvidia Neural Model

![Nvidia Neural model](https://cdn-images-1.medium.com/max/1600/1*HwZvJLpALucQkBuBCFDxKw.png)
___


### *Steps under gone -*

- **Clone** the data from github link - https://github.com/rslim087a/track
- **Preprocessing** the data to get the desired size of the image as well as colour scale - here YUV colour scale used, not RGB/Grayscale
- Do **data augmentation** for increasing the volumne as well as variance of images
- Data augmentation techniques used are,
  - **Zooming**
  - **Panning**
  - **Brightning & darkening**
  - **Flipping**
- Build the **Nvidia neural model** which has,
  - **5 convolutional layers**
  - **3 deep neural layers**
  
___

### *Downloading & testing the model -*
- **Download the model** into our system
- Download the **Udacity simulator from - https://github.com/udacity/self-driving-car-sim**
- Create a new environment in your anaconda navigator using ( for Windows ),
  - create create --name myenviron
- activate it using,
  - conda activate myenviron
- Install Tensorflow in myenviron,
  - conda install -c conda-forge tensorflow
- Install Keras in myenviron,
  - conda install -c conda-forge keras
- Similarly install OpenCV, Flask, Eventlet, Socketio

-Run the **drive.py program** which connects our model with our Udacity self driving car simulator (with drive.py and model.h5 in same directory)

- **Open the simulator in autonomous mode to test the self driving car**
