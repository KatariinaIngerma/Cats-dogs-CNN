# Cats-dogs-CNN
Classifying images of cats and dogs using convolutional neural network. <br>
This project is a program that uses a deep learning model to classify images as either cats or dogs. 
It is implemented using the Keras library and trained on a dataset of cat and dog images.
### Dataset
The dataset used for training and validation consists of cat and dog images. 
The dataset is organized into separate directories for training and validation, 
with each directory containing subdirectories for cats and dogs. 
The images in the test directory are not labeled and do not have subdirectories.
### Model Architecture
The deep learning model used for classification is based on the following architecture:
1. Convolutional layer with 32 filters and a kernel size of 3x3, followed by a ReLU activation function.
2. Max pooling layer with a pool size of 2x2.
3. Convolutional layer with 128 filters and a kernel size of 3x3, followed by a ReLU activation function.
4. Max pooling layer with a pool size of 2x2.
5. Flatten layer to convert the 2D feature maps into a 1D feature vector.
6. Dense layer with 128 units and a ReLU activation function.
7. Dropout layer with a dropout rate of 0.5 to prevent overfitting.
8. Dense layer with 1 unit and a sigmoid activation function for binary classification.   <br>
The model is compiled with the Adam optimizer, binary cross-entropy loss function, and accuracy as the evaluation metric.
### Results
The model achieved an accuracy of 68% on the test images. 
This means that it correctly classified 68% of the images as either cats or dogs.
