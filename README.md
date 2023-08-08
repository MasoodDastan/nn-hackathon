# Hotdog or Not Hotdog Hackathon Project
This short two-hour hackathon project draws inspiration from the famous Silicon Valley "hotdog or not hotdog" concept. The objective of this hackathon was to predict whether an image displays a hotdog or not, using a dataset of food images.

## Project Overview
In this project, we utilized transfer learning with the pre-trained VGG19 model to predict whether approximately 3500 food images contain a hotdog or not.

### Preprocessing
To enhance the variety of data and improve model performance, the following preprocessing techniques were employed:

- Data augmentation to create diverse variations
- Shear Transformation for geometric diversity
- Zooming to simulate different perspectives
- Horizontal Flip for mirror-image variations

### CNN Model
The core of the model consisted of a Convolutional Neural Network (CNN) utilizing transfer learning with the VGG19 pre-trained model:

- VGG 19 model as a base 
- Additional Flatten layer
- Supplementary Dense layer

#### About VGG-19
VGG-19 is a pre-trained deep convolutional neural network developed by the Visual Geometry Group (VGG) at Oxford. Comprising 19 layers, including 16 convolutional layers, 3 fully-connected layers, and 5 max-pooling layers, VGG-19 provides an efficient yet deep network structure for image processing tasks.

## Model Results
Baseline Accuracy: 50%
**Our Model's Accuracy: 85.25%**

This hackathon project demonstrates how a quick two-hour effort can yield significant improvements in predicting whether an image contains a hotdog, showcasing the potential of transfer learning and well-designed preprocessing techniques.