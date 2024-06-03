# KEKE_NAPEP_DETECTION
## Overview

This project addresses the challenge of detecting tricycles, locally known as keke_napep, using YOLOv8. Tricycles serve as the primary mode of public transportation in Nigeria, and their accurate detection is necessary for various applications, including traffic management. This project utilizes a dataset of 84 annotated images to train a custom YOLOv8 model specifically tailored for detecting keke_napep.
# Dataset
The dataset comprises 84 images sourced from various locations in kano state, capturing diverse scenarios of tricycles in different environments. The images were annotated using a user-friendly annotated tool CVAT.ai, to label the keke_napep instances in each image accurately.
# Model Training
YOLOv8n, a lightweight version of YOLOv8, was chosen for its ability to deliver efficient and accurate object detection on devices with limited computational power.
The model was trained for 100 epochs, achieving satisfactory results on the dataset.
# Results
After training for 100 epochs, the custom YOLOv8 model demonstrated promising results in accurately detecting keke_napep instances in various environments in Kano state. 
# Future Improvements
### 1. Diversifying the Dataset
To enhance the model's robustness and generalization capabilities, future efforts should focus on acquiring a more diverse dataset. This includes collecting images from various geographical locations across Nigeria, encompassing urban, rural, and suburban areas. Additionally, incorporating images captured under different weather conditions will help the model adapt to various environmental factors. Furthermore, expanding the dataset to include different varieties and colors of *keke_napep* commonly found across Nigeria will enable the model to recognize a wider range of tricycle types accurately.
### 2. Development of Tracking and Speed Detection Models
Beyond object detection, there is potential to extend the capabilities of the model to include tracking and speed detection functionalities. Implementing object tracking algorithms, such as Kalman filters or deep learning-based trackers, would enable the model to track the movement of *keke_napep* instances over time. Additionally, integrating speed estimation algorithms based on the detected object's motion could facilitate the development of a comprehensive system for monitoring *keke_napep* speeds on roads and highways.
### 3. Real-World Applications:
Collaborate with stakeholders (e.g. government, transportation companies, tax collectors) to integrate the model into real-world applications (e.g. traffic monitoring, surveillance). Also, Explore using the model for autonomous vehicles or robotics applications.
## Citation

The dataset used in this project was provided by [EJAZTECH.AI](ejaztech.ai@gmail.com), a company dedicated to gathering local datasets for AI applications. We acknowledge their invaluable contribution to the development of this model by providing access to diverse and localized data, which played a crucial role in training and validating the KEKE_NAPEP_DETECTION model. We express our gratitude to EJAZTECH.AI for their commitment to advancing AI research and applications in Nigeria and beyond.

