# Hybrid XGBoost-LSTM Ensemble with Attention Mechanism
### Remaining Useful Life (RUL) Prediction of Turbofan Engines

![Python](https://img.shields.io/badge/Python-3.9-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Latest-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Latest-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Latest-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## About

This project predicts the **Remaining Useful Life (RUL)** of turbofan engines using a **Hybrid XGBoost-LSTM Ensemble** with a **Soft Attention Mechanism**. It is evaluated on the NASA C-MAPSS benchmark dataset across all four sub-datasets (FD001–FD004).

The final output classifies engine health into three states: 🔴 Critical | 🟡 Warning | 🟢 Healthy

---

## Results

| Sub-dataset | Best Model | RMSE | R² |
|---|---|---|---|
| FD001 | LSTM + Attention | 15.58 | 0.85 |
| FD002 | Hybrid Ensemble | 17.47 | 0.83 |
| FD003 | LSTM + Attention | 13.54 | 0.88 |
| FD004 | Hybrid Ensemble | 23.56 | 0.70 |

---

## Dataset

**NASA C-MAPSS** — Commercial Modular Aero-Propulsion System Simulation  
Included in this repo as `CMAPSSData.zip`

---

## Files

| File | Description |
|---|---|
| `Predictive_Maintenece_LSTM_XGBoost.ipynb` | Main model notebook |
| `CMAPSSData.zip` | NASA C-MAPSS dataset |
| `IST_27 Project Report.pdf` | Full project report |
| `CSE7101-Capstone Project-Review-1.pptx` | Review 1 slides |
| `CSE7101-Capstone Project-Review-2.pptx` | Review 2 slides |
| `CSE7101-Capstone Project-Review-3.pptx` | Review 3 slides |
| `CSE7101-Capstone Project-Review-4.pptx` | Review 4 slides |

---

## Team — IST-27

| Name | Reg. No. |
|---|---|
| Darshan Gowda S | 20221IST0055 |
| Chirag Gowda S V | 20221IST0112 |
| Chethan C | 20221IST0069 |

**Guide:** Dr. Afroz Pasha  
**Institution:** Presidency University, Bengaluru  
**Degree:** B.Tech Information Science & Technology — April 2026
