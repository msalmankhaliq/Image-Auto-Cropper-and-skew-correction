# Image-Auto-Cropper and skew correction

An unsupervised algorithm that detects the edges of artworks in images, and automatically rotates/crops the images to eliminate the background.

## Applications

It can be useful in removing borders automatically from the artworks or images specially in a large number of quantity.


## Code Requirements 

The example code is in Python (version 3.6 or higher will work)

## Dependencies

1) import cv2
2) import imutils
3) import numpy
4) import pandas

## How to run the code?

> Install all the dependencies
> Clone the repo
> Run the notebook 'auto-crop.ipynb'
> To process your own image, change the path of the image in the above mentioned notebook
> If the code fails to detect edges on your image, then try increasing kernel values (borders of the images needs to be clear for detection)
