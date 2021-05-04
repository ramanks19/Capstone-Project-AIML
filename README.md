# Capstone-Project-AIML
This project was done as part of Capstone Project for PGP in Artificial Intelligence and Machine Learning by Great Learning 

## 📁 Getting Started
The project is built on Google Colab Jupyter Notebook and Kaggle. 

## 🤔 Problem Description
In this capstone project, the goal is to build a Pneumonia Detection System, to locate the position of inflammation in an image. In all, the project objective can be described as:
* Build a reliable Pneumonia Detection Model which can have a robust backing.
* Proper pre-processing and meaningful Exploratory Data Analysis.
* The medical images dataset can be properly trained by a deep learning network with custom architectures
* Use transfer learning to facilitate training with final layers of the deep network trainable
* Learn to fine tune the model by trying different optimizers, loss functions, epochs, learning rate, batch size, check pointing, early stopping etc.
* Read different research papers of given domain to obtain the knowledge of advanced models for the given problem.
* Advocate a strong backing case for the reliability of the model finally obtained by proposing a use case confidence interval.

## 📜 Approach
### 📈 Step 1: Exploratory Data Analysis & Data Preparation
* Understanding the data with a brief on train/test labels and respective class info
* Look at the first five rows of both the csvs (train and test)
* Identify how are classes and target distributed
* Check the number of patients with 1, 2, ... bounding boxes
* Read and extract metadata from dicom files
* Perform analysis on some of the features from dicom files
* Check some random images from the training dataset
* Draw insights from the data at various stages of EDA
* Visualize some random masks generated

**Outcome**
* [Jupyter Notebook Link](https://github.com/ramanks19/Capstone-Project-AIML/blob/main/Pneumonia_Detection%20-%20EDA%20and%20Data%20Prep.ipynb) containing the exploration steps.

### ⚙️ Step 2: Model Building
* Split the data
* Use different models to train the data. Here we are using UNet to train our dataset with different backbone structures
* Evaluate the models (ROC AUC, AP, F1 Score)

**Outcome**
* [Classification - Jupyter Notebook Link](https://github.com/ramanks19/Capstone-Project-AIML/blob/main/Pneumonia%20Detection%20-%20Classification%20and%20Localization.ipynb) with the UNet architecture with pretrained ImageNet weights. Evaluating the model on average precision, accuracy and ROC AUC.
