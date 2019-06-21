## Finding lanes using OpenCV

### *Steps undergone*

- Load the colour image with undetected lanes 
- Blur the image with **Guassian Blur** ( to reduce noise )
- Simple edge detection using **Canny algorithm**
- Finding region of interest (ROI)
- Line detection in the ROI using **Hough Transform**
- Optimising Hough Transform 

#### *Test Image*
![Test Image](https://github.com/Sahana-M/Images/blob/master/test_image.jpg)

#### *Lane detected using OpenCV*
![Lane detected](https://github.com/Sahana-M/Images/blob/master/lane_detected.png)
