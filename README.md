Task 1: AI Image Classification with Teachable Machine
Overview

This project demonstrates a simple AI image classification model built using Google Teachable Machine and tested with Python. The model is trained to distinguish between two image categories:

Dog
Cat

After exporting the trained model from Teachable Machine, it was loaded into Python to classify a new image.

Technologies Used
Google Teachable Machine
Python
TensorFlow / Keras
NumPy
Pillow (PIL)

├── Task1_AI_Image_Classification_TeachableMachine.ipynb

├── keras_model.h5

├── labels.txt

├── images (3).jfif

└── README.md


How It Works
Train an image classification model using Google Teachable Machine.
Export the model in TensorFlow/Keras format.
Load the trained model (keras_model.h5) in Python.
Load and preprocess a test image.
Run inference using the trained model.
Display the predicted class and confidence score.


Sample Prediction

The trained model was tested using a dog image.

Prediction Result

Class	Confidence
Dog	100%
Cat	0%

The model correctly identified the uploaded image as a Dog.


Conclusion

This project demonstrates the basic workflow of building and testing an AI image classification model using Google Teachable Machine. Although the training dataset is small, the model successfully classified the test image. Using more training images with greater diversity would improve the model's accuracy and generalization.


