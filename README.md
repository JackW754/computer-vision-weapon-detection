Computer Vision Weapon Detection

This repository contains the code developed for my BSc Computer Science and Artificial Intelligence dissertation:
Enhancing Public Safety: A Computer Vision Approach to Offensive Weapon Detection in Images

Project Overview

This project investigates the use of machine learning and deep learning for detecting and classifying offensive weapons in images.
Three approaches were evaluated:
- K-Nearest Neighbour with HOG
- Faster R-CNN
- YOLOv8

The models were trained and tested using the SOHAS dataset, which contains images of knives, pistols and similar handheld non-weapon objects.
YOLOv8 produced the strongest overall results and was integrated into a Python desktop application.

Final Results
- Weapon detection accuracy: 97.2%
- Weapon classification accuracy: 100%

Desktop Application
The Python/PyQt5 application includes:
- User registration and login
- SQLite user database
- Single image and folder uploads
- Knife and pistol detection
- Bounding boxes and confidence scores
- Automatic saving of detected images
- Alert sound when a weapon is detected

Technologies
- Python
- SQL / SQLite
- PyTorch
- YOLOv8
- Faster R-CNN
- OpenCV
- PyQt5
- Scikit-learn
- bcrypt

Running the Application

Install the required packages:
pip install -r requirements.txt

Run the application:
python main.py

The trained model file best_model.pt must be available in the project directory.

Dataset
The project uses the SOHAS (Small Objects Handled Similarly) dataset.
The dataset is not included in this repository and remains subject to its original licence and usage conditions.
