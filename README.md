# Brain Tumor Detection MRI using CNN

## Objective :

The goal is to detect brain tumor and classify it using deep learning techniques, specifically Convolutional Neural Network(CNN).

## Steps Taken :

### Data Exploration :

Visualize sample data images and assign labels to each class.

### Data Preprocessing :

Perform data augmentation and normalization using Keras ImageDataGenerator for training and testing datasets.

### Build The Model :

builds a custom Convolutional Neural Network(CNN) model that has three convolution layers, followed by max pooling for each convolution layer. After that, the results are passed through a fully connected layer to perform classification into 4 different classes. The softmax function in the output layer is used to obtain the probability of each class. After that we compile the model using Adam optimizer and train it on the training dataset.

### Model Evaluation :

Evaluated the model's with Categorical Crossentropy for calculating the difference between model predictions and actual labels in multi-class classification and Accuracy metrics for evaluating model performance during training and evaluation.

## Conclusion :

The Convolutional Neural Network (CNN) model shows excellent results in detecting and classifying brain tumors with a high degree of accuracy and minimizing the loss function. Further improvements can be made by exploring other algorithms.

This project demonstrates the applicability of deep learning in real-world scenarios such as brain tumor detection, where data preprocessing, model selection, and evaluation are critical for effective implementation.
