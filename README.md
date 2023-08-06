# Traffic-Sign-Detection

### Problem Statement 
The goal is to accurately identify different types of signs, such as speed limit signs, stop signs, yield signs, and so on, in real-time.
### Introduction
1.Traffic signs provide critical information to drivers, such as speed limits, warning of upcoming hazards, and guiding drivers through intersections and other complex traffic situations. Accurate detection and recognition of traffic signs can help prevent accidents and provide real-time guidance to drivers.
2.Traffic sign detection is the process of using computer vision and machine learning techniques to automatically detect and recognize traffic signs in images or video streams. 

### Methodology

1.Traffic sign recognition systems have a wide range of applications, from improving road safety to enabling self-driving cars to navigate complex roadways. 
2.To identify a model with better performance, implemented Inceptionv3, EfficientNet and finally YOLOv5 model to propose this methodology.
3.Inorder to improve the accuracy of YOLO v5, conditional GAN is used to generate synthetic dataset. The dataset generated is used to train YOLO v5 on real-time images.
