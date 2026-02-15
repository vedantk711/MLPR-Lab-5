# Lab 5

## Course
Machine Learning and Pattern Recognition  
Spring Semester 2026

## Aim
The objective of this lab is to perform face detection on a given image, extract meaningful features from detected face regions, and cluster them using the K-Means algorithm to study similarity patterns.

## Methodology
- The given Jupyter Notebook was used without modifying restricted sections, following all instructions provided in comments.
- The input image was processed using OpenCV for face detection with Haar Cascade classifiers.
- Detected face regions were converted to HSV color space.
- Hue and Saturation values were extracted as feature vectors.
- K-Means clustering was applied to group faces based on feature similarity.
- Results were visualized using scatter plots and annotated images.

## Key Findings
- Faces with similar color characteristics were grouped into the same clusters.
- K-Means effectively separated faces based on extracted HSV features.
- Visualization helped in understanding cluster separation and face grouping.

## Conclusions
This lab demonstrates how basic feature extraction combined with unsupervised learning can be used for grouping similar visual patterns. While the approach is simple, it highlights the importance of feature selection and clustering in pattern recognition tasks.
