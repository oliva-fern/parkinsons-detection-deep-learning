# 🧠 Parkinson's Disease Detection using Deep Learning & Voice Features

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow-orange.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-90--95%25-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📌 About the Project
This project presents a **Deep Learning approach to detect Parkinson's Disease** using voice/speech features. 
By analyzing biomedical voice measurements, the model can classify whether a person is likely to have 
Parkinson's Disease or not — enabling early and non-invasive diagnosis.

## 🎯 Objective
To build an accurate and reliable machine learning system that detects Parkinson's Disease 
from voice features using CNN and ensemble methods.

## 📊 Dataset
- **Source:** [Kaggle - Parkinson's Disease Dataset](https://www.kaggle.com)
- **Features:** Biomedical voice measurements including:
  - MDVP:Fo(Hz) — Average vocal fundamental frequency
  - Jitter & Shimmer variations
  - NHR, HNR — Noise-to-Harmonics ratios
  - RPDE, DFA — Nonlinear dynamical complexity measures
  - PPE — Pitch Period Entropy

## 🧪 Models Used
| Model | Description |
|-------|-------------|
| **CNN** | Convolutional Neural Network for feature extraction |
| **Random Forest** | Ensemble learning for robust classification |
| **XGBoost** | Gradient boosting for high accuracy |

## ✅ Results
- **Best Accuracy:** 90% - 95%
- The model successfully distinguishes between healthy individuals and those with Parkinson's Disease

## 🖥️ Features
- Voice feature extraction and preprocessing
- Multiple model comparison
- Interactive Gradio frontend for real-time prediction
- Visualization of results

## 🚀 How to Run
1. Open the notebook in Google Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)
2. Install dependencies:
```bash
pip install gradio tensorflow matplotlib opencv-python scikit-learn xgboost
```
3. Run all cells in `FRONTENDNEW.ipynb`

## 🛠️ Technologies Used
- Python 3.8+
- TensorFlow / Keras
- Scikit-learn
- XGBoost
- Gradio (Frontend)
- Pandas, NumPy, Matplotlib

## 👩‍💻 Author
**oliva-fern**  
Major Project — Deep Learning | Healthcare AI

## 📄 License
This project is licensed under the MIT License.
