🌾 Analyzing Agricultural Productivity and Resource Use: An Exploratory Study of Indian Districts

This repository contains the dataset analysis, machine learning models, and research paper for a project on district-level rice yield trends in India (1966–2000). The study combines Exploratory Data Analysis (EDA) and Machine Learning (ML) to understand agricultural productivity, spatial disparities, and policy implications.

📄 Research Paper

📕 Title: Analyzing Agricultural Productivity and Resource Use: An Exploratory Study of Indian Districts
👨‍🎓 Authors: Nagendra Vernekar, Shrusti Jadhav, C.R. Pratima, Srikar Kulkarni, Vaishali Y Parab, Salma S Shahapur
📍 Institution: Department of Computer Science and Engineering, KLE Technological University, Belagavi, Karnataka, India

The full paper is included in this repository under paper/PROJECT_AGRI.pdf.

📊 Dataset

Source: ICRISAT District Level Data (1966–2000)

Features:

Year

State

District

Area under rice cultivation

Rice production

Rice yield

Target Variables:

Rice Yield: Low / Not Low

Rice Production: High / Not High

Area under Cultivation: Large / Not Large

🔎 Methodology
1. Exploratory Data Analysis (EDA)

Correlation heatmaps & pair plots

Trends in rice yield, production, and cultivated area

Identification of regional disparities

2. Machine Learning Models

Random Forest Classifier (Best Performing)

K-Nearest Neighbors (KNN) for comparison

3. Performance Metrics

Accuracy

Precision, Recall, F1-Score

Confusion Matrix

ROC & AUC Curves

🚀 Results

Rice yield increased ~75% between 1966 and 2000.

Punjab & Haryana emerged as frontrunners (yield > 3500 kg/ha by 2000).

Eastern & Central India (e.g., Odisha, Bihar, Chhattisgarh) showed stagnation (<1800 kg/ha).

Random Forest Classifier achieved:

Rice Yield: 89.47%

Rice Production: 88.42%

Area Under Cultivation: 98.02%

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Environment: Jupyter Notebook

📂 Repository Structure
├── data/                # Dataset (if included; large files should be linked externally)
├── notebooks/           # Jupyter notebooks for EDA & ML models
├── src/                 # Source code (data processing, modeling)
├── paper/               # Research paper (PDF)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

📌 Key Insights

Machine learning can predict rice yield and production trends with high accuracy.

Regional disparities highlight the need for policy interventions in lagging districts.

Random Forest proved to be the most effective model for district-level agricultural predictions.
