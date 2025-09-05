# PRODIGY_ML_03

📌 Project Description: Dogs vs Cats Image Classification using CNN

The goal of this project is to build a Convolutional Neural Network (CNN) model that can automatically classify images of dogs and cats. 

This is a classic binary image classification problem widely used to demonstrate the power of deep learning in computer vision.

🔹 Steps in the Project:

- Dataset Preparation

  The dataset used is Dogs vs Cats from Kaggle.

  It consists of thousands of labeled images of cats and dogs.

  The dataset is extracted and divided into training and testing sets.

- Data Preprocessing

  Images are resized to 256x256 pixels.

  Normalization is applied (pixel values scaled between 0 and 1).

  Data generators are used to load images in batches for efficient training.

- Model Building (CNN Architecture)

  The model is built using Keras Sequential API with the following layers:

  Conv2D + MaxPooling layers to extract features from images.

  Flatten layer to convert 2D feature maps into 1D vector.

  Dense layers for classification.

  Output layer with a sigmoid activation function for binary classification.

- Model Compilation & Training

  Optimizer: Adam

  Loss Function: Binary Crossentropy

  Metric: Accuracy

  Model trained for 10 epochs with validation on test data.

- Evaluation & Visualization

  Training and validation accuracy and loss are plotted.

  Model performance is tested on sample images (dog.jpg, etc.).

🔹 Outcome:

  The CNN successfully learns to differentiate between cats and dogs.

  Achieves high accuracy on training and validation datasets.

  Can be used for automatic pet image classification.
