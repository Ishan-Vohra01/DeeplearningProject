Pneumonia Detection using Deep Learning

Introduction
This project aims to develop a deep learning model for detecting pneumonia from chest X-ray images. By leveraging convolutional neural networks (CNNs), the model assists healthcare professionals in making accurate and timely diagnoses of pneumonia.

Dataset
The dataset used in this project is a publicly available set of chest X-ray images. It consists of labeled images classified into two categories:
Normal
Pneumonia

Model Architecture
The model is built using a convolutional neural network (CNN) with the following architecture:

Convolutional layers
Pooling layers
Fully connected layers
Dropout layers for regularization
Preprocessing
Data preprocessing includes:

Resizing images to a uniform size
Normalizing pixel values
Data augmentation techniques such as rotation, flipping, and zooming to improve model generalization
Training
The model is trained using TensorFlow/Keras with the following parameters:

Loss function: Binary Crossentropy
Optimizer: Adam
Metrics: Accuracy
Epochs: 25
Batch size: 32
