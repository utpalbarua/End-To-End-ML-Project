# End-to-End MLOps Pipeline – Student Performance Prediction

This project implements a **production-ready end-to-end ML pipeline** for predicting student performance using structured educational data. The system follows full **MLOps best practices**, covering the entire ML lifecycle from development to deployment.

---

## 🚀 Key Features

* Modular ML pipeline (ingestion → validation → transformation → training → evaluation)
* **DVC** for data & model versioning
* **MLflow + DagsHub** for experiment tracking and model registry
* **Dockerized** training & deployment
* **AWS SageMaker** for cloud-based training and inference
* Reproducible experiments & environment management

---

## 🛠 Tech Stack

Python, Scikit-learn, Pandas, MLflow, DVC, DagsHub, Docker, AWS SageMaker

---

## 📌 Use Case

Predict student math, reading, and writing performance from demographic and academic features using a scalable and reproducible ML system.

---

## ▶️ Run Project

```bash
dvc pull
pip install -r requirements.txt
python app.py
```
