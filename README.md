# MACHINE LEARNING
# Project Overview
        Image Classification for Sugarcane Leaf Diseases
        The goal of this project is to develop a deep learning-based image classification model capable of categorizing sugarcane leaf images into the following categories:
        
        Healthy leaf.
        Infected by rust disease.
        Infected by Red Rot disease.
        Infected by Leaf scald disease.
        Infested by Sugarcane Woolly Aphid.
        We utilized Convolutional Neural Networks (CNN), a type of Deep Learning Model pioneered by Facebook for face detection, to create the image classification model.

# Data Collection

        I have collected a total of 18,000 sugarcane leaf images by conducting visits to nearby sugarcane farms and from google images. There were no specific images collected by any institution in large number, so I had to gather the images myself. The images were collected using an iPhone and Sony DSLR cameras. As this is a pilot project to test the capability of the classification model, I have not used drones for capturing images. 
The images collected are a mix of infected and healthy leaves. Around 14500 sugarcane leaf images will be used for training the CNN model and 3800 images will be used to test the accuracy of the model. This is approximately 80-20 split between testing and training data.


# Dataset Analysis

Image Characteristics
All images are in RGB format, with dimensions ranging from 1080x1616 to 3024x4032 pixels. To standardize the dataset, we resized the images to 100x100 pixels and trimmed unnecessary portions.

Organization
The dataset is meticulously organized into folders, with each folder representing a specific classification. This structured arrangement facilitates efficient training of the image classification model.

This README provides an overview of the project, detailing its objectives, data collection process, and dataset characteristics. For further details, refer to the project documentation and codebase available in the repository.
