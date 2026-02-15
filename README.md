# MLPR-Lab-5
Aim

The aim of this assignment was to detect faces in an image using Haar Cascade and then apply K-Means clustering based on Hue and Saturation values. The goal was to group similar faces and classify a new template image into one of the clusters.

Methodology

First, the input image was read using OpenCV.
The image was converted to grayscale for face detection.
Haar Cascade classifier was used to detect faces.
For each detected face, the image was converted to HSV color space.
Hue and Saturation features were extracted by calculating their mean values.
K-Means clustering was applied to group the faces into two clusters.
The centroids of both clusters were calculated and plotted.
A template image was processed in the same way and classified into one of the clusters using the trained K-Means model.

Key Findings

Faces were successfully detected using the Haar Cascade classifier.

K-Means clustering grouped faces based on color features (Hue and Saturation).

The centroids represented the average color characteristics of each cluster.

The template image was correctly assigned to one of the existing clusters based on similarity.

Conclusion

This assignment shows how face detection and clustering can be combined for simple image-based classification tasks. It shows how color features can be used to group similar images. The results highlight the usefulness of distance based algorithms like K-Means in real world applications.
<img width="1266" height="699" alt="image" src="https://github.com/user-attachments/assets/b2682798-1546-4bf8-9c4f-ee66ed5976cf" />
<img width="1261" height="701" alt="image" src="https://github.com/user-attachments/assets/fe3f31e0-d403-4482-acbd-fd5bbd2725e8" />
<img width="1273" height="699" alt="image" src="https://github.com/user-attachments/assets/4698d50f-b775-426d-b9c3-6a91f9e7e284" />
<img width="1268" height="688" alt="image" src="https://github.com/user-attachments/assets/a6bf73d3-1636-43ba-99f4-8475c5cea72f" />



