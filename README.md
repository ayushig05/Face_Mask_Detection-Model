# Face_Mask_Detection-Model
This repository contains a project for detecting face masks in images using deep learning techniques. The dataset used in this project includes images of people with and without face masks. The goal is to build a model that can accurately classify whether a person is wearing a face mask or not. The dataset used for this project is the Face Mask Detection Dataset from Kaggle which contains images categorized into two classes:
with_mask: Images of people wearing masks.
without_mask: Images of people not wearing masks.

Features about the Model:

Model Architecture: Used Convolutional Neural Networks (CNNs) for feature extraction and classification.

Techniques: Two different architectures were explored for the prediction task:

    •Simple CNN Model: A custom-built CNN with multiple convolutional and pooling layers.
    
    •Pre-trained Model: Transfer learning using a pre-trained model like MobileNetV2 for improved accuracy.
    
Evaluation Metrics: I have shown the accuracy, precision, recall, and F1-score for the model. Additionally, the confusion matrix is plotted to visualize the performance.

Libraries Used: TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Pandas, and Scikit-learn.
