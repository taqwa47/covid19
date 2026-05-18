# Real-Time COVID-19 Test Kit Object Detection using YOLOv5

## 1. Project Overview & Objective
[cite_start]This project implements an automated computer vision system designed to detect and localize COVID-19 rapid test strips within images[cite: 4, 5]. [cite_start]Using deep learning and transfer learning, the system automates inspection with high precision and real-time efficiency[cite: 6, 7].

## 2. System Pipeline & Tools
* [cite_start]**Language:** Python [cite: 15]
* [cite_start]**Framework:** PyTorch & YOLOv5 (Small Architecture) [cite: 10, 16]
* [cite_start]**Environment:** Google Colab (Tesla T4 GPU) [cite: 19]
* [cite_start]**Annotation Platform:** Roboflow [cite: 18]

## 3. Dataset & Hyperparameters
* [cite_start]**Dataset Size:** 339 custom-annotated images of COVID-19 lateral-flow tests[cite: 21].
* **Input Resolution:** 416x416 pixels.
* **Batch Size:** 16
* **Training Epochs:** 25
* **Optimizer:** SGD (Stochastic Gradient Descent)
* [cite_start]**Data Augmentation:** Mosaic augmentation was utilized dynamically to boost model generalization[cite: 45].

## 4. Empirical Results & Performance Evaluation
* [cite_start]**Convergence:** The network demonstrated seamless training convergence, showing a sharp drop in both bounding box and objectness losses over the 25 epochs[cite: 44].
* [cite_start]**Inference Speed:** Real-time validation achieved an ultra-fast evaluation time of **7.1ms per image**, perfectly validating its potential for real-time edge deployments[cite: 13].
