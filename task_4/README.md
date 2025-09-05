# PRODIGY_ML_04

📘 Project: Hand Gesture Recognition using CNN (LeapGestRecog Dataset)

🔹 Introduction

This project focuses on building a Convolutional Neural Network (CNN) to classify hand gestures from image data. 

Hand gesture recognition has applications in Human-Computer Interaction (HCI), gaming, sign language translation, and gesture-based control systems.

The model is trained on the LeapGestRecog dataset, which contains grayscale images of various hand gestures captured from different users.

🔹 Dataset Description

Dataset: LeapGestRecog (Kaggle)

- Content:

  Contains multiple gesture classes (e.g., thumbs up, palm, fist, etc.).

  Each gesture is captured across different users, ensuring diversity.

  Images are grayscale, resized to 64×64 pixels for model input.

- Preprocessing:

  Converted to grayscale.

  Normalized pixel values between 0–1.

  One-hot encoding applied to labels for multi-class classification.

🔹 Methodology

- Importing Libraries

  Used cv2, numpy, matplotlib for preprocessing and visualization.

  Used tensorflow/keras for building and training the CNN model.

- Data Preparation

  Extracted images from dataset folders.

  Resized each image to 64×64 pixels.

  Normalized and reshaped into the format (64, 64, 1).

  Split dataset into 80% training and 20% testing sets.

- Model Building (CNN Architecture)

  Conv2D + MaxPooling layers for feature extraction.

  Flatten layer to convert features into a 1D vector.

  Dense layer (128 neurons) with ReLU activation.

  Dropout (0.5) to reduce overfitting.

  Output layer with softmax activation for multi-class classification.

- Training the Model

  Optimizer: Adam

  Loss: Categorical Crossentropy

  Epochs: 10

  Validation performed on test set.

- Evaluation

  Model tested on unseen data.

  Achieved high classification accuracy on test images.

  Prediction on Sample Test Images

  Displayed a random test image.

  Model successfully predicted the correct gesture class.

🔹 Results and Insights

  The CNN achieved strong performance in recognizing gestures.

  Visualization of training and validation accuracy/loss shows good convergence.

  Random test predictions confirmed the model’s ability to classify unseen gestures.

🔹 Conclusion

  This project demonstrates the application of Convolutional Neural Networks for gesture recognition using the LeapGestRecog dataset.
  
  The model can classify multiple gesture categories with high accuracy, highlighting the effectiveness of CNNs in computer vision tasks.

  Such models can be extended to real-time hand gesture recognition for interactive systems, gaming, robotics, and sign language interpretation.
