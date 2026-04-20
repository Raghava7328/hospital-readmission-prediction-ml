🏥 Hospital Readmission Prediction & Patient Segmentation using Machine Learning
📌 Overview

This project applies Machine Learning techniques to healthcare analytics to predict hospital readmission risk and identify hidden patient groups.

It combines:

Supervised Learning: Decision Tree Classifier (prediction of 30-day readmission)
Unsupervised Learning: K-Means Clustering (patient segmentation)

The project is built using the UCI Diabetes 130-US Hospitals dataset, which contains real-world hospital encounter data.

🎯 Problem Statement

Hospital readmissions are costly and often indicate gaps in patient care.
The goal of this project is to:

Predict whether a patient will be readmitted within 30 days of discharge
Identify patterns in patient behaviour using clustering
Support healthcare decision-making using data-driven insights
📊 Dataset Information
Source: UCI Machine Learning Repository
Dataset: Diabetes 130-US Hospitals (1999–2008)
Size: 100,000+ patient records
Features include:
Patient demographics
Admission details
Medical history
Medication usage
Hospital utilization data

🔗 https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

🛠️ Technologies Used
Python 🐍
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Jupyter Notebook
🧠 Machine Learning Models
1️⃣ Decision Tree Classifier (Supervised Learning)

Used to predict whether a patient will be readmitted within 30 days.

Key Features:

Highly interpretable model
Handles non-linear relationships
Provides decision rules for clinical understanding

Evaluation Metrics:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
2️⃣ K-Means Clustering (Unsupervised Learning)

Used to group patients based on similarity in clinical and hospital usage patterns.

Techniques used:

Feature scaling (standardization)
Elbow Method for optimal clusters
Silhouette Score for cluster validation
📈 Key Results
Decision Tree achieved good overall accuracy but showed lower recall for readmission cases, indicating class imbalance issues.
K-Means clustering identified 3 distinct patient groups:
Low utilization patients
Moderate risk patients
High complexity patients
📊 Visualizations

The project includes:

Confusion Matrix for classification performance
Decision Tree visualization
Elbow Method graph for clustering
Cluster distribution plots
⚠️ Limitations
Imbalanced dataset affected recall for minority class (readmitted patients)
Limited temporal patient history
K-Means assumes spherical clusters, which may not fully reflect healthcare complexity
🚀 Future Improvements
Apply Random Forest or XGBoost for better prediction
Use SMOTE for handling class imbalance
Apply PCA for dimensionality reduction
Deploy as a healthcare decision-support tool
🏥 Real-World Application

This system can assist hospitals in:

Identifying high-risk patients early
Reducing unnecessary readmissions
Improving resource allocation
Supporting clinical decision-making
👨‍💻 Author

Raghava Krishna Anumari
MSc Data Science (UK)
📍 London, United Kingdom

📜 License

This project is licensed under the MIT License.
