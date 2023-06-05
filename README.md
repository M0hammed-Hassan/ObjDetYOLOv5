# YOLOv5 Object Detection with Custom and Pretrained Models

This repository contains an implementation of the YOLOv5 object detection algorithm using both custom and pretrained models.


# Custom Model 
To train the YOLOv5 model on a custom dataset, the following steps were taken:
- Importing the Dependencies: The necessary Python libraries were imported, including OS, PyTorch, OpenCV, labelme,... and etc.
- Collecting the Data: The images and annotations for the custom dataset were collected and organized into a directory structure.
- Data Annotation: The images were annotated with bounding boxes around the objects of interest using labelImg. The annotations were saved in a format that could be read by the YOLOv5 training script.
- Training Process: The YOLOv5 model was trained on the annotated dataset using the PyTorch framework.
- Real Time Object Detection: Once the model was trained, it was used to detect objects in real-time using a webcam. The detection results were visualized using OpenCV.


# Pretrained Model
Alternatively, a pretrained YOLOv5 model can be used for object detection. The following steps were taken:
- Importing the Dependencies: The necessary Python libraries were imported, including PyTorch, OpenCV,... and etc.
- Loading the Pretrained Model: A pretrained YOLOv5 model was downloaded and loaded into memory using PyTorch.
- Real Time Detection: The loaded model was used to detect objects in real-time using a webcam. The detection results were visualized using OpenCV.


# Results 
<img src = 'Images/results.png'>
<img src = 'Images/people.png'>
<img src = 'Images/cars.png'>
