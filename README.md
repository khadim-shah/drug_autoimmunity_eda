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
This project demonstrates an **advanced Exploratory Data Analysis (EDA)** and **machine learning pipeline** using RDKit molecular descriptor datasets to study potential **drug-induced autoimmunity**.

It covers:
- 🧹 Cleaning and preprocessing descriptor datasets  
- 📈 Visualizing distributions, correlations, and key molecular relationships  
- 🤖 Building baseline Random Forest models  
- 🧠 Explaining results using SHAP values  

All results and plots are auto-saved to: `reports/figures/`

---

## 🧠 Key Highlights
✅ Complete EDA with professional visualizations  
✅ Feature selection with **RFE + SHAP importance**  
✅ Reproducible ML workflow  
✅ Publication-ready plots & structure  
✅ GitHub portfolio-optimized layout  

---

## 📂 Repository Structure
```bash
drug_autoimmunity_eda/
│
├── data/
│   ├── DIA_trainingset_RDKit_descriptors.csv
│   ├── DIA_testset_RDKit_descriptors.csv
│   └── final_cleaned_dataset.csv
│
├── notebooks/
│   └── 01_EDA.ipynb
│
├── reports/
│   ├── figures/
│   │   ├── banner_drug_autoimmunity.png
│   │   ├── label_distribution.png
│   │   ├── correlation_heatmap.png
│   │   ├── feature_importance.png
│   │   ├── shap_feature_importance.png
│   │   └── confusion_matrix.png
│   └── top_features_rfe.csv
│
├── requirements.txt
└── README.md
⚙️ Installation & Setup
bash
Copy code
# 1️⃣ Clone this repository
git clone https://github.com/khadim-shah/drug_autoimmunity_eda.git
cd drug_autoimmunity_eda

# 2️⃣ Create & activate Conda environment
conda create -n drug_autoimmune python=3.10 -y
conda activate drug_autoimmune

# 3️⃣ Install dependencies
pip install -r requirements.txt
# or (recommended)
conda install -c conda-forge rdkit -y

# 4️⃣ Launch Jupyter Notebook
jupyter notebook notebooks/01_EDA.ipynb
📊 Results & Visualizations
Visualization	Description
Dataset label distribution
Descriptor correlation analysis
Top features selected via RFE
SHAP-based model interpretability
Model evaluation metrics

🧰 Tech Stack
Tool	Purpose
🐍 Python 3.10	Core programming language
🧮 Pandas / NumPy	Data preprocessing
📊 Matplotlib / Seaborn	Data visualization
🤖 Scikit-learn	Machine learning models
⚗️ RDKit	Molecular descriptor generation
🔍 SHAP	Model explainability

🧑‍💻 Author
Khadim Shah
📧 khadimshahswt@gmail.com
🔗 LinkedIn
🧬 ORCID
🐙 GitHub

🏁 Next Steps
⚡ Add XGBoost and LightGBM models

🌐 Develop a Streamlit dashboard

🚀 Deploy for real-time predictions

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

🙌 Acknowledgements
RDKit community for cheminformatics tools

Scikit-learn team for ML utilities

SHAP developers for explainability insights

<p align="center"> ⭐ If you found this project interesting, please consider starring the repository! <br>© 2025 <b>Khadim Shah</b> — All Rights Reserved. </p>