# 🌾 Analyzing Agricultural Productivity and Resource Use  
*An Exploratory Study of Indian Districts (1966–2000)*  

---

## 📖 Project Overview  
This project explores **district-level rice yield trends in India** from **1966 to 2000** using **Exploratory Data Analysis (EDA)** and **Machine Learning (ML)**.  
The research highlights spatial disparities in productivity, the impact of the Green Revolution, and the potential of ML models for yield prediction.  

---

## 📄 Research Paper  
📕 Title: *Analyzing Agricultural Productivity and Resource Use: An Exploratory Study of Indian Districts*  
👨‍🎓 Authors: Nagendra Vernekar, Shrusti Jadhav, C.R. Pratima, Srikar Kulkarni, Vaishali Y Parab, Salma S Shahapur  
🏫 Institution: Department of Computer Science and Engineering, KLE Technological University, Belagavi, India  

📂 Full paper: [`paper/PROJECT_AGRI.pdf`](paper/PROJECT_AGRI.pdf)  

---

## 📊 Dataset  
- **Source:** [ICRISAT District Level Data (1966–2000)](https://www.icrisat.org/)  
- **Features:**
  - Year  
  - State  
  - District  
  - Area under rice cultivation  
  - Rice production  
  - Rice yield  

- **Target Variables:**  
  - `Rice Yield`: Low / Not Low  
  - `Rice Production`: High / Not High  
  - `Area under Cultivation`: Large / Not Large  

---

## 🔎 Methodology  
1. **Exploratory Data Analysis (EDA):**  
   - Correlation heatmaps & pair plots  
   - Yield, production, and area trends  
   - Identification of regional disparities  

2. **Machine Learning Models:**  
   - Random Forest Classifier ✅ *(Best Performing)*  
   - K-Nearest Neighbors (KNN) *(for comparison)*  

3. **Evaluation Metrics:**  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix  
   - ROC & AUC Curves  

---

## 🚀 Results  
- Rice yield increased by **~75%** (1966 → 2000).  
- **Punjab & Haryana** were frontrunners (>3500 kg/ha).  
- **Odisha, Bihar, Chhattisgarh** lagged (<1800 kg/ha).  
- **Random Forest Classifier** achieved:  
  - Rice Yield: **89.47%**  
  - Rice Production: **88.42%**  
  - Area: **98.02%**  

---

## 🛠️ Tech Stack  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📂 Repository Structure  
├── data/ # Dataset (if included; else provide link)
├── notebooks/ # Jupyter notebooks for EDA & ML
├── src/ # Source code (data preprocessing, modeling)
├── paper/ # Research paper (PDF)
├── requirements.txt # Python dependencies
└── README.md # Project documentation
