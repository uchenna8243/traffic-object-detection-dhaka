# Traffic Monitoring with Object Detection (Dhaka)

Real-time object detection applied to traffic video from Dhaka, Bangladesh, then extended through custom training so the model detects local vehicle types.

## Problem
Dhaka's roads carry vehicles that general detection models were never trained on, such as rickshaws and CNG auto-rickshaws. Accurate detection of these vehicles is the first step towards traffic counting and congestion analysis.

## Process
1. **Frame extraction:** split the traffic video into individual frames for analysis.
2. **Pre-trained detection:** ran a pre-trained object-detection model on the frames and drew bounding boxes with class labels and confidence scores.
3. **Gap analysis:** found which local vehicle types the pre-trained model missed or mislabelled.
4. **Data preparation:** converted the annotated Dhaka dataset into the label format the detection model expects, and split it into training and validation sets.
5. **Custom training:** trained the model on the local data so it learned the new vehicle classes.
6. **Evaluation:** compared detections before and after custom training on validation images and video.

## Tools
Python · PyTorch · Ultralytics YOLO · OpenCV · pandas · Jupyter

## Skills shown
Object detection · Bounding boxes · Annotation formats · Custom model training · Video processing

## Repository status
The project notebooks and scripts are being prepared for upload and will be added here shortly.

## Programme
Completed as part of the **WorldQuant University Applied AI Lab: Deep Learning for Computer Vision** (Jul 2025).

## Author
**Uchenna Francis Onyeka** · MSc FinTech with Business Analytics, University of Westminster
[LinkedIn](https://www.linkedin.com/in/uchenna-onyeka) · [GitHub](https://github.com/uchenna8243)
