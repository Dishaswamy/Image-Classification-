# Image-Classification
This project is an image classifier that detects and classifies images as either "happy" or "sad". It is built using TensorFlow and Keras and has been trained on a dataset containing images classified into these two categories.

Overview:
The goal of this project is to create a neural network that can accurately classify images as happy or sad. This can be useful for applications in emotion detection, sentiment analysis, and various AI-driven user experience improvements.

Loading Data:
We utilize the tf.keras.utils.image_dataset_from_directory API to handle data labeling, reshaping, and batching, making the data preprocessing pipeline straightforward and efficient.

Model Architecture:
The neural network is built using the Sequential API available in tensorflow.keras.models. The architecture includes the following layers:
Conv2D: Convolutional layers for feature extraction
MaxPooling2D: Max pooling layers for downsampling
Flatten: Flattening the 2D arrays into a 1D vector
Dense: Fully connected layers for classification


