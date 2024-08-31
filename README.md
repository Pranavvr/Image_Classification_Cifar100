# Image_Classification_Sifar100

Project Overview
This project focuses on implementing and comparing different neural network architectures for image classification using the CIFAR-100 dataset. The dataset comprises 60,000 32x32 color images across 100 different classes. We explore two distinct approaches: one using a traditional Deep Neural Network (DNN) without convolutional layers, and the other combining Convolutional Neural Networks (CNN) with a DNN to enhance classification performance.

1. DNN with CNN Layer
In this approach, the CIFAR-100 dataset is classified using a DNN that incorporates Convolutional Neural Network (CNN) layers. The CNN layers first process the images by extracting spatial features using convolutional filters, which helps in identifying edges, textures, and more complex patterns. These features are then passed to the fully connected layers of the DNN for classification. This combination leverages the strengths of CNNs in capturing spatial hierarchies, making the model more effective in recognizing and classifying images into the 100 distinct categories.

2. DNN without CNN Layer
In this approach, we implement a Deep Neural Network (DNN) for image classification on the CIFAR-100 dataset without utilizing any Convolutional Neural Network (CNN) layers. The images, originally 32x32 pixels with 3 color channels (RGB), are flattened into a 1D vector of 3,072 features. The DNN model consists of multiple fully connected (dense) layers that aim to learn patterns directly from these flattened pixel values. While the DNN can capture some patterns, the absence of CNN layers means it may not effectively learn spatial features, leading to potential limitations in recognizing complex structures within the images.
