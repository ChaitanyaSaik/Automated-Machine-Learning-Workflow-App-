# 🤖 Automated Machine Learning Workflow App

**Timeline**: September 2024 – December 2024  
**Tech Stack**: Streamlit · Python · Scikit-learn · TensorFlow/Keras · Pandas · NumPy · MongoDB

An end-to-end **ML & DL workflow automation platform** built with Streamlit that empowers users to **train, evaluate, visualize, and deploy machine learning models** seamlessly — without writing code. It supports classification, regression, and clustering tasks, making model experimentation and insight generation accessible for both technical and non-technical users.

---

## 🌟 Key Features

- 🔧 **Interactive Workflow UI** via Streamlit  
- 🤖 Supports **Classical ML** (Scikit-learn) and **Deep Learning** (TensorFlow/Keras) models  
- 📊 Real-time **Data Visualization** and **Metric Reports**  
- 🧠 Train models for:
  - **Classification** (Logistic Regression, Random Forest, DNN)
  - **Regression** (Linear Regression, SVR, DNN)
  - **Clustering** (K-Means, DBSCAN)
- 📁 **Upload your dataset** (CSV format)
- 🔍 **Data Preprocessing** pipeline (null handling, encoding, scaling)
- 📈 **Model Evaluation** (confusion matrix, accuracy, MSE, silhouette score, etc.)
- 💾 MongoDB for storing model performance metadata & logs
- 🚀 Model deployment-ready interface with experiment tracking

---

## 📂 Project Structure

├── app.py # Main Streamlit app
├── data/ # Sample datasets
├── models/ # Saved model artifacts
├── modules/
│ ├── data_preprocessing.py
│ ├── model_training.py
│ ├── visualization.py
│ └── database.py
├── utils/
│ └── helpers.py
├── requirements.txt
└── README.md

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/automl-streamlit-app.git
cd automl-streamlit-app
```
2. Install Dependencies

Copy
Edit
```bash
pip install -r requirements.txt
```
3. Launch the App
   ```bash
streamlit run app.py
```

🛠️ ML/DL Models Used
Task	Algorithms Used
Classification	Logistic Regression, Random Forest, SVM, KNN, Deep Neural Network (Keras)
Regression	Linear Regression, Decision Tree Regressor, SVR, DNN Regressor (Keras)
Clustering	KMeans, DBSCAN, Hierarchical Clustering

💡 Sample Use Case Flow
Upload Dataset

Data Preview & Clean

Choose ML/DL Task: Classification / Regression / Clustering

Train Model (customize hyperparameters)

Evaluate & Visualize Results

Save and Log Model Info in MongoDB

📦 MongoDB Integration
Stores experiment metadata:

Model type

Accuracy / Loss

Hyperparameters

Timestamp

Easily retrieve past experiment logs for reproducibility and tracking

