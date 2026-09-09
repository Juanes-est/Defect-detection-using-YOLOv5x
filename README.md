# 🔍 Defect Detection using YOLOv5x

This project implements a computer vision system for the detection and localization of defects using the **YOLOv5x object detection model**.

The system uses **bounding boxes** to identify and locate defective areas in steel plate images and can be adapted for both static images and real-time video detection.

## 🛠️ Requirements

The project requires:

- **Python 3.8.10**
- YOLOv5x
- PyTorch
- OpenCV
- NumPy

> ⚠️ It is recommended to use **Python 3.8.10** to ensure compatibility with the project dependencies.

## 🚀 Project Workflow

The project follows the following workflow:

1. 📷 Image acquisition
2. 🏷️ Manual image annotation
3. 🧹 Dataset preparation
4. 🧠 Model pre-training
5. 🎯 YOLOv5x training
6. 🔍 Defect detection

## 🏷️ Image Annotation

Before training the model, the images must be manually annotated by creating bounding boxes around the defects.

For manual annotation, you can use:

👉 [MakeSense.ai](https://www.makesense.ai/)

MakeSense.ai is a web-based tool that allows you to manually annotate images and create bounding boxes for object detection datasets.

## 🧠 Model Pre-training

For model pre-training and custom YOLOv5 training, the following Google Colab notebook can be used:

👉 [YOLOv5 Custom Training - Google Colab](https://colab.research.google.com/github/roboflow-ai/yolov5-custom-training-tutorial/blob/main/yolov5-custom-training.ipynb?authuser=0&pli=1#scrollTo=1jS9_BxdBBHL)

This notebook provides a practical workflow for training a custom YOLOv5 model using a GPU-enabled Google Colab environment.

## 🎥 Detection

Once the model has been trained, it can be used for defect detection on:

- 📷 Static images
- 🎥 Video files
- 📹 Real-time webcam or camera streams

The model generates **bounding boxes** around detected defects, along with their corresponding class labels and confidence scores.
