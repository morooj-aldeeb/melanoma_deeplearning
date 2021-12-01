## Skin Cancer (Melanoma) Deep Learning MVP



## Introduction

In this project we will utilize both general purpose and more specialised types of neural networks to train and classify different skin lesions. 
To this end, we used general purpose Multi-layer Perceptron (MLP) network and Convoluted Neural Network (CNN) to predict and classify the type of skin lesion from dermatoscopic images of real patients. for more information regarding general introduction , data description and data sources for this project, please <a href='proposal.md'>Click here</a>.


## Approach

- All dermatoscopic images were split physically to train, test and validation sets based on their classification labels, this structure is required by `ImageDataGenerator` class which is provided by keras library out of the box. the advantages of using this library is that it partitions images into memory and thus preserve memory and enhances computing performances.

- Two different types of neural networks were training and tested on those images, namely, Multi-Layer Perceptron Network (MLP) and Convoluted Neural Network (CNN) and their both classification metrics were compared and evaluated.


## CNN Visualization

To see the visualization of the simple CNN model, please <a href='simple.cnn.pdf'>Click here</a>.

To see the visualization of the complex CNN Model, please <a href='complex.cnn.pdf'>Click here</a>.



## results

Simple Convoluted Neural Network (Simple CNN)
---------------------------------------------

- By training a very simple CNN network composed of one Convoluted layer, we obtained accuracy for training data of `68 %` and `71 %` accuracy on validation data using ImageDataGenerator instructed to perform Image Augmentation like skewness, rotation, scaling....etc.







