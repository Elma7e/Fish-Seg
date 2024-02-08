# Image Segmentation with YOLOv8 + Dataset created in Roboflow

## Overview

[GitHub](https://github.com/Elma7e/Fish-Seg)


This project demonstrates how to perform image segmentation using YOLOv8 for  image segmentation and creating your own Roboflow dataset. YOLOv8 is the latest version (as of February 2024) of the acclaimed real-time object detection and image segmentation model. YOLOv8 is built on cutting-edge advancements in deep learning and computer vision, offering unparalleled performance in terms of speed and accuracy. This project was made in Google Colab and using the T4 GPU.
*Note: It will be much much faster if you run this by changing the Runtime -> Hardware accelerator: T4 GPU*


## Technologies Used
- Python
- OpenCV
- Ultralytics YOLOv8
- Numpy
- Matplotlib

![](./train/images/yt-Oy0ASziVJcA-0048_jpg.rf.8d96cc00f1b7ccbb04734a4e1da6bbe1)

## YOLOv8 + Roboflow dataset Overview


![](./video.avi)

**YOLOv8, short for You Only Look Once with Neural Architecture Search,** is a cutting-edge object detection model optimized for both accuracy and low-latency inference. Developed by Deci, YOLOv8 employs state-of-the-art techniques like Quantization Aware Blocks and selective quantization for superior performance. It sets a new standard for state-of-the-art (SOTA) object detection, making it an ideal choice for a wide range of applications including autonomous vehicles, robotics, and video analytics.

### Unique Features of YOLOv8
- Utilizes Quantization Aware Blocks for efficient inference without sacrificing accuracy.
- Incorporates AutoNAC technology for optimal architecture design, balancing accuracy, speed, and complexity.
- Supports INT8 quantization for unprecedented runtime performance.
- Employs a hybrid quantization method that selectively quantizes certain parts of the model, reducing information loss and balancing latency and accuracy.
- Pre-training regimen includes automatically labeled data, self-distillation, and large datasets.
- Available under an open-source license with pre-trained weights for research use on SuperGradients, Deci’s PyTorch-based computer vision training library.

### YOLOv8 architecture 
- Quantization-aware blocks: These blocks are designed to be quantized efficiently, which can improve performance and reduce latency.
- Selective quantization: This technique allows for quantization of specific layers of the model without sacrificing accuracy.
- Attention mechanism: This mechanism allows the model to focus on the most important parts of an image, which can improve accuracy and reduce inference time.

### Training Details
YOLOv8 undergoes a multi-phase training process that includes pre-training on Object365, COCO Pseudo-Labeled data, Knowledge Distillation (KD), and Distribution Focal Loss (DFL). The model is meticulously trained on Objects365, a comprehensive dataset with 2 million images and 365 categories, for 30-100 epochs, ensuring robust performance.

## Roboflow dataset Overview

![](./video.avi)

