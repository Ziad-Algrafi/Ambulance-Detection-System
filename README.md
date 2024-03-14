# Ambulance Detection System
This repository contains code and resources for a cloud-based ambulance detection system using YOLOv8.

# Overview
The project aims to minimize ambulance response time to emergency calls by detecting ambulance vehicles and synchronizing them with traffic cameras and signaling systems. The system utilizes machine learning techniques, specifically YOLOv8, for real-time ambulance detection.

# Key Features
YOLOv8 Model: The core of the system is the YOLOv8 model, trained to detect ambulance vehicles in real-time.
Dataset: A dataset comprising 3000 images of ambulance vehicles from 10 different countries is included for training and evaluation purposes.
Layered Architecture: The system architecture consists of multiple layers, including the data acquisition layer (DAL), ambulance detection layer (ADL), monitoring layer (ML), and cloud layer (CL), to support cloud-based ambulance detection.


## Data 

| Country              | Data Type | Total Images | Total Labels 
|----------------------|-----------|--------------|--------------|
| Ambulance - Germany  | train     | 200          | 220          | 
| Ambulance - Germany  | val       | 100          | 112          | 
| Ambulance - Italy    | train     | 200          | 203          | 
| Ambulance - Italy    | val       | 100          | 111          | 
| Ambulance - Japan    | train     | 200          | 211          | 
| Ambulance - Japan    | val       | 100          | 113          | 
| Ambulance - Norway   | train     | 200          | 219          | 
| Ambulance - Norway   | val       | 100          | 108          | 
| Ambulance - Russia   | train     | 200          | 253          | 
| Ambulance - Russia   | val       | 100          | 116          | 
| Ambulance - Saudi Arabia | train  | 200          | 215         | 
| Ambulance - Saudi Arabia | val    | 100          | 104         | 
| Ambulance - Spain    | train     | 200          | 233          | 
| Ambulance - Spain    | val       | 100          | 114          | 
| Ambulance - Sweden   | train     | 200          | 216          | 
| Ambulance - Sweden   | val       | 100          | 112          | 
| Ambulance - Turkey   | train     | 200          | 250          | 
| Ambulance - Turkey   | val       | 100          | 111          | 
| Ambulance - United Kingdom | train | 200        | 286          | 
| Ambulance - United Kingdom | val   | 100        | 131          | 



## Models

| Country          | Model Type        | Accuracy -             | 
| ---------------- | ----------------- | ---------------------- | 
| Germany          | Pre-trained       | 0.985                  |
| Germany          | Custom            | 0.956                  |
| Italy            | Pre-trained       | 0.945                  |
| Italy            | Custom            | 0.903                  |
| Japan            | Pre-trained       | 0.995                  |
| Japan            | Custom            | 0.938                  |
| Norway           | Pre-trained       | 0.942                  |
| Norway           | Custom            | 0.895                  |
| Russia           | Pre-trained       | 0.993                  |
| Russia           | Custom            | 0.957                  |
| Saudi Arabia     | Pre-trained       | 0.991                  |
| Saudi Arabia     | Custom            |  0.98                  |
| Spain            | Pre-trained       | 0.969                  |
| Spain            | Custom            | 0.958                  |
| Sweden           | Pre-trained       | 0.994                  |
| Sweden           | Custom            | 0.976                  |
| Turkey           | Pre-trained       | 0.988                  |
| Turkey           | Custom            | 0.944                  |
| United Kingdom   | Pre-trained       | 0.987                  |
| United Kingdom   | Custom            | 0.972                  |
| Universal - Yolov7 | Pre-trained     | 0.953                  |
| Universal - Yolov7 | Custom          | 0.953                  |
| Universal - Yolov5 | Pre-trained     | 0.979                  |
| Universal - Yolov5 | Custom          | 0.979                  |
| Universal - Yolov8 | Pre-trained     | 0.982                  |
| Universal - Yolov8 | Custom          | 0.982                  |



# contact

Access to Data and Models: For access to the dataset and the YOLOv8 model provided in the dataset and model directories respectively,
please contact us at: ziadalgurafi@gmail.com, tnoor@taibahu.edu.sa, anoor@taibahu.edu.sa.

Deploy the system and integrate it with traffic cameras and signaling systems for real-time ambulance detection. For any assistance regarding the system, please contact us at basil.khalid.alharbi@gmail.com.
