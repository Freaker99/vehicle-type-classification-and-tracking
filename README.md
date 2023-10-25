# Vehicle Type Classification And Tracking

**Traffic Object Detection and Classification Project**

In case the **car_detection.ipynb** file doesn't open correctly, please visit the project using the following link:
<br>[Link to the project on Google Colab](https://colab.research.google.com/drive/1qT0ljzGAMB0inCouexfN8NKoE5T3CTJ_?usp=sharing)

## Project Description

### Introduction

This project presents the concept and implementation of a tool for detecting and classifying objects in traffic. The primary goal was to develop a tool for detecting and classifying objects in traffic, which could be used to assess the level of road noise and its impact on the environment.

### Choice of Detection Algorithm

The first step involved reviewing available object detection algorithms. After analyzing various solutions, the **YOLO (You Only Look Once)** algorithm was chosen for implementation. YOLO represents an innovative approach that enables real-time object detection and classification, making it an ideal tool for traffic-related applications.

### Dataset and Data Modifications

The project utilized the **BDD100K image database**. To prepare the data for the YOLO model, certain modifications were made. Object labels were transformed into a format accepted by the YOLO model, including information about object locations and categories. Furthermore, image sizes were adjusted to meet the model's requirements, and segments containing traffic motion were extracted.

## Model Training

### Training

The core of the project consisted of training and experiments with various model variants. Before commencing the training, input data was modified to match the format accepted by the YOLO model. Subsequently, the model underwent training and was subjected to tests on both the test dataset and real-world recordings. These recordings captured moving objects from the perspective of an overpass. The model's effectiveness in object detection, classification into different categories, and tracking their movements was evaluated.

### Project Results

The project yielded promising results. The trained YOLOv5s model achieved an F1-score of 0.449 on the test dataset, confirming its capability for effective object detection and classification. The F1-score before training was 0.336, so the classification efficiency was improved. In addition, tests conducted on real traffic recordings validated the model's practical effectiveness.

## Screenshots

![Alt text](example_clear.png?raw=true "Vehicle Tracking")
![Alt text](example.png?raw=true "Vehicle Tracking")

Here are a few screenshots showcasing the results of my work.

## Conclusion

This project represents just the beginning of its potential applications. Ongoing work can focus on refining the models and expanding their applications in traffic monitoring and other domains.

I encourage you to explore the project and its results.

Thank you for your interest in my project!
