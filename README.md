# YOLOv5 Smart Parking System
## Overview
This project implements a Smart Parking System using YOLOv5, designed to detect empty parking spaces in a parking lot. By training a YOLOv5 model, the system accurately identifies available parking spots, making it easier to manage parking efficiently.

## Features
- Object Detection: Detects available parking spaces in real-time using YOLOv5.
- Custom Trained Model: Trained on a dataset specifically designed for parking spaces.
- Google Colab Recommended: Due to computational limitations, this project is optimized to run on Google Colab for a smoother experience.

## Getting Started
Prerequisites
A Google Drive account to store the project files and mount on Colab.
YOLOv5 (download the latest version from the official repository).

## Setup Instructions
- Create Folder on Google Drive: First, create a folder named SmartParking in your Google Drive.


Upload the following to the SmartParking folder:
- The yolov5 directory.
- CarP (dataset).
- train_data (dataset for training).

## Custom Configuration:
If there is an update in the YOLOv5 version, download the latest version from the official YOLOv5 GitHub.
Copy the custom configuration file custom1.yaml (located in the Changed File Folder) to the yolov5 > data directory.

## Run on Google Colab:
Open Copy_of_YOLOv5_Tutorial.ipynb in Google Colab.
Run the first step to mount your Google Drive.
Ensure that the directory points to the yolov5 folder within SmartParking on your Google Drive.
If your folder has a different name, update the directory paths accordingly.


Follow the Steps in the Notebook:
The notebook contains detailed instructions and steps to follow. If everything is set up correctly, it should run smoothly and detect parking spaces effectively.
Recommendations


Training Environment: It’s highly recommended to run the model training on Google Colab since it provides more computational power compared to a local machine, especially for training YOLOv5 models.
Directory Structure: Make sure your directory structure is consistent with the instructions. If there are any deviations, update the paths accordingly in the notebook.
