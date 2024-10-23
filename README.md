# Deepfake Audio Detection

This repository contains a Jupyter Notebook implementation of deepfake audio detection using machine learning (SVC) and deep learning (CNN) models on the ASVspoof 2017 dataset. The project includes feature extraction, model training, evaluation, and explainability techniques for cybersecurity applications.

## Dataset

Download the ASVspoof 2017 dataset from [this link](https://datashare.ed.ac.uk/handle/10283/3055).  
Unzip the dataset and update the path in the notebook to point to the unzipped dataset folder.

## Prerequisites

Ensure you have the following installed on your machine:
- Python 3.x
- Jupyter Notebook

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install required libraries:**
   Open the notebook and run the code. If any libraries are missing, install them using:
   ```bash
   pip install <library-name>
   ```

   The most common libraries include:
   - `numpy`
   - `pandas`
   - `librosa`
   - `matplotlib`
   - `seaborn`
   - `sklearn`
   - `keras`
   - `tensorflow`
   - `lime`
   - `shap`

3. **Download and Prepare the Dataset:**
   - Download the dataset from [this link](https://datashare.ed.ac.uk/handle/10283/3055).
   - Unzip the dataset and place it in your working directory.
   - Update the dataset path in the notebook to match the location of your unzipped dataset.

4. **Run the Notebook:**
   - Open the notebook in Jupyter:
     ```bash
     jupyter notebook
     ```
   - Run all the cells in sequence.

## Project Overview

This project implements two models for deepfake audio detection:
- **SVC (Support Vector Classifier)** for machine learning, with explainability techniques like LIME, SHAP, and feature importance.
- **CNN (Convolutional Neural Network)** for deep learning using Mel spectrograms as input features, with Grad-CAM for visual interpretability.

The models are evaluated using:
- Equal Error Rate (EER)
- ROC AUC score
- Accuracy, precision, and recall

## Outputs

After running the notebook, you will get clean outputs with model performance metrics, interpretability visualizations, and insights into the models' decision-making processes.
