# CNN Model for Detection Of Brain_Tumor using MRI scans

This project focuses on developing a Convolutional Neural Network (CNN) designed to classify MRI scans into four distinct categories, assisting in the early detection of cancer. The primary aim is to enhance diagnostic accuracy and efficiency, providing a crucial tool for medical professionals. [Brain_MRI_Scan Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)


## Dataset 
The dataset comprises high-quality MRI scans labeled for Brain Tumor Detection. It can be downloaded from [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

### Problem Statement 
 
 The task is a **Classification** problem to predict the type of Brain Tumor present / Not .

 ### Classes

 The dataset includes the following classes:

- **meningioma**
- **glioma**
- **pituitary**
- **notumor**

## Model Architecture

The CNN model comprises two convolutional blocks followed by a fully connected classifier; influenced by TinyVGG16 architecture.

## Performance Metrics

The model was evaluated on both training and test datasets. Below are the key metrics:

### Training Metrics

- **Precision:** 0.9299
- **Recall:** 0.9279
- **F1-score:** 0.9273
- **Accuracy:** 0.9279

### Testing Metrics 

- **Precision:** 0.8873
- **Recall:** 0.8825
- **F1-score:** 0.8809
- **Accuracy:** 0.8825

### Train-Test Loss Over Epochs:

