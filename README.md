# 3D-Image-classification-of-CT-scans
This example will show the steps needed to build a 3D convolutional neural network (CNN) to predict the presence of viral pneumonia in computer tomography (CT) scans. 2D CNNs are commonly used to process RGB images (3 channels). A 3D CNN is simply the 3D equivalent: it takes as input a 3D volume or a sequence of 2D frames (e.g. slices in a CT scan), 3D CNNs are a powerful model for learning representations for volumetric data.

The code is inspired from the following paper: https://arxiv.org/abs/2007.13224

The Dataset used was a subset of the following data: https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1

## Network architecture:
![Alt text](relative/path/to/img.jpg?raw=true "Title")
