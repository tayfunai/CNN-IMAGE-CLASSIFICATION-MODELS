## 1. Comparison of CNN based image classification architectures
In this tutorial I am going to compare the most popular CNN based DNN architectures for Image Classification, including ***LeNet-5, AlexNet, VGGNet, GoogleNet, ResNet, DenseNet, MobileNet, EfficientNet, Xception and Ensemble method which is DEX (DenseNet, EfficientNet, and Xception).***

And I am gonna use CIFAR-100 dataset to compare all architectures given above. CIFAR-100 contains 60000 32x32 images accross 100 classes.

> **Note:** I trained LeNet-5 CNN architecture on CIFAR-10 dataset with and without data agumentation. Despite getting lower accuracy on training dataset with agumentation, but I got 2% more (70.11 % accuracy) accuracy on the test dataset when I trained the model with data agumentation. That means after image agumentation my LeNet-5 image classification model is able to generalize well on new unseen dataset.

> **Note:** Training VGG19 from scratch on cifar10 dataset which results ***60% ***accuracy on training and ***58%*** on testing. After that Fine tuning VGG19 pre-trained model for detecting pneumonia on Chest X-Ray Images (Pneumonia) dataset, achieving accuracy of ***98%*** and ***82%***, on training and testing, respectively.



