# Breast Cancer Image Classifier

A convolutional neural network (CNN)-based project for classifying breast ultrasound images as **malignant** or **benign/normal**, developed as part of the COM2028 Artificial Intelligence module.

This project uses the [BreastMNIST](https://medmnist.com/) dataset and explores deep learning techniques, model evaluation metrics, and transfer learning with ResNet18.

---
## Project Structure

- `CW_AI_2425.ipynb` – Main Jupyter notebook containing all training, evaluation, and visualization code.
---

## Features Implemented

Hyperparameter tuning (learning rate, weight decay, epochs)  
Data augmentation (random rotation, horizontal flipping)  
Comparison between optimizers (SGD vs. Adam)  
Custom CNN model (`Net2`)  
Evaluation metrics: AUC, AUPR, F1 Score, Precision, Recall  
Confusion matrix + ROC curve visualization  
Fixed and implemented k-fold cross-validation  
Transfer learning with fine-tuned ResNet18

