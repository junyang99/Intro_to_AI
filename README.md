# Intro_to_AI
Introduction
This README provides an overview of a deep learning model designed for classifying images from the MNIST and Fashion MNIST datasets. The model utilizes convolutional neural networks (CNNs) and is implemented using TensorFlow. The code includes loading datasets, constructing the CNN architecture, training the model, and evaluating its performance.

Table of Contents
Dataset Loading
Inspect Images
CNN Architecture
Training the Model
Test the Network
1. Dataset Loading <a name="dataset-loading"></a>
The code loads both the MNIST and Fashion MNIST datasets, combining them into a single dataset for training and testing. It then prepares the data for further processing.

2. Inspect Images <a name="inspect-images"></a>
Visual inspection of a subset of images from the combined dataset is performed using Matplotlib. This step helps to verify that the data is loaded correctly and provides insights into the nature of the images.

3. CNN Architecture <a name="cnn-architecture"></a>
The CNN architecture is constructed using TensorFlow's Keras API. The model includes convolutional layers, max-pooling layers, fully connected layers, and dropout layers to prevent overfitting. The architecture is designed to handle both MNIST and Fashion MNIST datasets, with a total of 20 output classes.

4. Training the Model <a name="training-the-model"></a>
The model is trained using the Adam optimizer, and the training progress is monitored using ModelCheckpoint to save the weights after each epoch. The training accuracy and loss are displayed at each epoch.

5. Test the Network <a name="test-the-network"></a>
The trained model is loaded from the saved weights, and its performance is evaluated on the test data. The test accuracy is displayed, and additional marks are awarded based on predefined accuracy conditions.

Usage Instructions
Ensure TensorFlow is installed (pip install tensorflow).
Copy and paste the provided code into a Python script or Jupyter Notebook.
Run the script or notebook to train and test the model.
Feel free to modify hyperparameters, layers, or any other aspects of the code to experiment and improve the model's performance. Happy coding!
