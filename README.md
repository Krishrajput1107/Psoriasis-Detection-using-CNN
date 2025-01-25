# Psoriasis-Detection-using-CNN

#Overview
This project utilizes a Convolutional Neural Network (CNN) based on ResNet50 to classify skin lesion images and detect psoriasis, aiding early diagnosis.

#Dataset

Source: Kaggle – Skin Conditions Classification Dataset
Details: Images resized to 224x224, split into train (70%), validation (20%), and test (10%) sets.
Preprocessing: Applied normalization and data augmentation (rotation, flipping, zoom).

#Model

Base Architecture: Pre-trained ResNet50 with custom fully connected layers.
Optimizer: Adam, Loss Function: Categorical Crossentropy
Validation Accuracy: Achieved 66.34%.

#Challenges

Imbalanced dataset resolved through oversampling and augmentation.
Overfitting mitigated using dropout layers and regularization.

#Future Enhancements

Use a larger and more balanced dataset.
Experiment with advanced architectures like EfficientNet.
Deploy as a web app using Streamlit.
