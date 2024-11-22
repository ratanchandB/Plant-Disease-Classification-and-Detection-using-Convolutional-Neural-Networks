# Plant-Disease-Classification-and-Detection-using-Convolutional-Neural-Networks
Plant Disease Classification and Detection using Convolutional Neural Networks (CNNs). 

## Overview

This project leverages the power of Convolutional Neural Networks (CNNs) for automated plant disease detection and classification based on leaf images. The system is designed to assist farmers, agronomists, and agricultural researchers by providing an efficient tool for early disease diagnosis, enabling timely interventions to prevent crop loss and promote sustainable agriculture.

## Dataset

The project uses the New Plant Diseases Dataset from Kaggle. This dataset comprises labeled images of healthy and diseased plant leaves covering a variety of plant species and diseases.
[DataSet](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)

## Tools and Technologies

**Python**: Primary programming language.
**TensorFlow and Keras**: For building, training, and deploying the CNN model.
**NumPy and Pandas**: For data handling and preprocessing.
**Matplotlib and Seaborn**: For visualizing data distribution and model performance.
**Jupyter Notebook**: Interactive environment for coding and documenting results.

## CNN Architecture

The model employs a deep CNN with skip connections for improved performance. Key components include:

The different layers used in this model are as follows:

**1. Input**
**2. Depthwise Convolution 2D**
**3. Convolution 2D**
**4. Max Pooling 2D**
**5. Global Average Pooling 2D**
**6. Concatenation**
**7. Dropout**
**8. Dense**

### Callbacks

**Early Stopping**: Prevents overfitting by halting training when validation performance stops improving.
**TensorBoard**: Tracks training metrics for analysis.

## Model Evaluation

Accuracy: Achieved a high classification accuracy on test data.

Loss: Minimized during training and validation.

Confusion Matrix: Visualized for performance assessment across classes.
