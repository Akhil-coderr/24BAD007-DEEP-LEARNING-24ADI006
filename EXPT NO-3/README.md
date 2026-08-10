# EXPT NO-3 — CNN Image Classification

## Implementation of Convolutional Neural Networks (CNNs) for Image Classification

In this experiment, I implemented a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to classify images from the **Intel Image Classification dataset**.

### What I Implemented

* Prepared and preprocessed the image dataset.
* Resized images to **150 × 150** and normalized pixel values.
* Split the training data into **training and validation sets**.
* Built a CNN using:

  * Convolutional layers
  * Batch Normalization
  * ReLU activation
  * Max Pooling
  * Flatten and Dense layers
  * Dropout
  * Softmax output layer
* Compiled the model using the **Adam optimizer** and **Sparse Categorical Crossentropy**.
* Trained the model and monitored training and validation performance.
* Visualized **Accuracy vs Epoch** and **Loss vs Epoch**.
* Evaluated the model using **test accuracy and test loss**.
* Analyzed performance using a **Confusion Matrix**.
* Generated **sample predictions and misclassified images**.
* Saved the trained CNN model for future use without retraining.

### Dataset

**Intel Image Classification Dataset**

https://www.kaggle.com/datasets/puneet6060/intel-image-classification

Classes:

`Buildings` • `Forest` • `Glacier` • `Mountain` • `Sea` • `Street`

### Tools & Technologies

`Python` • `TensorFlow/Keras` • `NumPy` • `Matplotlib` • `Scikit-learn` • `VS Code`

### Key Learning

This experiment provided hands-on experience in building an end-to-end CNN image classification pipeline, from **image preprocessing and feature extraction to model training, evaluation, and performance analysis**.

