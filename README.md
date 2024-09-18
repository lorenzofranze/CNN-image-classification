# Convolutional Neural Network for Leaf Classification

*Developed between October and November 2023 at Politecnico di Milano*

![image](https://github.com/user-attachments/assets/1e845a90-562a-4c1d-9f2f-9957e0ed007f)

## Project Overview
This project was part of the **Artificial Neural Networks and Deep Learning** course. The goal was to classify images of leaves into two categories based on their health status, making it a binary classification problem.

## Dataset
The dataset consists of images of leaves categorized into two classes indicating their state of health. Preliminary analysis was performed, including the removal of some outliers.

You can download the dataset from [this link](https://drive.google.com/drive/u/0/folders/152B-_69uFDqnDyBIbS0gEhjlwHmqEKeB).

## Methodology
- **Model Selection:** Various pretrained models were tested, with **EfficientNetV2B0** showing the best performance.
- **Fine-tuning:** The chosen model was fine-tuned for the specific task and evaluated on the training set.

## Tools
- **Programming Language:** Python
- **Frameworks:** Keras, TensorFlow
