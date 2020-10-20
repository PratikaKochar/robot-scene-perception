# robot-scene-perception
For bettere understanding, refer: Robot Soccer Perception.pptx

Problems tackled for robot's actions: <br>
1. Perception (further away balls and goalposts to be detected) <br>
2. Localization (robust line detection and state estimation) <br>


Problem Statement:
Implement visual perception system for soccer-related objects (https://arxiv.org/abs/1912.07405)
1. Object detection: Detecting ball, goalposts, and robots  
2. Classification:  Semantic Segmentation of field and lines  


Dataset:<br>
Two datasets:<br>

1. Object Detection for ball, goalposts, and robots <br>
Input RGB image, along with annotations containing landmark points for each relevant object<br>

2. Segmentation for background, field and lines <br>
Input RGB image, along with the ground truth (mask)<br>


Model:
Single model with 2 output heads: object detection and classification
