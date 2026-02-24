# Colorectal Cancer Classification Using Gut Microbiome Data
## Machine Learning Pipeline Project
### By Muhammad Auffa Hakim Aditya

This project was developed by Muhammad Auffa Hakim Aditya as an end-to-end Machine Learning pipeline for classifying colorectal cancer using gut microbiome sequencing data.

The system performs data preprocessing, feature selection, model comparison, synthetic patient simulation, biomarker extraction, and model export for deployment.

------------------------------------------------------------

## 📌 Project Overview

Colorectal cancer (CRC) is one of the most common cancers worldwide. Recent studies show that gut microbiome composition plays a significant role in colorectal cancer detection.

This project uses microbiome sequencing data to:

- Classify patients into:
  - Healthy
  - Adenomatous Polyps
  - Colorectal Cancer
- Extract top microbial biomarkers
- Compare multiple ML models
- Generate synthetic patient cases
- Export trained models for web medical application deployment

------------------------------------------------------------

## 📊 Dataset

Dataset Source:
Kaggle - CRC Gut Microbiome ML Data

Files used:
- metadata.csv
- seqtab_nochim_export.xlsx
- taxa_species_export.xlsx

The dataset includes:
- Patient metadata
- Microbiome sequencing features
- Taxonomy mapping (Family, Genus, Species)

------------------------------------------------------------

## ⚙️ Machine Learning Pipeline

### 1️⃣ Data Preprocessing
- Merge metadata and microbiome features
- Encode categorical variables
- Handle missing values
- Clean feature names
- Label encoding for disease status

### 2️⃣ Feature Selection
- Random Forest used to extract Top 200 important features

### 3️⃣ Models Compared

Tree-Based Models:
- Random Forest
- XGBoost
- XGBoost with L1 & L2 Regularization

Linear Models:
- Logistic Regression (L1 / Lasso)
- Logistic Regression (L2 / Ridge)
- Logistic Regression (Top 200 features)

### 4️⃣ Model Evaluation
- Accuracy comparison
- Classification report

------------------------------------------------------------

## 🧬 Biomarker Extraction

Using Logistic Regression coefficients:

- Extract Top 15 microbial biomarkers
- Map DNA fragments to:
  - Family
  - Genus
  - Species
- Export to Excel:
  Laporan_Biomarker_Kanker.xlsx

------------------------------------------------------------

## 🧪 Synthetic Patient Simulation

The system generates complex synthetic patients:

- Synthetic Cancer Patient
- Synthetic Polyp Patient
- Borderline Healthy-Polyp Patient

Prediction output includes:
- Diagnosis
- Probability per class

------------------------------------------------------------

## 💾 Model Export

Exported files for deployment:

- model_logreg_l2_crc.pkl
- scaler_crc.pkl
- label_encoder_crc.pkl
- fitur_template_crc.pkl

These files can be used for:
- Web medical applications
- Clinical decision support systems
- AI diagnostic systems

------------------------------------------------------------

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Joblib

------------------------------------------------------------

## 👨‍💻 Author

Muhammad Auffa Hakim Aditya  
Machine Learning & AI Enthusiast  

This project is part of my research and portfolio in:
- Machine Learning
- Biomedical AI
- Clinical AI Systems
- Microbiome-based Disease Detection

------------------------------------------------------------

## 🚀 Future Improvements

- Deep Learning comparison (MLP / CNN for microbiome vectors)
- SHAP Explainability
- Web-based medical dashboard (Flask / FastAPI)
- Real-time prediction API
- External validation dataset

------------------------------------------------------------

## ⭐ Keywords

Colorectal Cancer Machine Learning  
Gut Microbiome AI  
Biomedical Machine Learning Project  
CRC Classification Model  
Microbiome Biomarker Extraction  
Muhammad Auffa Hakim Aditya Machine Learning  

------------------------------------------------------------

If you find this project useful, feel free to connect and collaborate.
