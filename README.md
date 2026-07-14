# 🚀 Spam Shield: End-to-End MLOps Pipeline for SMS Spam Detection

> A production-oriented MLOps pipeline for SMS spam classification, demonstrating the complete machine learning lifecycle—from data ingestion and experiment tracking to cloud-backed model versioning, API deployment, and CI/CD automation.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![MLflow](https://img.shields.io/badge/MLflow-Experiment%20Tracking-blue)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED)
![FastAPI](https://img.shields.io/badge/FastAPI-Serving-009688)
![AWS](https://img.shields.io/badge/AWS-S3-FF9900)
![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-2088FF)

</p>

---

# 📌 Overview

Building an accurate machine learning model is only one part of delivering real-world AI applications. Production systems require reproducibility, version control, experiment tracking, automated deployment, and scalable inference.

This project demonstrates an **end-to-end MLOps workflow** for SMS spam detection by integrating modern ML engineering practices with cloud services and deployment pipelines.

The repository showcases how a traditional NLP classification model can be transformed into a production-ready machine learning application.

---

# ✨ Features

* 📊 End-to-End Machine Learning Pipeline
* 🧹 Automated Data Preprocessing & Feature Engineering
* 🧠 TF-IDF Based NLP Classification
* 📈 MLflow Experiment Tracking & Model Registry
* 📦 Dataset & Model Versioning using DVC
* ☁️ AWS S3 Remote Storage Integration
* 🐳 Dockerized Deployment
* ⚡ FastAPI Model Serving
* 🔄 GitHub Actions CI/CD Pipeline
* 💻 Streamlit Web Interface

---

# 🏗️ System Architecture

```text
                SMS Dataset
                     │
                     ▼
           Data Validation & Cleaning
                     │
                     ▼
         Text Preprocessing (NLTK)
                     │
                     ▼
        TF-IDF Feature Engineering
                     │
                     ▼
         Model Training & Evaluation
                     │
          ┌──────────┴──────────┐
          │                     │
          ▼                     ▼
      MLflow             DVC + AWS S3
 Experiment Tracking     Dataset & Model Versioning
          │                     │
          └──────────┬──────────┘
                     ▼
              Trained Model
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
     FastAPI Service      Streamlit UI
                     │
                     ▼
           GitHub Actions CI/CD
```

---

# ⚙️ Tech Stack

### Programming

* Python

### Machine Learning

* Scikit-learn
* Pandas
* NumPy
* NLTK

### MLOps

* MLflow
* DVC
* Docker
* FastAPI
* GitHub Actions

### Cloud

* AWS S3

### Frontend

* Streamlit

---

# 🔬 MLOps Workflow

### 1️⃣ Data Pipeline

* Dataset ingestion
* Data validation
* Text preprocessing
* Feature engineering using TF-IDF

---

### 2️⃣ Model Development

* Model training
* Hyperparameter tuning
* Performance evaluation
* Model serialization

---

### 3️⃣ Experiment Tracking

Using **MLflow** to

* Track experiments
* Compare model runs
* Log evaluation metrics
* Manage model versions

---

### 4️⃣ Dataset & Model Versioning

Using **DVC**

* Dataset version control
* Model artifact versioning
* Reproducible experiments
* Remote storage through AWS S3

---

### 5️⃣ Deployment

* Docker containerization
* FastAPI REST inference service
* Streamlit frontend for interactive predictions

---

### 6️⃣ CI/CD

GitHub Actions automatically

* Validate code
* Execute workflows
* Build the application
* Deploy updated models

---

# 📂 Project Structure

```bash
SPAM-DETECTOR-MLOPS-END-TO-END-PIPELINE/

│── artifacts/
│── config/
│── data/
│── notebooks/
│── src/
│── pipelines/
│── app.py
│── main.py
│── requirements.txt
│── Dockerfile
│── dvc.yaml
│── .github/workflows/
│── README.md
```

---

# 🚀 Workflow

1. Load SMS dataset.
2. Clean and preprocess text.
3. Generate TF-IDF features.
4. Train and evaluate classification model.
5. Track experiments with MLflow.
6. Version datasets and models using DVC.
7. Push artifacts to AWS S3.
8. Serve predictions through FastAPI.
9. Automate the pipeline using GitHub Actions.

---

# 🎯 Machine Learning Concepts

* Natural Language Processing
* Text Classification
* TF-IDF Vectorization
* Feature Engineering
* Hyperparameter Optimization
* Model Evaluation

---

# 🚀 MLOps Concepts

* Experiment Tracking
* Model Registry
* Dataset Versioning
* Model Versioning
* Reproducibility
* Containerization
* REST API Deployment
* CI/CD Automation
* Cloud Artifact Storage

---

# 📈 Future Improvements

* Kubernetes deployment
* Model monitoring & drift detection
* Automated retraining pipeline
* Feature store integration
* MLflow Model Registry promotion stages
* Infrastructure as Code (Terraform)
* Prometheus & Grafana monitoring
* Batch inference workflows

---

# 🤝 Contributing

Contributions, suggestions, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

# 📜 License

Released under the MIT License.

---

# 👨‍💻 Author

**Harishwar Chinikeri**

B.Tech, Computer Science & Engineering
National Institute of Technology Durgapur

**Areas of Interest**

* Machine Learning
* Generative AI
* MLOps
* Large Language Models
* NLP
* Agentic AI
