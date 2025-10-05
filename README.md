<!-- Banner -->
<p align="center">
  <img src="https://raw.githubusercontent.com/khadim-shah/drug_autoimmunity_eda/main/reports/figures/banner_drug_autoimmunity.png" alt="Drug Autoimmunity EDA Banner" width="100%">
</p>

<h1 align="center">🧬 Drug Autoimmunity — Exploratory Data Analysis & Prediction</h1>

<p align="center">
  <a href="https://github.com/khadim-shah/drug_autoimmunity_eda/stargazers"><img src="https://img.shields.io/github/stars/khadim-shah/drug_autoimmunity_eda?color=gold&style=for-the-badge"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"></a>
</p>

---

## 🚀 Project Overview
This project demonstrates an **advanced Exploratory Data Analysis (EDA)** and **machine learning pipeline** using **RDKit molecular descriptor datasets** to study potential **drug-induced autoimmunity**.

### It covers:
- 🧹 Data cleaning and preprocessing  
- 📊 Exploratory data analysis and correlation visualization  
- 🤖 Model training using Random Forest  
- 🧠 Model interpretation with SHAP values  

All results and plots are automatically saved in `reports/figures/`.

---

## 🧠 Key Highlights
✅ Comprehensive and reproducible EDA  
✅ RFE and SHAP-based feature selection  
✅ Publication-ready plots  
✅ Portfolio-optimized GitHub layout  

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

yaml
Copy code

---

## ⚙️ Installation & Setup

bash
# 1️⃣ Clone this repository
git clone https://github.com/khadim-shah/drug_autoimmunity_eda.git
cd drug_autoimmunity_eda

# 2️⃣ Create a Conda environment
conda create -n drug_autoimmune python=3.10 -y
conda activate drug_autoimmune

# 3️⃣ Install dependencies
pip install -r requirements.txt
# (or recommended)
conda install -c conda-forge rdkit -y

# 4️⃣ Run the notebook
jupyter notebook notebooks/01_EDA.ipynb
📊 Results & Visualizations
Visualization	Description
<img src="https://raw.githubusercontent.com/khadim-shah/drug_autoimmunity_eda/main/reports/figures/label_distribution.png" width="70%">	Label Distribution
<img src="https://raw.githubusercontent.com/khadim-shah/drug_autoimmunity_eda/main/reports/figures/correlation_heatmap.png" width="70%">	Correlation Heatmap
<img src="https://raw.githubusercontent.com/khadim-shah/drug_autoimmunity_eda/main/reports/figures/feature_importance.png" width="70%">	Feature Importance
<img src="https://raw.githubusercontent.com/khadim-shah/drug_autoimmunity_eda/main/reports/figures/shap_feature_importance.png" width="70%">	SHAP Feature Importance
<img src="https://raw.githubusercontent.com/khadim-shah/drug_autoimmunity_eda/main/reports/figures/confusion_matrix.png" width="70%">	Confusion Matrix

🧰 Tech Stack
Tool	Purpose
🐍 Python 3.10	Programming Language
🧮 Pandas / NumPy	Data Handling
📊 Matplotlib / Seaborn	Visualization
🤖 Scikit-learn	Machine Learning
⚗️ RDKit	Chemical Descriptors
🔍 SHAP	Model Explainability

🧑‍💻 Author
Khadim Shah
📧 khadimshahswt@gmail.com
🔗 LinkedIn
🧬 ORCID
🐙 GitHub

🏁 Next Steps
⚡ Add advanced ML models (XGBoost, LightGBM)

🌐 Build a Streamlit dashboard

🚀 Deploy for interactive predictions

📜 License
Licensed under the MIT License — see the LICENSE file for details.

🙌 Acknowledgements
RDKit community for cheminformatics tools

Scikit-learn developers for ML utilities

SHAP contributors for model explainability

<p align="center"> ⭐ If you found this project helpful, please consider starring the repository! <br>© 2025 <b>Khadim Shah</b> — All Rights Reserved. </p>