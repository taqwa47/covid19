# Real-Time COVID-19 Test Kit Object Detection using YOLOv5

## 1. Project Overview & Objective
This project implements an automated computer vision system designed to detect and localize COVID-19 rapid test strips within images. Using deep learning and transfer learning, the system automates inspection with high precision and real-time efficiency.

## 2. System Pipeline & Tools
* **Language:** Python
* **Framework:** PyTorch & YOLOv5 (Small Architecture)
* **Environment:** Google Colab (Tesla T4 GPU)
* **Annotation Platform:** Roboflow

## 3. Dataset & Hyperparameters
* **Dataset Size:** 339 custom-annotated images of COVID-19 lateral-flow tests.
* **Input Resolution:** 416x416 pixels.
* **Batch Size:** 16
* **Training Epochs:** 25
* **Optimizer:** SGD (Stochastic Gradient Descent)

## 4. Empirical Results
* **Convergence:** The network demonstrated seamless training convergence, showing a sharp drop in both bounding box and objectness losses over the 25 epochs.
* **Inference Speed:** Real-time validation achieved an ultra-fast evaluation time of **7.1ms per image**, validating its potential for real-time edge deployments.
