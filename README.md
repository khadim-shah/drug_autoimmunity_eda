<p align="center">
  <img src="reports/figures/banner_drug_autoimmunity.png" alt="Drug Autoimmunity EDA Banner" width="100%">
</p>

# 🧬 Drug Autoimmunity — Exploratory Data Analysis & Prediction

<p align="center">
<a href="https://github.com/khadim-shah"><img src="https://img.shields.io/badge/GitHub-khadim--shah-black?logo=github" /></a>
<a href="https://www.linkedin.com/in/khadim-shah/"><img src="https://img.shields.io/badge/LinkedIn-Khadim%20Shah-blue?logo=linkedin" /></a>
<a href="https://orcid.org/0009-0007-7110-9010"><img src="https://img.shields.io/badge/ORCID-0009--0007--7110--9010-green?logo=orcid" /></a>
<a href="mailto:khadimshahswt@gmail.com"><img src="https://img.shields.io/badge/Email-khadimshahswt%40gmail.com-red?logo=gmail" /></a>
</p>

---

## 🚀 Project Overview

This project demonstrates an advanced **Exploratory Data Analysis (EDA)** and **machine learning pipeline** using **RDKit molecular descriptor datasets** to investigate potential drug-induced autoimmunity.

It covers:

- 🧹 Data cleaning and preprocessing  
- 📊 Exploratory data analysis and correlation visualization  
- 🤖 Model training using Random Forest  
- 🧠 Model interpretation with SHAP values  

All results and plots are automatically saved in `reports/figures/`.

---

## 🧠 Key Highlights

✅ Comprehensive and reproducible EDA  
✅ Feature selection with RFE and SHAP importance  
✅ Publication-ready plots  
✅ GitHub portfolio-optimized layout  

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
│ │ ├── shap_feature_importance.png
│ │ ├── confusion_matrix.png
│ │ └── sample_feature_distribution.png
│ └── top_features_rfe.csv
│
├── requirements.txt
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

```bash
# 1️⃣ Clone this repository
git clone https://github.com/khadim-shah/drug_autoimmunity_eda.git
cd drug_autoimmunity_eda

# 2️⃣ Create a Conda environment
conda create -n drug_autoimmune python=3.10 -y
conda activate drug_autoimmune

# 3️⃣ Install dependencies
pip install -r requirements.txt
# or (recommended)
conda install -c conda-forge rdkit -y

# 4️⃣ Run the notebook
jupyter notebook notebooks/01_EDA.ipynb
📊 Results & Visualizations
Visualization	Description
Dataset label balance
Feature correlations
Variance-based top features
	Model explainability
Model evaluation

🧰 Tech Stack
Tool	Purpose
🐍 Python 3.10	Core Programming Language
🧮 Pandas / NumPy	Data Processing
📊 Matplotlib / Seaborn	Visualization
🤖 Scikit-learn	Machine Learning
⚗️ RDKit	Molecular Descriptor Generation
🔍 SHAP	Model Explainability

🧑‍💻 Author
Khadim Shah
📧 khadimshahswt@gmail.com
🔗 LinkedIn
🧬 ORCID
🐙 GitHub

🏁 Next Steps
⚡ Add advanced ML models (XGBoost, LightGBM)

🌐 Develop a Streamlit dashboard

🚀 Deploy for interactive predictions

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

🙌 Acknowledgements
RDKit community for cheminformatics tools

Scikit-learn developers for ML utilities

SHAP contributors for model interpretability

<p align="center"> ⭐ If you found this project helpful, please consider starring the repository! <br> © 2025 <b>Khadim Shah</b> — All Rights Reserved. </p>