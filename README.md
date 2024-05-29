# recognizing_solarpanels

# Overview
This project aims to recognize solar panels in aerial images from Swisstopo using Convolutional Neural Networks (CNN).

# Dataset
The dataset comprises 400 satellite images labeled with solar panels and 400 images without solar panels. The data is split into:
    + Training: 60%
    + Validation: 20%
    + Test: 20%
Images are of shape (150, 150, 3) and are in .png format.

# Approach
For the first part of the code we experiment with 3 CNN layers. The last part was with 4 layers

# Result
With 4 layers of CNN, the model reaches 89% of accuracy and a lost of 0.27. 
