# Football-Analysis 

![YOLOv5m](https://img.shields.io/badge/YOLOv5m-FF6F00?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-FF0000?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-ADD8E6?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-008000?style=for-the-badge)
![Ultralytics](https://img.shields.io/badge/Ultralytics-800080?style=for-the-badge)
![Supervision](https://img.shields.io/badge/Supervision-FFD700?style=for-the-badge)


## Introduction
The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. We will also train the model to improve its performance. Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered. This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.

![Output-Image](https://github.com/tejred213/Football-Analysis/assets/86062873/96b9683f-f8a5-4ab4-be28-ef668ee6a0d0)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://colab.research.google.com/drive/1lOr0iSD7k6qamk1Qom-af8xiup_2lrDZ?usp=sharing)

Disclaimer - The version used to train the model is v5m. 

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas

## Dataset Link
- [Kaggle Dataset](https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data?select=clips)
- [RoboFlow Football Dataset](https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc/dataset/1)
