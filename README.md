# Object Detection using YOLO on PASCAL VOC 2012

This project implements an object detection pipeline using a YOLO-based deep learning model trained on the PASCAL VOC 2012 dataset. The model is built using TensorFlow and Keras and is designed to run efficiently on Google Colab with Google Drive integration for dataset handling and model checkpointing.

## Features
- Uses PASCAL VOC 2012 dataset for multi-class object detection
- YOLO-style object detection architecture
- TensorFlow/Keras implementation
- XML annotation parsing for bounding boxes
- Custom learning rate scheduler
- ModelCheckpoint callback to save best weights
- Google Drive integration for persistent storage

## Dataset
The PASCAL VOC 2012 dataset contains annotated images with bounding boxes for multiple object categories. After extraction, the dataset follows the standard VOC directory structure including Annotations, JPEGImages, and ImageSets.

## How to Run
1. Upload `kaggle.json` to Google Drive
2. Mount Google Drive in Google Colab
3. Download and extract the PASCAL VOC 2012 dataset using Kaggle API
4. Run the notebook cells sequentially
5. Best model weights are automatically saved to Google Drive

## Technologies Used
- Python
- TensorFlow / Keras
- Google Colab
- Kaggle API
- PASCAL VOC 2012 Dataset

## Use Case
This project is suitable for learning and experimenting with object detection models and understanding YOLO-based architectures using real-world annotated datasets.
