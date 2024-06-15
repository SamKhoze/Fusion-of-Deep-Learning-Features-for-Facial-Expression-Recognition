# Fusion-of-Deep-Learning-Features-and-Histogram-of-Oriented-Gradients-for-Facial-Expression-Recognit

## Read the research paper [Here](https://github.com/SamKhoze/Fusion-of-Deep-Learning-Features-for-Facial-Expression-Recognition/blob/main/Fusion%20of%20%20Deep%20Learning%20Features%20and%20Histogram%20of%20Oriented%20Gradients%20for%20Facial%20Expression%20Recognition.pdf)

Download Data set and Model: https://drive.google.com/drive/folders/148cul8A3IgwShU6zDkOOD8qNbOk_RQND?usp=sharing

# Fusion of Deep Learning Features and Histogram of Oriented Gradients for Facial Expression Recognition

## Table of Contents
- [Introduction](#introduction)
- [Challenges of Face Detection Techniques](#challenges-of-face-detection-techniques)
- [Research Objectives](#research-objectives)
- [Research Methodology](#research-methodology)
- [Dataset](#dataset)
- [Ethical Considerations](#ethical-considerations)
- [Literature Review](#literature-review)
- [Methodologies and Research Design](#methodologies-and-research-design)
- [Results, Analysis & Evaluation](#results-analysis--evaluation)
- [Discussion](#discussion)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [References](#references)

## Introduction
Facial changes in reaction to an individual's internal emotional states, goals, or social communications are referred to as facial expressions. Behavioral scientists have been analyzing facial expressions for a long time. Based on facial video processing, this innovative research detects the face and extracts features like the mouth, left eye, right eye, and nose. These features and Histogram of Oriented Gradients (HOG) features are merged to create a new dataset called HOGFER. This research proposes a model that combines a Convolutional Neural Network (CNN) and HOG features. Facial Expression Recognition (FER) analysis goes through face detection, facial expression detection, and classification of an emotional state.

## Challenges of Face Detection Techniques
### Occlusion
Occlusion of the face is considered one of the most intractable problems because we need to predict the location or size of the occluded part in a face image before it happens.

### Lighting
Illumination is a critical factor in the design of face recognition applications.

### Pose
The varying pose is another challenge affecting the face recognition process.

### Accessories/Makeup/Facial Hair
Accessories, facial hair, or modifications might also affect the detection system's performance.

### Scale of Face
Scale poses a vexing problem in unconstrained environments; faces captured at large distances are significantly harder to recognize than faces captured at close ranges.

### Tiny Face Detection
An accurate and reliable algorithm to detect tiny faces in images, videos, and other real-life situations has always been the focus of research.

## Research Objectives
This research hypothesizes that combining traditional features with deep learning techniques can improve performance. The specific objectives are:
- Creating a robust and efficient model to detect base emotions from video streams in a constraint-free environment.
- Improving the emotion recognition performance in terms of time and precision.
- Merging handcrafted features with deep learning networks to boost performance.

## Research Methodology
The study addresses research questions about the effectiveness of GAN as a pre-processing step, the maintenance of facial expressions after rotation, and the accuracy improvement by merging certain efficient handcrafted features with deep learning.

## Dataset
The proposed study uses FER2013, an open-source dataset, for development purposes. The dataset consists of 48x48 pixel grayscale images of faces.

## Ethical Considerations
This research raises potential ethical implications. The proposed method decided to use data already in the public domain. No private users' data will be collected and stored by third parties' servers, and everything will be run on the machines owned by the end users.

## Literature Review
Several technological advancements have been made in face detection, involving computer vision and machine learning-based techniques. The study categorizes and evaluates these methods.

## Methodologies and Research Design
The process starts with live streaming input video converted to frames. A few selective frames are fed into the developed model, moving through phases of face detection and face rotation to get the frontal view, then feeding into a simple CNN model and feeding to a fusion-based CNN with a handcrafted feature model.

## Results, Analysis & Evaluation
This chapter discusses the results produced by the research at different stages of its lifecycle, starting from video input to the identification of facial expressions through the proposed research.

## Discussion
This chapter evaluates the suggested model's parameters and compares the proposed strategy to other research.

## Conclusion
The proposed model performs well for most classes, and the model's performance can be improved with denoising and sharpening filters. The evaluation shows room for improving performance.

## Future Work
Future research could focus on using models like Faster R-CNN, HOG + Linear SVM, and YOLO. Improvements can also be made in data augmentation and performance metrics.

## References
The references section includes all the citations and research papers used throughout the study.

[Complete Reference List Available in the PDF Document]
