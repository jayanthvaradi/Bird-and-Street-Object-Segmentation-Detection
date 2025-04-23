Bird and Street Object Segmentation & Detection
This project demonstrates the application of deep learning-based object detection and image segmentation models using PyTorch. Two primary tasks are addressed:

Task 1: Bird Segmentation from Natural Images
Objective:
To detect and segment birds from high-resolution images in outdoor settings using state-of-the-art segmentation models.

Models Used:

Mask R-CNN: Performs instance-level segmentation by predicting bounding boxes and masks for each detected bird.

DeepLabV3 (U-Net style): Generates semantic segmentation maps highlighting bird regions using dilated convolutions.

Key Highlights:

Utilized pretrained models from torchvision and segmentation-models-pytorch.

Preprocessing ensured compatibility with model input requirements.

Visual results included overlayed masks and bounding boxes for comparison.

Task 2: Object Detection in Street Scene
Objective:
To detect vehicles and pedestrians in a busy urban street image using real-time and high-accuracy object detection models.

Models Used:

YOLOv5: Fast, single-stage detector ideal for real-time inference.

Faster R-CNN: Two-stage detector providing high accuracy, suitable for applications needing detailed detections.

Key Highlights:

Inference using Ultralytics YOLOv5 and torchvision.models Faster R-CNN.

Confidence threshold set to 0.5 for visualizing bounding boxes.

Performance comparison based on speed and accuracy trade-offs.

Technologies & Libraries:
PyTorch

torchvision

segmentation-models-pytorch

Ultralytics YOLOv5

OpenCV, NumPy, Matplotlib, Pillow

Output Visualization :
The repository includes input images and model output comparisons showing detected/segmented regions.

