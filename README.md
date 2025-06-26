<h1 align="center">🌾 Crop Yield Prediction Using Machine Learning 🌾</h1>

<p align="center">
  <font color="gray" size="3">Predicting crop yield based on soil properties and environmental data using ML algorithms</font>
</p>

---

## 📑 Table of Contents

- [About the Project](## 🌱 About the Project)
- [Project Features](#project-features)
- [Tech Stack](#tech-stack)
- [Machine Learning Algorithms Used](#machine-learning-algorithms-used)
- [System Specifications](#system-specifications)
- [System Architecture](#system-architecture)
- [Installation Guide](#installation-guide)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

---

## 🌱 About the Project

This project uses **supervised machine learning algorithms** to predict the most suitable **crop** and **fertilizer** based on soil nutrients, pH, and weather conditions.

<font color="green"><b>Goal:</b></font> To improve crop yield, reduce resource waste, and promote sustainable farming.

### Features Provided:
- ✅ Crop Recommendation
- ✅ Fertilizer Recommendation

---

## ✨ Project Features

- 🔍 Predict crop yield using soil and weather data
- 🌿 Suggest fertilizers based on crop & soil nutrients
- 🌐 Real-time weather using OpenWeatherMap API
- 🎯 High accuracy using Random Forest and XGBoost
- 🧪 Includes unit, integration, and system testing
- 💻 Flask + Jupyter-based user interface

---

## 🛠️ Tech Stack

| Component         | Technology                                                   |
|------------------|--------------------------------------------------------------|
| **Language**      | Python 3.10.2                                                |
| **IDE**           | Jupyter Notebook                                             |
| **Libraries**     | `scikit-learn`, `pandas`, `numpy`, `flask`, `matplotlib`    |
| **ML Models**     | Random Forest, XGBoost, SVM, Naive Bayes, etc.              |
| **Datasets**      | Kaggle, Tata Cornell Institute                              |
| **API**           | OpenWeatherMap API v3.0                                     |
| **Standards**     | ISO/IEC 25010, PEP8                                          |

---

## 🤖 Machine Learning Algorithms Used

| Algorithm           | Accuracy |
|---------------------|----------|
| **Random Forest**   | 0.99     |
| **XGBoost**         | 0.99     |
| **Naive Bayes**     | 0.98     |
| **SVM**             | 0.97     |
| **Logistic Regression** | 0.95 |
| **Decision Tree**   | 0.90     |

✅ **Best Model:** Random Forest (Highest accuracy and robustness)

---

## 💻 System Specifications

### 🔧 Hardware:
- Intel i3 or higher
- 1.6 GHz CPU
- 4–8 GB RAM
- 2–4 GB Disk Space

### 💽 Software:
- OS: Windows 7 or later
- Language: Python 3.10.2
- Platform: Jupyter Notebook

---

## 🧩 System Architecture


- Data is cleaned and normalized
- Visual/Statistical feature engineering
- ML model training and testing
- Web UI with Flask for crop & fertilizer prediction

![System Architecture](https://github.com/Premkumarreddy-datascience/An_Efficient_Analysis_of_Crop_Yield_Prediction_Using_Machine_Learning_Techniques/blob/main/app/static/images/Architecture.jpg)

---

## ⚙️ Installation Guide

### ✅ Prerequisites:
- Python 3.10+
- Anaconda (recommended)
- Internet connection for OpenWeatherMap API

### 🔌 Setup:

```bash
# Step 1: Clone the repository
git clone https://github.com/Premkumarreddy-datascience/An_Efficient_Analysis_of_Crop_Yield_Prediction_Using_Machine_Learning_Techniques
cd crop-yield-prediction

# Step 2: Create environment
conda create --name cropenv python=3.10
conda activate cropenv

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run app
jupyter notebook
# OR for Flask app
python main.py
```
## ▶️ How to Run

### 📓 Jupyter Notebook

1. Open `main.ipynb` or `Crop_Yield_Prediction.ipynb`.
2. Run all cells to:
   - Train machine learning models
   - Test their accuracy
   - Predict crop and fertilizer recommendations

### 🌐 Flask Web Application

1. Run the app using:

   ```bash
   python main.py
   ```

2. Open your browser and visit:

   ```
   http://127.0.0.1:5000/
   ```

3. Enter values in the form to get:
   - Crop recommendation
   - Fertilizer suggestion

## 🗂️ Project Structure

```
crop-yield-prediction/
├── models/
│   ├── RandomForest.pkl
│   ├── DecisionTree.pkl
│   ├── NBClassifier.pkl
│   ├── SVMClassifier.pkl
│   └── XGBoost.pkl
├── utils/
│   ├── disease.py
│   ├── fertilizer.py
│   └── model.py
├── static/
│   ├── css/
│   ├── images/
│   └── scripts/
├── templates/
│   ├── index.html
│   ├── crop.html
│   └── fertilizer.html
├── app.py / main.py
├── crop_prediction.ipynb
├── requirements.txt
└── README.md
```

## 📊 Results

- **Best Performing Model**: Random Forest
- **Accuracy Achieved**: 99%
- **Predicted Outputs**:
  - Most suitable crop
  - Matching fertilizer recommendation
- **User Interface**:
  - Built with Flask
  - Input form and real-time prediction output

## 🙏 Acknowledgements

- **Datasets**: Kaggle, Tata Cornell Institute
- **Weather Data API**: OpenWeatherMap
- **Open-source Tools**:
  - scikit-learn
  - Flask
  - Pandas
  - NumPy
- **Special Thanks**: The open-source community and contributors who made this project possible
