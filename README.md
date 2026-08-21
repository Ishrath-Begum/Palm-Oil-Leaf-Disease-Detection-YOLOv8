# Palm Oil Leaf Disease Detection using YOLOv8

## Overview

This project focuses on detecting diseases in palm oil leaves using computer vision and the YOLOv8 object detection model. The project includes dataset preparation and annotation using Roboflow, YOLOv8 model training, and deployment of the trained model through a Streamlit application.

## Problem Statement

Palm oil leaf diseases can affect plant health and crop productivity. Manual identification of diseases from leaf images can be time-consuming. This project aims to develop an automated computer vision solution that detects disease-affected regions in palm oil leaf images.

## Project Workflow

The project follows the workflow below:

**Image Dataset → Roboflow Annotation → Data Preparation → YOLOv8 Training → Model Evaluation → Disease Detection → Streamlit Deployment**

## Dataset

The image dataset was imported and prepared using Roboflow.

Roboflow was used for:

* Organizing the image dataset
* Annotating disease-affected regions
* Preparing the dataset for YOLOv8
* Applying preprocessing and augmentation where required

> The dataset itself is not included in this repository.

## Data Annotation

Images were annotated in Roboflow by identifying and labeling disease-affected regions of palm oil leaves.

The annotated dataset was then prepared in a YOLOv8-compatible format for model training.

## Model

**YOLOv8** was used as the object detection model for identifying disease-affected regions in palm oil leaf images.

The model was trained using the prepared and annotated dataset and evaluated using the available detection metrics.

## Technologies Used

* Python
* YOLOv8
* Roboflow
* OpenCV
* Streamlit
* Google Colab

## Project Implementation

The implementation includes:

1. Importing and preparing the image dataset.
2. Annotating images using Roboflow.
3. Preparing the annotated dataset for YOLOv8.
4. Training the YOLOv8 object detection model.
5. Evaluating model performance.
6. Performing disease detection on palm oil leaf images.
7. Deploying the detection application using Streamlit.

## Deployment

A Streamlit application was developed to provide an interactive interface for uploading palm oil leaf images and obtaining disease detection results.

## Repository Structure

```text
Palm-Oil-Leaf-Disease-Detection-YOLOv8/
│
├── README.md
└── Palm_Oil_Leaf_Disease_Detection.ipynb
```

## How to Run

1. Open the Jupyter/Google Colab notebook.
2. Install the required Python packages.
3. Configure your Roboflow API key securely if dataset download is required.
4. Run the notebook cells to prepare the dataset and perform detection.

**Note:** The actual Roboflow API key is not included in this repository for security reasons.

## Future Improvements

* Improve detection accuracy with a larger and more diverse dataset.
* Experiment with different YOLOv8 model variants.
* Further optimize the Streamlit application for real-time inference.
* Add additional palm oil leaf disease categories as more annotated data becomes available.
