# Sign-Language-Recognition using Convolutional Neural Network (CNN) 

# Objective

The objective of this project is to develop a Convolutional Neural Network (CNN) model for recognizing and classifying hand gestures from image datasets. The model is designed to accurately classify 29 different hand gestures, including alphabetic characters (A-Z) and specific gestures such as 'delete,' 'nothing,' and 'space.'

# Project Workflow

**Data Preprocessing**: Images are preprocessed using TensorFlow and Keras functions for scaling and normalization, ensuring compatibility with the CNN model for effective training.

**Model Architecture**: The CNN model is built with multiple convolutional layers for feature extraction, followed by pooling layers to reduce dimensionality. The extracted features are then passed through fully connected dense layers for final classification across 29 hand gesture classes.

**Optimization**: The model employs Adam and Stochastic Gradient Descent (SGD) optimizers to minimize loss and improve accuracy.

**Callbacks**: ReduceLROnPlateau and early stopping techniques are applied to optimize the model training and prevent overfitting. The initial learning rate is set to 0.001, which is dynamically reduced based on validation loss to ensure more stable and efficient training.

## Technologies Used

### Programming Language:
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Framework:
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

### Libraries:
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)

