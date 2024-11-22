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

**Structure**
![model](https://github.com/user-attachments/assets/e7c98079-1f11-4d34-bbcc-f8dfe201f839)


## Model Evaluation

**Accuracy**: Achieved a high classification accuracy on test data.

**Loss**: Minimized during training and validation.
![acc_and_loss](https://github.com/user-attachments/assets/40a40c2a-da6e-416d-b47b-c634711da5ad)



**Confusion Matrix**: Visualized for performance assessment across classes.
![confusion_matrix](https://github.com/user-attachments/assets/2298f37b-d018-486b-835c-94fa2a523e96)


## **Metrics**
| | Train | Validation | Test |
| --- | --- | --- | --- |
| Count of Records | 70,295 | 17,572 | 33 |
| Categorical Cross-entropy | 0.1908 | 0.186 | - |
| Categorical Accuracy | 93.70% | 93.91% | 93.93% |
		
			
			
			
