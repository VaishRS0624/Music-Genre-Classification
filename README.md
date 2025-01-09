# Music-Genre-Classification
## Overview
This project aims to classify music genres based on features extracted from audio files. The model uses machine learning (ML) and deep learning (DL) techniques to predict the genre of a given music track based on its features.

The project implements several machine learning models, including Logistic Regression, Support Vector Machines (SVM), Random Forest, Gradient Boosting, and a Deep Learning model using Keras.

## Project Structure
```bash
/assets
  └── features_3_sec.csv          # CSV file containing features extracted from music tracks
/README.md
/main.py                         # Main script for training and testing models

```

## Requirements
You can install the required dependencies using:
```bash
pip install -r requirements.txt
```

## Steps to Run the Code
### 1. Clone the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/YourUsername/Music-Genre-Classification.git
cd Music-Genre-Classification
```
### 2. Prepare the Dataset
Ensure that the features_3_sec.csv file is placed inside the /assets folder. This file contains the necessary features for training the models.

### 3. Train and Evaluate the Models
Run the following script to train and evaluate different models, including:

Logistic Regression
Support Vector Machines (SVM)
Random Forest Classifier
Gradient Boosting Classifier
Deep Learning Model (Keras)

### 4. Results and Accuracy
After training and evaluating the models, the accuracy of each model will be printed, and confusion matrices will be plotted for each model.

### 5. Visualize Model Performance
The results will be shown as a bar chart comparing the accuracy of all models, and confusion matrices will help evaluate the performance of each model.

## Model Architecture (Deep Learning Model)
The deep learning model consists of the following architecture:

- **Input Layer:** 512 neurons (with ReLU activation)
- **Hidden Layer 1:** 256 neurons (with ReLU activation)
- **Hidden Layer 2:** 128 neurons (with ReLU activation)
- **Hidden Layer 3:** 64 neurons (with ReLU activation)
- **Output Layer:** 10 neurons (with Softmax activation)

The model uses the Adam optimizer and Sparse Categorical Cross-Entropy loss function.

## Results Visualization

Confusion matrices and accuracy plots for each model are visualized using Matplotlib and Seaborn, allowing you to compare model performance visually.
