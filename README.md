CV 1D Project 2023 by Group 8

Members:
* 1005802 - Swastik Majumdar
* 1005265 - Win Tun Kyaw
* 1005284 - Ishan Monnappa Kodira
* 1005375 - Aditi Kumaresan
* 1005374 - Nguyen Thai Huy
* 1005372 - Prabhakar Dhilahesh

In response to the escalating concerns around distracted driving, our computer vision project sought to deploy simple yet effective solutions for the detection of
distracted behaviors using dashboard camera images. With this in mind, our group has decided to join a State Farm Distracted Driver Detection Kaggle challenge to devise a model capable of categorizing driver behaviors from a dataset consisting of ≈ 79,700 training images and ≈ 22,400 testing images with precision. 

This report outlines the various solutions created to solve the Kaggle challenge. Upon utilization of data augmentation on the train dataset, our solution applied computer vision concepts and algorithms by experimenting with a multitude of approaches to seek what suited this project best, namely: Custom CNN, DenseNet, VGG-16, ResNet, EfficientNet, and an Ensemble Learning of all previous models. 

Significant strides were made in model performance through Ensemble Learning, demonstrating its prowess as the best-performing model with the lowest cross-entropy loss and highest F1 score. However, upon reflection for potential improvements, further refinements were identified. These include the implementation of region of interest (ROI) pooling to focus on critical regions of interest and the adoption of advanced techniques like fine-tuning, batch normalization, enhanced image augmentations, dropout layers, hyperparameter tuning, and a combination of these techniques to further mitigate overfitting and enhance model robustness.
