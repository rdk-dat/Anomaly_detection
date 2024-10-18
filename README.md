# Anomaly_detection
ANOMALY DETECTION SYSTEM USING PYTHON AND MACHINE LEARNING

This project implements an Anomaly Detection System using machine learning algorithms to detect and classify network attacks. The system uses the KDD Cup 1999 dataset and applies Random Forest and Support Vector Machine (SVM) classifiers to differentiate between normal and malicious network activities. To tackle the class imbalance in the dataset, SMOTE (Synthetic Minority Over-sampling Technique) is used, ensuring the model is trained on a balanced dataset.

Key Features
Dataset: KDD Cup 1999, which contains over 4.9 million records of network activities categorized as either normal or attack types (e.g., DoS, Probe, U2R, R2L).
Data Preprocessing: Handled missing values, label-encoded categorical features, and scaled the features using StandardScaler to normalize the data.

Class Imbalance Handling: Utilized SMOTE to oversample the minority classes and balance the dataset for effective training.

Machine Learning Models:
Random Forest Classifier: Achieved high accuracy, precision, recall, and F1 score.
Support Vector Machine (SVM): Implemented with RBF kernel to classify network events.

Evaluation Metrics: Accuracy, precision, recall, and F1 score were calculated for both Random Forest and SVM classifiers.

Visualization: Insights and model performance were visualized using Tableau or Power BI for clear presentation to stakeholders.

Web Application: Built a user-friendly web interface using Flask for real-time predictions on new data.

Technologies Used
Python: Data processing and model implementation (Pandas, Scikit-learn, Imbalanced-learn)
SMOTE: For handling class imbalance in the dataset
Random Forest & SVM: For attack detection and classification
Flask: To create a simple web interface for the system
Tableau/Power BI: To create visualizations of the model performance and dataset insights


Results
Random Forest:

Accuracy: 99.1%
Precision: 98.5%
Recall: 99.0%
F1 Score: 99.0%

SVM:

Accuracy: 97.2%
Precision: 97.2%
Recall: 96.8%
F1 Score: 96.8%

Future Work
Deep Learning: Implement a deep learning-based IDS model using PyTorch for more complex attack patterns.
Real-Time Analysis: Incorporate real-time data streaming to detect live network attacks.
Advanced Visualizations: Extend the visual reporting with more detailed dashboards using Tableau or Power BI.
