# CyberSecurity_LR_Model
This repository provides code for a machine learning classifier that detects and categorises cyber attacks in network data. The project focuses on using a Logistic Regression model to detect intrusions and do cybersecurity assessments.


# Intrusion Detection with Logistic Regression
This repository contains code for a machine learning classifier designed to detect and classify cyber attacks in network data. The project focuses on leveraging a Logistic Regression model for intrusion detection and cybersecurity analysis.

# Table of Contents
* Project Description
* Installation
* Usage
* Dataset
* Evaluation Metrics
* Features
* Prerequisites
* License

# Project Description
This repository provides code for a machine learning classifier that detects and categorises cyber attacks in network data. In today's digital world, cybersecurity is critical, and intrusion detection systems (IDS) play a critical role in protecting sensitive data from unauthorised access and malicious activities. The goal of this project is to create an efficient and effective IDS using a Logistic Regression model.
Because of its simplicity, interpretability, and ability to handle binary classification problems well, the Logistic Regression algorithm is a popular choice for intrusion detection. The project intends to use this classifier to identify many forms of cyber assaults, including Denial of Service (DoS), User to Root (U2R), Remote to Local (R2L), and Probing, among others. The technology can stimulate fast reactions to possible threats and assist administrators safeguard their networks by effectively discriminating between regular network behaviour and distinct attack types.

## Installation
### To use this code, you need the following dependencies:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- scikit-learn
- scipy
- pandas

You can install the required packages using the following command:
pip install tensorflow keras numpy scikit-learn scipy pandas

## Usage
1. Data Preparation: Begin by uploading the dataset file KDDTest.csv to your Google Colab environment or the appropriate working directory.

2. Data Loading and Preprocessing: Run the provided code cells to load the data into a Pandas DataFrame and perform initial data preprocessing steps. This includes handling missing values, encoding categorical features, and scaling numerical variables using z-score normalization.

3. Model Training: The Logistic Regression model will be trained using the preprocessed data. The model aims to learn patterns and relationships from the network data to differentiate normal network behavior from potential cyber attacks.

4. Model Evaluation: After training, the model will make predictions on the test set. The accuracy of the classifier will be computed to quantify its overall performance. Additionally, a confusion matrix will be presented to assess the model's ability to correctly classify different attack types.

5. Interpretation and Insights: Analyze the results and gain insights into the model's strengths and limitations. Understand which features contribute most to accurate predictions and which attack types are more easily distinguishable.



## Dataset
The project uses a dataset named KDDTest.csv, which contains network traffic data collected from real-world scenarios. The dataset includes a diverse range of cyber attacks and normal network activities. Each record is characterized by a set of features representing different aspects of network communication.

## Evaluation Metrics
The model's performance is evaluated using two key metrics:

* Accuracy: Measures the proportion of correctly classified instances out of the total predictions, providing an overall assessment of the model's correctness.

* Confusion Matrix: Offers a granular view of the model's performance by detailing the number of true positive, true negative, false positive, and false negative predictions. The matrix allows understanding the classifier's ability to distinguish between different attack categories.



## Features
The dataset comprises various features that characterize network connections and communication patterns. Some of the key features include:

* duration: Duration of the network connection.
* protocol_type: Type of protocol used for the communication.
* service: Type of service requested.
* flag: Status of the connection (e.g., normal, error, etc.).
* src_bytes: Number of data bytes sent by the source.
* dst_bytes: Number of data bytes received by the destination.

## Prerequisites
Make sure you have Python 3.x installed along with the required dependencies mentioned in the Installation section.

## License
MIT License












