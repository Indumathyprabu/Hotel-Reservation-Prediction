# Hotel Reservation Cancellation Prediction 🏨

**MLOps Pipeline to Predict Booking Cancellations**  
*Optimizing Revenue Management with Machine Learning*

---

## 📌 Overview
This project predicts whether a hotel customer will cancel their reservation using machine learning. It addresses a critical business problem for hotels—revenue loss due to last-minute cancellations—by identifying high-risk bookings early. The solution includes:
- **Data preprocessing** (10M+ rows from Google Cloud Buckets)
- **Model training** (10+ algorithms evaluated, LightGBM deployed)
- **MLOps pipeline** (CI/CD with Jenkins, Docker, GCR, and Google Cloud Run)
- **Experiment tracking** (MLflow) and **data versioning** (DVC)

**Key Metrics (LightGBM Model):**  
✅ **Accuracy:** 88%  
✅ **Recall:** 90% *(Minimizes missed cancellations)*  
✅ **Precision:** 86%  
✅ **F1-Score:** 88%  

---

## 🛠️ Tech Stack
- **ML Frameworks:** LightGBM, Scikit-learn, XGBoost, Random Forest  
- **MLOps Tools:** MLflow, DVC, Jenkins, Docker, Google Cloud Run  
- **Data Engineering:** Google Cloud Buckets, Pandas, Feature Engineering  
- **Deployment:** CI/CD Pipeline (Jenkins → GCR → Cloud Run)  

---

🌟 Key Features
Modular Codebase: LightGBM chosen for deployment due to its efficiency/accuracy trade-off.

Reproducibility: DVC for data versioning, MLflow for experiment tracking.

Scalability: Cloud-native deployment handles 10M+ rows.