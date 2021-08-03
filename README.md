# Social-Distance-Monitoring
Monitoring Social Distancing using Yolo Algorithm.

## Workflow

Input Video

Object Detection

Object Localisation

Monitoring distance between objects

Checking the threshold

Detecting people at risk

## YOLO (You Only Look Once)

YOLO is an algorithm used for object detection.

It processes 45 frames per second in real time.

It uses convolutional neural networks (CNN) to detect objects in real-time.

It takes the entire image in a single instance and predicts the bounding box coordinates and class probabilities for these boxes.

## Object Detection

RESIDUAL BLOCKS

![image](https://user-images.githubusercontent.com/71822090/128061506-3c188c88-661c-4a43-8838-942f7f482f95.png)

BOUNDING BOX REGRESSION

![image](https://user-images.githubusercontent.com/71822090/128061555-ce99d424-cdc4-46c7-9db9-886d183d9a44.png)

IOU AND NON–MAX SUPPRESSION 

![image](https://user-images.githubusercontent.com/71822090/128061650-6dfc35e4-2b68-4096-b25a-14728d11751c.png)

![image](https://user-images.githubusercontent.com/71822090/128061694-44744c0e-6055-4cfb-885a-1a0c19b3027d.png)

![image](https://user-images.githubusercontent.com/71822090/128061734-1ee0499b-550f-4127-a0bc-977026e0e586.png)

## Distance Calculation

![image](https://user-images.githubusercontent.com/71822090/128061821-e0f15468-59be-4f71-be23-bb6b5df3502b.png)

## FURTHER IMPROVEMENT

Distance calculated by the algorithm depends on how the camera is positioned.

Considering top-down view of the pedestrains.  

Accuracy of  the algorithm is less.




