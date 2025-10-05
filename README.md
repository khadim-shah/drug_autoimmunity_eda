<p align="center">
  <img src="reports/figures/banner_drug_autoimmunity.png" alt="Drug Autoimmunity EDA Banner" width="100%">
</p>

<h1 align="center">🧬 Drug Autoimmunity — Exploratory Data Analysis & Prediction</h1>

<p align="center">
  <a href="https://github.com/khadim-shah"><img src="https://img.shields.io/badge/GitHub-@khadim--shah-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/khadim-shah/"><img src="https://img.shields.io/badge/LinkedIn-Khadim%20Shah-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://orcid.org/0009-0007-7110-9010"><img src="https://img.shields.io/badge/ORCID-0009--0007--7110--9010-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="mailto:khadimshahswt@gmail.com"><img src="https://img.shields.io/badge/Email-khadimshahswt%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## 🚀 Project Overview

This project demonstrates an **advanced Exploratory Data Analysis (EDA)** and **baseline machine learning workflow** on RDKit molecular descriptor datasets to study potential drug-induced autoimmunity.

It focuses on:
- Understanding and cleaning molecular descriptor datasets  
- Visualizing distributions, correlations, and key molecular properties  
- Building baseline Random Forest models  
- Interpreting model results using SHAP explainability  

The notebook is **fully reproducible** and structured for professional data science portfolio presentation.

---

## 🧠 Key Highlights

✅ Comprehensive EDA with interactive visuals  
✅ Feature selection using RFE and SHAP importance  
✅ Clean and reusable data pipeline  
✅ Publication-ready visualizations in `reports/figures/`  
✅ GitHub-ready structure and README  

---

## 📂 Repository Structure

DRUG_AUTOIMMUNITY_EDA/
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


> 🧩 *All plots and generated datasets are saved automatically during notebook execution.*

---

## 🧾 Data Description

| File | Description |
|------|--------------|
| `DIA_trainingset_RDKit_descriptors.csv` | Training molecules with RDKit descriptors and labels |
| `DIA_testset_RDKit_descriptors.csv` | Testing molecules for model evaluation |
| `RDKit_ChemDes.xlsx` | Reference descriptor file (optional) |
| `final_cleaned_dataset.csv` | Final preprocessed dataset after cleaning and feature selection |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/khadim-shah/drug_autoimmunity_eda.git
cd drug_autoimmunity_eda

2️⃣ Create a conda environment
conda create -n drug_autoimmune python=3.10 -y
conda activate drug_autoimmune

3️⃣ Install dependencies
pip install -r requirements.txt
# or (recommended)
# conda install -c conda-forge rdkit -y

4️⃣ Run the notebook
jupyter notebook notebooks/01_EDA.ipynb

📊 Results & Visualizations

Correlation heatmaps for descriptor relationships

Label distribution plot

SHAP-based feature importances

RFE-selected top features

Confusion matrix and model evaluation metrics

All saved in: reports/figures/

🧩 Example Visuals
<p align="center"> <img src="reports/figures/feature_importance.png" alt="Feature Importance" width="70%"> </p> <p align="center"> <img src="reports/figures/shap_feature_importance.png" alt="SHAP Feature Importance" width="70%"> </p>
🧰 Tech Stack

Python 3.10

Pandas / NumPy

Matplotlib / Seaborn

Scikit-learn

RDKit

SHAP

🧑‍💻 Author

Khadim Shah
📧 khadimshahswt@gmail.com

🔗 LinkedIn

🧬 ORCID

🐙 GitHub

🏁 Next Steps

Integrate advanced ML models (XGBoost, LightGBM)

Build a Streamlit dashboard for molecular analysis

Deploy the model for live prediction

📜 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

🙌 Acknowledgements

RDKit community for molecular descriptor tools

Scikit-learn developers for machine learning utilities

SHAP team for model explainability support

<p align="center"> <b>⭐ If you found this project interesting, please consider starring the repository!</b><br> © 2025 Khadim Shah — All Rights Reserved. </p> ```