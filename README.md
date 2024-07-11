# Image-Classification
This project is an image classifier that detects and classifies images as either "happy" or "sad". It is built using TensorFlow and Keras and has been trained on a dataset containing images classified into these two categories.

Overview:
The goal of this project is to create a neural network that can accurately classify images as happy or sad. This can be useful for applications in emotion detection, sentiment analysis, and various AI-driven user experience improvements.

Loading Data:
We utilize the tf.keras.utils.image_dataset_from_directory API to handle data labeling, reshaping, and batching, making the data preprocessing pipeline straightforward and efficient.

Model Architecture:
The convolutional neural network is built using the Sequential API available in tensorflow.keras.models. The architecture includes the following layers:
Conv2D: Convolutional layers for feature extraction
MaxPooling2D: Max pooling layers for downsampling
Flatten: Flattening the 2D arrays into a 1D vector
Dense: Fully connected layers for classification

Result:
Training and Validation Accuracy:The model achieved an accuracy of approximately 100% on the training dataset, indicating that it learned the features and patterns associated with the "happy" and "sad" images effectively.
During the validation phase, the model maintained a high accuracy, close to 100%, which suggests that the model generalized well to unseen data and did not overfit.

Loss and Accuracy Graphs:The training and validation loss graphs showed a steady decrease, and the accuracy graphs demonstrated an upward trend, which signifies that the model was learning effectively and improving with each epoch.

![image](https://github.com/Dishaswamy/Image-Classification-/assets/136960301/38a04346-8ecc-4280-bc74-9bf230a3f8c3)
![image](https://github.com/Dishaswamy/Image-Classification-/assets/136960301/18b9d08e-701e-400a-bab8-b7f9d4fbc9ac)


