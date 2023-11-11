# Vehicle Detection using YOLOv8 on Google Colab

## Overview

This repository contains the implementation of a vehicle detection model using YOLOv8. YOLOv8 (You Only Look Once version 8) is a state-of-the-art object detection algorithm that can detect and classify objects in real-time.

## Google Colab Setup

To run this vehicle detection model in Google Colab, follow these steps:

1. Open the notebook `VehicleDetectionYOLOv8.ipynb` in Google Colab.
2. Ensure that the Colab notebook is set to use a GPU runtime. Go to "Runtime" -> "Change runtime type" and select "GPU" in the Hardware Accelerator dropdown.
3. Execute the cells in the notebook sequentially.

## Usage

### Inference

Run the vehicle detection model on an image or a video by executing the cells in the "Inference" section of the Colab notebook.

By default, the notebook uses the pre-trained YOLOv8 weights for vehicle detection.

### Training (Optional)

If you want to train the model on your custom dataset, follow the training section in the Colab notebook. Make sure to upload your dataset to your Google Drive and update the paths accordingly.

## Customization

### Configuration

Modify the `yolov8-custom.cfg` file in your Google Drive to adjust the model architecture, training parameters, and other settings according to your requirements. Make sure to update the Colab notebook accordingly.

### Post-processing

Tune the post-processing parameters in the "Inference" section of the Colab notebook for better results.

## Acknowledgments

This implementation is based on the YOLOv8 repository by Ultralytics. Check their repository for the latest updates and additional features: [https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5)
