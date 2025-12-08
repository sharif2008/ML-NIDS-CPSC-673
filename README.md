# ML-NIDS-CPSC-673  
Network Intrusion Detection System using Machine Learning  
**CPSC-673: Data Mining Project**

This project implements multiple machine learning algorithms to detect network intrusions using the CIC-IDS-2017 dataset.  
The objective is to classify network flows as **BENIGN** or **ATTACK** using supervised machine learning techniques.

The project includes:
- Exploratory Data Analysis (EDA)
- Feature selection (correlation analysis and RFE)
- Training and evaluation of multiple ML models
- Metrics comparison (Accuracy, Precision, Recall, F1-Score)
- A random prediction demo from the dataset

This repository contains the full experimental notebook and sample dataset for demonstration.

## 📂 Repository  
Public repository:  
https://github.com/sharif2008/ML-NIDS-CPSC-673

## 🧠 Models Implemented
The notebook trains and compares the performance of:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- AdaBoost  
- Support Vector Machine (RBF)  
- Naive Bayes  

Optional (if installed):
- XGBoost  
- CatBoost  

## 📊 Dataset  
Dataset used: CIC-IDS-2017

Due to storage limitations, only one sample CSV is included in this repository.  
The full dataset can be downloaded from public CIC-IDS-2017 sources.  
or  Personal storage link: https://gounbc-my.sharepoint.com/:f:/r/personal/islam5_unbc_ca/Documents/data?csf=1&web=1&e=QQQYWG

Place all required CSV files inside the local `data/` folder.

Expected structure:
```
ML-NIDS-CPSC-673/
├─ data/
│  ├─ Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv
│  ├─ ... full CIC-IDS-2017 files (optional)
├─ notebooks/
│  ├─ NIDS_DM.ipynb
├─ requirements.txt
└─ README.md
```

Target column:
```
Attack_Binary:
0 = BENIGN
1 = ATTACK
```

## ⚙️ Requirements

Install Python 3.x on your system.

Python packages used:
- numpy  
- pandas  
- scikit-learn  
- matplotlib  
- seaborn  
- xgboost  
- catboost  
- jupyterlab or notebook  
- joblib  

Install all required packages using:
```
pip install -r requirements.txt
```

## 🚀 How to Run the Project

### 1. Clone the repository
```
git clone https://github.com/sharif2008/ML-NIDS-CPSC-673
cd ML-NIDS-CPSC-673
```

### 2. Install dependencies
```
pip install -r requirements.txt
```

### 3. Prepare the dataset
- Ensure there is a folder named `data/`
- Copy the required CIC-IDS-2017 CSV files into `data/`

### 4. Launch Jupyter
```
jupyter notebook
```
or:
```
jupyter lab
```

### 5. Open the notebook
Navigate to:
```
notebooks/NIDS_DM.ipynb
```

### 6. Execute the notebook
Run all notebook cells:
- Cell-by-cell: Shift + Enter  
or  
- Full run: Run > Run All Cells

Outputs include:
- Dataset analysis
- Correlation heatmap
- Feature selection results
- Model performance table
- Random flow prediction

## 📈 Expected Output
The notebook displays:
- Model comparison table (Accuracy, Precision, Recall, F1-Score)
- Performance plots
- Data distribution visualization
- Random prediction example showing:
  - Actual label
  - Predicted label

## ✨ Author
**Md Shariful Islam**  
MSc Computer Science (Research-based)  
University of Northern British Columbia  
Course: CPSC 673 — Data Mining
UNBC ID : 230168914
Email: islam5@unbc.ca
