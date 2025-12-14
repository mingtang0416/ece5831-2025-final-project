# ece5831-2025-final-project: Real-time Distracted Driver Detection using Deep Learning

## Project Overview

This project implements a comprehensive deep learning pipeline for real-time multi-class driver distraction detection. The system leverages state-of-the-art computer vision techniques to analyze visual cues from in-vehicle cameras and classify driver behavior into ten distinct distraction categories. The primary goal is to enhance road safety by providing timely alerts for driver inattention.

The pipeline integrates YOLOv8 for robust object detection (identifying persons and distracting objects like cell phones and bottles), MediaPipe Face Mesh for extracting fine-grained facial features (Eye Aspect Ratio and 3D Head Pose angles), and a Fully Connected Neural Network (Multilayer Perceptron) for final classification.

## Project Structure & How to Run

This repository contains the Jupyter Notebooks and essential code developed for the project. The full workflow is divided into logical stages, as outlined in the `final-project.ipynb` notebook.

### **Repository Contents:**

*   `final-project.ipynb`: The main Jupyter Notebook demonstrating the later part of project , using MediaPipe to extract EAR and head direction feature and conbine the output with yolo. Train and test the MLP with this final feature table . 
*   `pseudo-labels.ipynb`: This Jupyter Notebook contain pseudo-label generation using yoloV8.
*   `visualization.ipynb`: Notebook for local visualization of YOLO and MediaPipe outputs.
*   `.gitignore`: Specifies files and directories to be ignored by Git (e.g., large datasets, generated outputs, virtual environments).
*   `extracted_features.csv`: CSV file containing the extracted features for all images.
*   `Real-time Distracted Driver Detection using Deep Learning Report.pdf`: The final project report (PDF format).
*   `Real-time Distracted Driver Detection using Deep Learning.pdf`: The final project presentation file


## **Project Deliverables & Links**

All final project deliverables are organized for easy access:

*   **Google Drive Folder:**
    *   (https://drive.google.com/drive/folders/1dtkeUzjHLgPRXbX5w-galG-6AV-mwovr?usp=drive_link)
    *   This folder contains:
        *   `dataset/`: Compressed and unziped original dataset.
        *   `presentation/`: The project presentation slides (PDF format).
        *   `report/`: The final project report (PDF format).


*   **Pre-recorded Presentation Video (YouTube):**
    *   (https://youtu.be/kffiZe1_rXQ)
    *   This video demonstrates the project's key aspects and findings.
    
*   **Pre-recorded Demo Video (YouTube):**
    *   (https://youtu.be/8LFzc2PeXQU)
    *   This video briefly intrduce the whole process of the project.


## **Contact**

Ming Tang
[mingtan@umich.edu]

---
