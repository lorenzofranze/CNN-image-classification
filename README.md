# Convolutional Neural Network for Leaf Classification

*Developed between October and November 2023 at Politecnico di Milano*

![image](https://github.com/user-attachments/assets/1e845a90-562a-4c1d-9f2f-9957e0ed007f)

## Project Overview
This project was part of the **Artificial Neural Networks and Deep Learning** course. The goal was to classify images of leaves into two categories based on their health status, making it a binary classification problem. The purpose of the project was to learn the use of Convolutional neural networks.
## Dataset
The dataset consists of images of leaves categorized into two classes indicating their state of health. Preliminary analysis was performed, including the removal of some outliers.

You can download the dataset from [this link](https://drive.google.com/drive/u/0/folders/152B-_69uFDqnDyBIbS0gEhjlwHmqEKeB).

Dataset Details:
- Image size: 96x96
- Color space: RGB
- File Format: npz
- Number of classes: 2
- Classes:
0: "healthy"
1: "unhealthy"
- Dataset Structure:
  - training: containing the 'public_data.npz' file. The file contains the following items:
    - 'data': numpy array of shape 5100x96x96x3, containing the RGB images.
    - 'data': 3-dimensional numpy array of shape 5200x96x96x3, containing the RGB images.
    - 'labels': 1-dimensional numpy array of shape 5200 with values in {'healthy', 'unhealthy'}


## Methodology
- **Model Selection:** Various pretrained models were tested, with **EfficientNetV2B0** showing the best performance.
- **Data augmenation** Different transformations applied on the images in order to increase the sample size and improve model performances.
- **Fine-tuning:** The chosen model was fine-tuned for the specific task and evaluated on the training set.

## Tools
- **Programming Language:** Python
- **Frameworks:** Keras, TensorFlow
