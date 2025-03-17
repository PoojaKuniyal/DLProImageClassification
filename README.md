# ImageClassification --> Distracted Driver MultiAction Classification
This project aims to classify images into 10 distinct classes based on the action of a driver. It uses a Convolutional Neural Network (CNN) model built with Keras and TensorFlow, which is trained on a dataset of images of drivers performing various actions.

Key Features:
Data Augmentation: Utilized the ImageDataGenerator and flow_from_directory methods to load and preprocess the image data, with on-the-fly augmentation for improved model generalization.
Custom CNN Architecture: Designed a custom CNN model incorporating layers like Conv2D, MaxPooling2D, Dropout, BatchNormalization, and GlobalAveragePooling to effectively classify images.
Pre-trained Model for Feature Extraction: Leveraged the VGG-16 pre-trained model for feature extraction, which was used to improve model performance by taking advantage of learned features from large-scale datasets.
Model Monitoring with Callbacks: Incorporated EarlyStopping to monitor the validation loss and stop training when the model stops improving, and ModelCheckpoint to save the model with the best validation accuracy.
