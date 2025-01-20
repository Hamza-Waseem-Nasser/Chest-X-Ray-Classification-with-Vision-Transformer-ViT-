# Chest X-Ray Classification with Vision Transformer (ViT)

This repository contains a detailed implementation of chest X-ray image classification using three different models:
1. **Vision Transformer (ViT) without freezing parameters**.
2. **Vision Transformer (ViT) with freezing parameters**.
3. **Convolutional Neural Network (CNN) using ResNet50**.

The project aims to classify chest X-ray images into four distinct categories: COVID-19, Normal, Pneumonia-Bacterial, and Pneumonia-Viral. The dataset used is the **Chest X-Ray Images dataset**, available on Kaggle.

---

## Dataset

The dataset consists of chest X-ray images categorized into four classes:
1. **COVID-19**: X-ray images from patients diagnosed with COVID-19.
2. **Normal**: X-ray images from healthy individuals without any respiratory disease.
3. **Pneumonia-Bacterial**: X-ray images from patients diagnosed with bacterial pneumonia.
4. **Pneumonia-Viral**: X-ray images from patients diagnosed with viral pneumonia.

### Dataset Summary
- **Train Set**: 6,902 images belonging to 4 classes.
- **Validation Set**: 923 images belonging to 4 classes.
- **Test Set**: 1,384 images belonging to 4 classes.

You can download the dataset from Kaggle: [Chest X-Ray Images Dataset](https://www.kaggle.com/dataset-link).

---

## Getting Started

### 1. Setting Up the Environment
To run the notebook, follow these steps:
1. **Access Google Colab**:
   - Open [Google Colab](https://colab.research.google.com/).
   - Click on `File > Open notebook`.
   - Select the `GitHub` tab and paste the repository link, or upload the notebook directly from your local machine.

2. **Mount Google Drive** (if using Colab):
   - Upload the dataset to your Google Drive.
   - Run the following code snippet to mount Google Drive in Colab:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

3. **Install Required Libraries**:
   Ensure you have the necessary libraries installed by running:
   ```python
   !pip install torch torchvision transformers

[View the Vit PDF](./Vit.pdf)
