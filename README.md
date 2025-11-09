# 🧠 Gender Classification using Machine Learning  

This project presents an **end-to-end Machine Learning solution** that predicts **gender (Male/Female)** based on measurable features such as **height, weight, and voice pitch**.  
It demonstrates the **complete ML lifecycle** — from data preprocessing and model training to **API deployment** and **MLOps automation** using **Docker, Jenkins, and Kubernetes**.  

---

## 🚀 Project Overview  
The objective of this project is to build a **robust, production-ready gender classification system** capable of making real-time predictions.  
The system is deployed as a RESTful API, integrated with MLOps tools to ensure **reliability, scalability, and maintainability** across environments.

✨ **Key Highlights:**  
- 🧩 End-to-End ML pipeline (Data → Model → API → Deployment)  
- 🐳 Dockerized setup for cross-environment consistency  
- ⚙️ CI/CD automation using Jenkins and Kubernetes  
- 📊 MLflow integration for experiment tracking and model versioning  

---

## 🧰 Tech Stack  

| Category | Tools & Technologies |
|-----------|----------------------|
| **Language** | Python 🐍 |
| **Libraries** | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| **Frameworks** | Flask / FastAPI |
| **MLOps Tools** | MLflow, Docker, Jenkins, Kubernetes |
| **Version Control** | Git & GitHub |
| **Deployment** | REST API, Docker, K8s Cluster |

---

## ⚙️ Workflow  

### 🔹 Step 1: Data Preprocessing  
- Cleaned, normalized, and encoded dataset features.  
- Removed outliers and handled missing values for balanced data.  

### 🔹 Step 2: Model Training  
- Trained using **Logistic Regression**, **Random Forest**, and **SVM** classifiers.  
- Hyperparameter tuning via **GridSearchCV** for optimal performance.  

### 🔹 Step 3: Model Evaluation  
- Evaluated on test data using **Accuracy**, **Precision**, **Recall**, and **F1-score**.  
- Achieved **~94% accuracy** with excellent generalization.  

### 🔹 Step 4: API Development  
- Built **Flask/FastAPI** endpoint `/predict` for real-time inference.  
- Integrated input validation and JSON-based responses.  

### 🔹 Step 5: Containerization & Deployment  
- Dockerized the entire application for portability.  
- Deployed on **Kubernetes cluster** with **Jenkins CI/CD** pipeline.  

### 🔹 Step 6: Experiment Tracking  
- Used **MLflow** to monitor metrics, parameters, and model versions.  
- Ensured reproducibility and transparency in experimentation.  

---

  "voice_pitch": 205
}
