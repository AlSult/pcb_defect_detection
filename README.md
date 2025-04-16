# pcb_defect_detection
This project focuses on detecting and classifying defects in printed circuit boards (PCBs) using computer vision and deep learning techniques. Leveraging a real-world dataset from Kaggle, it aims to build an end-to-end pipeline—from data exploration to model training, evaluation, and deployment via a user-friendly app.

# Table of Contents
1. [Chapter 1 - Project Overview](#ch1)
1. [Chapter 2 - Data Science Steps](#ch2)
1. [Chapter 3 - Step 1: Problem Definition](#ch3)
1. [Chapter 4 - Step 2: Data Gathering](#ch4)
1. [Chapter 5 - Step 3: EDA and Data Preparation](#ch5)
1. [Chapter 6 - Step 4: Build the Models](#ch6)
1. [Chapter 7 - Step 5: Model Comparison](#ch7)
1. [Chapter 7 - Step 6: Summary](#ch8)


1. [References](#ch9)


<a id="ch1"></a>
# Project Overview
Printed Circuit Boards (PCBs) are critical components used in virtually all electronic devices. Even minor defects in PCBs—such as open circuits, shorts, or missing holes—can lead to complete device failure, costly recalls, or safety hazards.
This project aims to identify and categorize six common types of PCB defects. It starts with classification using CNNs and explores object detection for localization. Deployment is handled through a simple Streamlit app.
<a id="ch2"></a>
# Data Science Steps
1. **Problem Definition:** Manual inspection of PCBs is time-consuming, error-prone, and expensive, especially in high-throughput manufacturing environments.
2. **Data Gathering:** I used the PCB defect dataset, which I got access to through the [Kaggle: PCB Defects](https://www.kaggle.com/datasets/akhatova/pcb-defects/data).
3. **Data Preparation:**
4. **EDA (Exploratory Data Analysis):**
5. **Data Modelling:**
6. **Validate Model:**
7. **Optimize Model:**
<a id="ch3"></a>
# Step 1: Problem Definition
Manual inspection of PCBs is time-consuming, error-prone, and expensive, especially in high-throughput manufacturing environments. This project aims to automate the inspection process using deep learning techniques.
The goal is to develop a computer vision model that can accurately detect and classify defects in PCBs from image data, with potential for real-time deployment on manufacturing lines.

Goals:
1. Identify whether a PCB image is defective or not
2. Classify the type of defect (6 classes)
3. Optionally localize defects using object detection techniques
4. Provide a user-friendly interface for easy inference and testing

Defect Categories:
1. Missing Hole – A required hole is not present
2. Mouse Bite – Jagged, semi-circular holes on edges
3. Open Circuit – Break in the intended connection
4. Short – Unintended connection between traces
5. Spur – Thin, unintended copper trace
6. Spurious Copper – Extra unwanted copper traces

**Project Summary from Kaggle:**
This is a public synthetic PCB dataset containing 1386 images with 6 kinds of defetcs (missing hole, mouse bite, open circuit, short, spur, spurious copper) for the use of detection, classification and registration tasks.

<a id="ch4"></a>
# Step 2: Data Gathering
The dataset for this project can be found on the Kaggle website: [Kaggle: PCB Defects](https://www.kaggle.com/datasets/akhatova/pcb-defects/data).
**Input data:**

<a id="ch5"></a>
# Step 3: EDA and Data Preperation

<a id="ch6"></a>
# Step 4: Build the Models

<a id="ch7"></a>
# Step 5: Model Comparison 

<a id="ch8"></a>
# Step 6: Summary

<a id="ch90"></a>
# References
Thank you for the following resources and developers for the inspiration:
