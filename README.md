#Psoriasis Detection Using CNN

Overview:-

Built a CNN model using ResNet50 to detect psoriasis from skin lesion images.

Aimed to assist dermatologists with early and accurate diagnosis.

Dataset:-

Source: Kaggle – Skin Conditions Classification Dataset.

Images resized to 224x224 pixels.

Split: Train (70%), Validation (20%), Test (10%).

Preprocessing: Normalization and data augmentation (rotation, flipping, zoom).

Model Details:-

Base Model: Pre-trained ResNet50.

Optimizer: Adam | Loss Function: Categorical Crossentropy.

Accuracy: Achieved 66.34% validation accuracy.

Challenges:-

Imbalanced Dataset: Addressed with oversampling and augmentation.

Overfitting: Resolved using dropout layers and regularization.

Future Enhancements:-

Use a larger dataset for better accuracy.

Deploy the model as a web app using Streamlit.
