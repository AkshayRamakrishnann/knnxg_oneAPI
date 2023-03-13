# Fetal Health Classification using KNN and XGBoost
This project aims to classify fetal health based on various features using two popular machine learning algorithms - K-Nearest Neighbors (KNN) and XGBoost.

## Dataset
The dataset used in this project is the Cardiotocography (CTG) dataset from the UCI Machine Learning Repository. This dataset contains 2126 fetal cardiotocograms (CTG) and their respective fetal health classification by expert obstetricians. The features used in this dataset are:

Baseline Fetal Heart Rate (FHR)
Number of Fetal Movements (FM)
Uterine Contractions (UC) - duration, number, and intensity
Fetal Heart Rate Accelerations (AC)
Fetal Heart Rate Decelerations (DP)
Gestational Age (GA)
pH of fetal blood

## Requirements
This project requires the following Python packages:

pandas
numpy
sklearn
xgboost
You can install these packages using pip:

Copy code
pip install pandas numpy sklearn xgboost
Usage
You can clone this repository using the following command:

bash
Copy code
git clone https://github.com/your-username/fetal-health-classification.git
After cloning the repository, you can run the fetal_health_classification.ipynb Jupyter notebook to train and test the KNN and XGBoost classifiers on the CTG dataset.

## Results
After training and testing the KNN and XGBoost classifiers on the CTG dataset, we achieved the following classification accuracies:

KNN: 93.89%
XGBoost: 96.28%
These results suggest that XGBoost is a more effective classifier for fetal health classification based on the given features.

## Acknowledgments
The Cardiotoc
