# ❤️ CardioCare: Predicting Heart Disease Risk with Machine Learning & FastAPI 

📌 **Short Description**  
CardioCare develops a predictive machine learning model to identify individuals at risk of heart disease using clinical and behavioral health indicators. It demonstrates a **complete end-to-end workflow**—from exploratory data analysis and feature engineering to model training, evaluation, and API deployment with FastAPI.  

---

## 📊 Project Overview  
This project highlights **data science, machine learning, and deployment skills** through a healthcare-focused classification problem. Beyond notebooks, the trained model is wrapped in a **FastAPI application** with **Pydantic validation** and deployed as a **REST API**, making it usable in real-world scenarios.  
👉 You can go through the project files for detailed instructions on usage and testing.  

---

## 🚀 Key Steps & Skills Demonstrated  

### 📂 Data Loading & Exploration  
- Loaded structured health data with **pandas**.  
- Performed descriptive analysis (`.info()`, `.describe()`) to understand data distribution.  
- Summarized missing values and identified patterns.  

### 🧹 Data Cleaning & Preparation  
- Removed records with missing values.  
- Standardized features for training.  

### 📊 Exploratory Data Analysis (EDA)  
- Visualized relationships between risk factors and heart disease (gender, age groups, BMI, glucose, smoking, diabetes).  
- Tools: **matplotlib, seaborn**.  

### 🔍 Feature Selection  
- Applied correlation analysis to identify top predictors.  

### ⚖️ Handling Imbalanced Data  
- Applied **SMOTE** to balance dataset classes and improve fairness.  

### 🧠 Model Training  
- Trained and compared two models:  
  - 🌲 Random Forest Classifier  
  - 📍 K-Nearest Neighbors (KNN)  

### 📈 Model Evaluation  
- Evaluated models using:  
  - Accuracy Score  
  - Confusion Matrix  
  - Precision, Recall, F1-Score  

### 🌐 Model Deployment  
- Saved trained model using **pickle**.  
- Built a **FastAPI app** with:  
  - `/predict/` endpoint for predictions  
  - **Pydantic validation** for clean input handling  
- Tested the API with **Python requests**.  

---
## 📌 Skills Demonstrated  
- **Data Wrangling & Analysis**: pandas, numpy  
- **Statistical Visualization**: matplotlib, seaborn  
- **Exploratory Data Analysis (EDA) & Feature Engineering**  
- **Class Imbalance Handling**: SMOTE  
- **Machine Learning Classification**: Random Forest, KNN (scikit-learn)  
- **Model Evaluation**: Accuracy, Precision, Recall, F1-Score  
- **Deployment & API Development**: FastAPI, Pydantic, Pickle, Docker  
- **API Testing**: requests  

---

## 🧰 Tools & Technologies Used  
- **Python 3.11**  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, imblearn, FastAPI, Pydantic, requests  

---

## 📂 File Structure  
- `EDA_and_HeartDisease_prediction.ipynb` → Jupyter Notebook containing EDA, feature engineering, model training, and evaluation  
- `model_api.py` → FastAPI application for serving the trained ML model as a REST API  
- `testing.py` → Client script to test API endpoints with sample input data  
- `Dockerfile` → Docker configuration file to containerize the FastAPI application  
- `model.pkl` → Serialized trained machine learning model  
- `dataset.csv` → Raw dataset used for training and analysis
- - Other supporting files → Pickled trained model, dataset.  
---

🔗 **Note**: Please check the repository files for detailed instructions on how to run the project and test the API.  
