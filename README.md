# Ambulance Detection System
This repository contains code and resources for a cloud-based ambulance detection system using YOLOv8.

# Overview
The project aims to minimize ambulance response time to emergency calls by detecting ambulance vehicles and synchronizing them with traffic cameras and signaling systems. The system utilizes machine learning techniques, specifically YOLOv8, for real-time ambulance detection.

# Key Features
YOLOv8 Model: The core of the system is the YOLOv8 model, trained to detect ambulance vehicles in real-time.
Dataset: A dataset comprising 3000 images of ambulance vehicles from 10 different countries is included for training and evaluation purposes.
Layered Architecture: The system architecture consists of multiple layers, including the data acquisition layer (DAL), ambulance detection layer (ADL), monitoring layer (ML), and cloud layer (CL), to support cloud-based ambulance detection.


## Models

| Country          | Model Type        | Accuracy - Pre-trained | Accuracy - Non-pre-trained | Models |
| ---------------- | ----------------- | ---------------------- | -------------------------- | ---- |
| Germany          | Pre-trained       | 0.985                  | -                          | [Germany_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Germany/Germany_Pre-trained.pt) |
| Germany          | Custom            | -                      | 0.956                      | [Germany_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Germany/Germany_Custom.pt) |
| Italy            | Pre-trained       | 0.945                  | -                          | [Italy_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Italy/Italy_Pre-trained.pt) |
| Italy            | Custom            | -                      | 0.903                      | [Italy_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Italy/Italy_Custom.pt) |
| Japan            | Pre-trained       | 0.995                  | -                          | [Japan_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Japan/Japan_Pre-trained.pt) |
| Japan            | Custom            | -                      | 0.938                      | [Japan_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Japan/Japan_Custom.pt) |
| Norway           | Pre-trained       | 0.942                  | -                          | [Norway_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Norway/Norway_Pre-trained.pt) |
| Norway           | Custom            | -                      | 0.895                      | [Norway_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Norway/Norway_Custom.pt) |
| Russia           | Pre-trained       | 0.993                  | -                          | [Russia_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Russia/Russia_Pre-trained.pt) |
| Russia           | Custom            | -                      | 0.957                      | [Russia_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Russia/Russia_Custom.pt) |
| Saudi Arabia     | Pre-trained       | 0.991                  | -                          | [Saudi-Arabia_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Saudi%20Arabia/Saudi-Arabia_Pre-trained.pt) |
| Saudi Arabia     | Custom            | -                      | 0.98                       | [Saudi-Arabia_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Saudi%20Arabia/Saudi-Arabia_Custom.pt) |
| Spain            | Pre-trained       | 0.969                  | -                          | [Spain_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Spain/Spain_Pre-trained.pt) |
| Spain            | Custom            | -                      | 0.958                      | [Spain_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Spain/Spain_Custom.pt) |
| Sweden           | Pre-trained       | 0.994                  | -                          | [Sweden_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Sweden/Sweden_Pre-trained.pt) |
| Sweden           | Custom            | -                      | 0.976                      | [Sweden_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Sweden/Sweden_Custom.pt) |
| Turkey           | Pre-trained       | 0.988                  | -                          | [Turkey_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Turkey/Turkey_Pre-trained.pt) |
| Turkey           | Custom            | -                      | 0.944                      | [Turkey_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Turkey/Turkey_Custom.pt) |
| United Kingdom   | Pre-trained       | 0.987                  | -                          | [United-Kingdom_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/United%20Kingdom/United-Kingdom_Pre-trained.pt) |
| United Kingdom   | Custom            | -                      | 0.972                      | [United-Kingdom_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/United%20Kingdom/United-Kingdom_Custom.pt) |
| Universal - Yolov7 | Pre-trained     | 0.953                  | -                           | [YOLOv7_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Universal/YOLOv7/YOLOv7_Pre-trained.pt) |
| Universal - Yolov7 | Custom           | -                      | 0.953                      | [YOLOv7_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Universal/YOLOv7/YOLOv7_Custom.pt) |
| Universal - Yolov5 | Pre-trained     | 0.979                  | 0.979                      | [YOLOv5_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Universal/YOLOv5/YOLOv5_Pre-trained.pt) |
| Universal - Yolov5 | Custom           | -                      | 0.979                      | [YOLOv5_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Universal/YOLOv5/YOLOv5_Custom.pt) |
| Universal - Yolov8 | Pre-trained     | 0.982                  | 0.982                      | [YOLOv8_Pre-trained.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Universal/YOLOv8/YOLOv8_Pre-trained.pt) |
| Universal - Yolov8 | Custom           | -                      | 0.982                      | [YOLOv8_Custom.pt](https://github.com/BaseelAlharbi/Ambulance-Detection-System/blob/main/Models/Universal/YOLOv8/YOLOv8_Custom.pt) |








# Usage
To use the system, follow these steps:

Clone the Repository: Clone this repository to your local machine.
Dataset: Access the dataset provided in the dataset directory for training and evaluation.
Model: Use the YOLOv8 model provided in the model directory for ambulance detection.
Run the System: Deploy the system and integrate it with traffic cameras and signaling systems for real-time ambulance detection.



