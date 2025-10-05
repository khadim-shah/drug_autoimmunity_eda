<p align="center">
  <img src="https://raw.githubusercontent.com/khadim-shah/drug_autoimmunity_eda/main/reports/figures/banner_drug_autoimmunity.png" alt="Drug Autoimmunity EDA Banner" width="100%">
</p>

# 🧬 Drug Autoimmunity — Exploratory Data Analysis & Prediction

[![GitHub](https://img.shields.io/badge/GitHub-khadim--shah-181717?logo=github)](https://github.com/khadim-shah)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Khadim%20Shah-blue?logo=linkedin)](https://www.linkedin.com/in/khadim-shah/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--7110--9010-green?logo=orcid)](https://orcid.org/0009-0007-7110-9010)
[![Email](https://img.shields.io/badge/Email-khadimshahswt%40gmail.com-red?logo=gmail)](mailto:khadimshahswt@gmail.com)

---

## 🚀 Project Overview

This project demonstrates an advanced **Exploratory Data Analysis (EDA)** and baseline **machine learning pipeline** on RDKit molecular descriptor datasets to study potential **drug-induced autoimmunity**.

It covers:
- 🧹 Cleaning and preprocessing molecular descriptor datasets  
- 📈 Visualizing data distributions, correlations, and feature relationships  
- 🤖 Training baseline **Random Forest** models for binary prediction  
- 🧠 Interpreting results using **SHAP** for feature explainability  

All figures and reports are auto-saved to `reports/figures/`.

---

## 🧠 Key Highlights

✅ Comprehensive EDA with high-quality visualizations  
✅ Feature selection using RFE and SHAP importance  
✅ Fully reproducible ML workflow  
✅ Publication-ready plots and structure  
✅ Portfolio-optimized GitHub presentation  

---

## 📂 Repository Structure

```plaintext
DRUG_AUTOIMMUNITY_EDA/
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
📌 All generated plots and data are automatically saved during notebook execution.

🧾 Data Description
File	Description
DIA_trainingset_RDKit_descriptors.csv	Training molecules with RDKit descriptors
DIA_testset_RDKit_descriptors.csv	Test molecules for model evaluation
final_cleaned_dataset.csv	Final preprocessed dataset after feature selection

⚙️ Installation & Setup
bash
Copy code
# 1️⃣ Clone the repository
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
All results are stored in the reports/figures/ folder.

Visualization	Description
Label distribution across dataset
Feature correlation map
RFE feature importance
Model explainability via SHAP
Model evaluation results

🧰 Tech Stack
Tool	Purpose
🐍 Python 3.10	Core language
🧮 Pandas / NumPy	Data processing
📊 Matplotlib / Seaborn	Visualization
🤖 Scikit-learn	Machine Learning
⚗️ RDKit	Molecular descriptor generation
🔍 SHAP	Model explainability

🧑‍💻 Author
Khadim Shah
📧 khadimshahswt@gmail.com
🔗 LinkedIn
🧬 ORCID
🐙 GitHub

🏁 Next Steps
⚡ Add advanced ML models (XGBoost, LightGBM)

🌐 Build a Streamlit dashboard for molecule visualization

🚀 Deploy the model for real-time prediction

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

🙌 Acknowledgements
RDKit community for descriptor generation tools

Scikit-learn developers for ML utilities

SHAP team for explainability framework

<p align="center"> ⭐ If you found this project interesting, please consider starring the repository! <br>© 2025 <b>Khadim Shah</b> — All Rights Reserved. </p> ```