# TELLO Drone Detection By YOLO
Tello drone with YOLO and DDPG control.


![](demo.gif)


This is My Class Final Project

Use VOC Dataset:

VOC2012 Train/val : http://pjreddie.com/media/files/VOCtrainval_11-May-2012.tar


Powered By :

- Tello Python : https://github.com/damiafuentes/DJITelloPy

- YOLO V3 implementation : https://github.com/experiencor/keras-yolo3

- Drone Tracking (DDPG) : https://github.com/keras-rl/keras-rl

# Necessary Package : #

- Python 3.7
- OpenCV
- Numpy
- CUDA Toolkit
- Gym
- Keras-rl
- Keras


# How To Use #

1- Start main.py

2- After video Display, wait 30 seconds start YOLO and DDPG

3- using T Take off 

4- Drone should track bounding box in Pygame.

P.S. root folder need VOC.h5 file : 

