# Sign-Language-Recognition using Convolutional Neural Network (CNN) 

# Objective

The objective of this project is to develop a Convolutional Neural Network (CNN) model for recognizing and classifying hand gestures from image datasets. The model is designed to accurately classify 29 different hand gestures, including alphabetic characters (A-Z) and specific gestures such as 'delete,' 'nothing,' and 'space.'

# Project Workflow

**Data Preprocessing**: Images are preprocessed using TensorFlow and Keras functions for scaling and normalization, ensuring compatibility with the CNN model for effective training.

**Model Architecture**: The CNN model is built with multiple convolutional layers for feature extraction, followed by pooling layers to reduce dimensionality. The extracted features are then passed through fully connected dense layers for final classification across 29 hand gesture classes.

**Optimization**: The model employs Adam and Stochastic Gradient Descent (SGD) optimizers to minimize loss and improve accuracy.

**Callbacks**: ReduceLROnPlateau and early stopping techniques are applied to optimize the model training and prevent overfitting. The initial learning rate is set to 0.001, which is dynamically reduced based on validation loss to ensure more stable and efficient training.
