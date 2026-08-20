# Experiment 4 — Transfer Learning Using Pre-Trained Vision Models

**Date:** 17/08/2026

## Aim
To implement transfer learning and fine-tuning using a pre-trained **ResNet50** model for Cats vs Dogs image classification and compare it with a pre-trained Hugging Face Vision Transformer (ViT).

## Dataset
**Cats vs Dogs Dataset — Kaggle:**  
[Dataset Link](https://www.kaggle.com/datasets/salader/dogs-vs-cats)

The dataset was split into **training, validation, and testing** sets and processed using resizing, normalization, and data augmentation.

## Implementation

- Prepared and visualized the Cats vs Dogs dataset.
- Implemented **ResNet50 Transfer Learning** with ImageNet pre-trained weights.
- Added Global Average Pooling, Dropout, and a Sigmoid classification layer.
- Trained and evaluated the model using Binary Cross-Entropy and Adam optimizer.
- Visualized training/validation accuracy and loss.
- Fine-tuned the later ResNet50 layers using a smaller learning rate.
- Used `model.predict()` to classify sample images.
- Loaded a pre-trained **Hugging Face Vision Transformer (ViT)** for image classification.
- Compared ResNet50 and Hugging Face predictions.

## Technologies

`Python` · `TensorFlow/Keras` · `ResNet50` · `Hugging Face` · `ViT` · `NumPy` · `Matplotlib` · `Jupyter Notebook` · `VS Code`

## Dataset
cats vs dogs mini dataset
dataset link: https://www.kaggle.com/datasets/aleemaparakatta/cats-and-dogs-mini-dataset

## Observation

ResNet50 achieved good classification performance using transfer learning. Fine-tuning the later layers allowed the model to adapt its pre-trained features to the Cats vs Dogs dataset. The Hugging Face ViT also successfully classified sample images using its pre-trained knowledge.

## Result

Transfer learning and fine-tuning using **ResNet50** were successfully implemented and evaluated, and its predictions were compared with a pre-trained **Hugging Face ViT** model.
