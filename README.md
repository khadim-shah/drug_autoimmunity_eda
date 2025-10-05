<p align="center">
  <img src="reports/figures/banner_drug_autoimmunity.png" alt="Drug Autoimmunity Banner" width="100%">
</p>

<h1 align="center">🧬 Drug Autoimmunity — Exploratory Data Analysis & Prediction</h1>

<p align="center">
This project explores <b>drug-induced autoimmunity</b> using advanced data analysis and machine learning.<br>
It performs <b>Exploratory Data Analysis (EDA)</b>, <b>feature selection</b>, and <b>predictive modeling</b> using molecular descriptors from RDKit.
</p>

---

## 🚀 Project Overview
This repository demonstrates a full workflow for molecular data science — from data cleaning to model explainability.

**Key Objectives**
- 🧹 Clean and preprocess RDKit descriptor datasets  
- 📊 Perform EDA with correlations, distributions, and variance checks  
- 🤖 Build baseline Random Forest models for binary classification  
- 🧠 Use SHAP values for interpretability and feature importance visualization  

All visual outputs are saved automatically to: `reports/figures/`

---

## 🧠 Key Highlights
✅ Comprehensive and reproducible EDA  
✅ Feature selection using RFE and SHAP  
✅ Publication-ready, high-quality visualizations  
✅ Clean and professional GitHub project structure  

---

## 📂 Repository Structure
drug_autoimmunity_eda/
│
├── data/
│ ├── DIA_trainingset_RDKit_descriptors.csv
│ ├── DIA_testset_RDKit_descriptors.csv
│ └── final_cleaned_dataset.csv
│
├── notebooks/
│ └── 01_EDA.ipynb
│
├── reports/
│ ├── figures/
│ │ ├── banner_drug_autoimmunity.png
│ │ ├── label_distribution.png
│ │ ├── correlation_heatmap.png
│ │ ├── feature_importance.png
│ │ ├── shap_feature_importance.png
│ │ └── confusion_matrix.png
│ └── top_features_rfe.csv
│
├── requirements.txt
└── README.md

---

## ⚙️ Installation & Setup

**1️⃣ Clone this repository**
```bash
git clone https://github.com/khadim-shah/drug_autoimmunity_eda.git
cd drug_autoimmunity_eda
2️⃣ Create and activate a Conda environment

bash
Copy code
conda create -n drug_autoimmune python=3.10 -y
conda activate drug_autoimmune
3️⃣ Install dependencies

bash
Copy code
pip install -r requirements.txt
# or (recommended)
conda install -c conda-forge rdkit -y
4️⃣ Run the notebook

bash
Copy code
jupyter notebook notebooks/01_EDA.ipynb
📊 Results & Visualizations
<p align="center"> <img src="reports/figures/label_distribution.png" alt="Label Distribution" width="65%"> </p> <p align="center"> <img src="reports/figures/correlation_heatmap.png" alt="Correlation Heatmap" width="65%"> </p> <p align="center"> <img src="reports/figures/feature_importance.png" alt="Feature Importance" width="65%"> </p> <p align="center"> <img src="reports/figures/shap_feature_importance.png" alt="SHAP Feature Importance" width="65%"> </p>
🧰 Tech Stack
Tool	Purpose
🐍 Python 3.10	Core language
🧮 Pandas / NumPy	Data manipulation
📊 Matplotlib / Seaborn	Visualization
🤖 Scikit-learn	Machine learning
⚗️ RDKit	Chemical descriptor generation
🔍 SHAP	Model explainability

🧑‍💻 Author
Khadim Shah

<p align="center"> <a href="mailto:khadimshahswt@gmail.com"><img src="https://img.icons8.com/ios-filled/30/3498db/email.png" alt="Email"/></a> &nbsp;&nbsp; <a href="https://www.linkedin.com/in/khadim-shah/"><img src="https://img.icons8.com/ios-filled/30/0a66c2/linkedin.png" alt="LinkedIn"/></a> &nbsp;&nbsp; <a href="https://github.com/khadim-shah"><img src="https://img.icons8.com/ios-glyphs/30/ffffff/github.png" alt="GitHub"/></a> &nbsp;&nbsp; <a href="https://orcid.org/0009-0007-7110-9010"><img src="https://img.icons8.com/ios-filled/30/00cc66/orcid.png" alt="ORCID"/></a> &nbsp;&nbsp; <a href="https://www.kaggle.com/khadimshah"><img src="https://img.icons8.com/windows/30/20BEFF/kaggle.png" alt="Kaggle"/></a> </p>
🧭 Next Steps
⚡ Add XGBoost and LightGBM models

🌐 Develop a Streamlit dashboard

🚀 Deploy for real-time predictions

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

🙌 Acknowledgements
RDKit community for cheminformatics tools

Scikit-learn developers for ML utilities

SHAP team for explainability frameworks

<p align="center"> ⭐ If you found this project helpful, please consider starring the repository! <br> © 2025 <b>Khadim Shah</b> — All Rights Reserved. </p>