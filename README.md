# MobiSense Transportation Mode Classification

Machine learning project focused on classifying transportation modes using smartphone sensor data.

## Overview

This project explores transportation mode recognition using mobile sensor measurements. The objective is to process sensor data, extract meaningful features, and train machine learning models capable of distinguishing between different modes of transportation.

The project was completed as part of the **MobiSense research project at the American University of Beirut (AUB)**.

## Approach

The notebook implements a machine learning pipeline that includes:

* Loading and preprocessing sensor data
* Cleaning and organizing measurements
* Feature extraction from sensor signals
* Analysis of missing sensor measurements
* Preparation of training and testing datasets
* File-level train/test splitting to reduce data leakage
* Training an **XGBoost classifier**
* Model evaluation using classification metrics
* Feature importance analysis

GPS coordinates are excluded from the feature set so that classification relies on sensor-derived characteristics rather than direct location information.

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Google Colab

## Dataset

The notebook uses transportation sensor data collected across multiple mobility modes.

The raw dataset is **not included in this repository**.

## Repository Structure

```text
mobisense-transport-classification/
├── mobisense_transport_classification.ipynb
├── README.md
└── .gitignore
```

## Notebook

The complete analysis and machine learning workflow can be found in:

`mobisense_transport_classification.ipynb`

The notebook includes the original saved outputs from the experiments so that the analysis and model results can be viewed directly without rerunning the complete pipeline.

## Skills Demonstrated

* Machine Learning
* Data Preprocessing
* Feature Engineering
* Classification
* Model Evaluation
* Sensor Data Analysis
* Python Data Science Workflow

## Author

**Talia Semaan**
Computer & Communications Engineering
American University of Beirut
