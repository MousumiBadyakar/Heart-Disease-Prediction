# ❤️ Heart Disease Prediction

A machine learning-powered web application that estimates the likelihood of heart disease based on user-provided medical parameters. Built with **Python, Scikit-learn, and Streamlit**, the application uses a trained **K-Nearest Neighbors (KNN)** classification model to generate predictions through an interactive web interface.

🔗 **[Live Demo — Heart Disease Prediction](https://heart-disease-prediction-e78ex26dwpsb6wjmlejwbl.streamlit.app)**

---

## 📌 Overview

Heart disease is a major global health concern, making early risk assessment an important area of healthcare research. Machine learning can help explore patterns in medical data and demonstrate how predictive models classify health-related records.

This project implements an end-to-end machine learning workflow, from processing user inputs to generating a prediction using a trained KNN model.

Users can enter the required medical parameters through a Streamlit interface and receive a model-generated result in real time.

> **Important:** This application is an educational demonstration. It does not diagnose heart disease or establish an individual's actual medical risk.

---

## ✨ Features

- ❤️ **Heart Disease Risk Prediction** — Generates a prediction using a trained KNN classification model.
- 🧠 **Machine Learning** — Uses the K-Nearest Neighbors algorithm for classification.
- 🖥️ **Interactive Web Interface** — Enter medical parameters through Streamlit input fields.
- ⚡ **Real-Time Inference** — Generates predictions without manually running a notebook.
- 📊 **Preprocessing Pipeline** — Uses saved scaling and feature-column artifacts to prepare inputs for the model.
- 📦 **Reusable Model Artifacts** — Loads the trained model and supporting files for inference.
- 🌐 **Live Deployment** — Accessible through Streamlit Community Cloud.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Application development |
| Streamlit | Interactive web interface |
| Scikit-learn | KNN model and preprocessing |
| Pandas | Tabular data handling |
| NumPy | Numerical operations |
| Joblib | Loading saved model and preprocessing artifacts |

---

## 🧠 Machine Learning Approach

### Algorithm: K-Nearest Neighbors (KNN)

KNN is a supervised machine learning algorithm that classifies a sample based on the labels of its nearest neighbors in the feature space.

The algorithm compares an input with examples from the training data and predicts a class based on the nearest neighbors.

**Why KNN?**

- Simple and intuitive classification approach.
- Useful for learning relationships in structured datasets.
- Provides a practical introduction to supervised machine learning.
- Demonstrates the importance of feature scaling when distances are used for classification.

### Prediction Workflow

```text
User Input
    ↓
Medical Parameter Collection
    ↓
Feature Preparation
    ↓
Feature Scaling
    ↓
Trained KNN Classifier
    ↓
Predicted Class
    ↓
Result Displayed in Streamlit
```

The application loads the saved model, scaler, and feature-column configuration so that inputs can be prepared consistently with the model's expected format.

---

## 📂 Project Structure

```text
Heart-Disease-Prediction/
│
├── app.py
├── knn_heart_model.pkl
├── heart_scaler.pkl
├── heart_columns.pkl
├── heart.csv
├── requirements.txt
└── README.md
```

### File Descriptions

| File | Description |
|---|---|
| `app.py` | Streamlit application and prediction logic |
| `knn_heart_model.pkl` | Serialized, trained KNN model |
| `heart_scaler.pkl` | Saved feature scaler used during preprocessing |
| `heart_columns.pkl` | Saved feature-column configuration |
| `heart.csv` | Dataset used by the project |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |

---

## ⚙️ Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/MousumiBadyakar/Heart-Disease-Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd Heart-Disease-Prediction
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS / Linux**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
python -m streamlit run app.py
```

Streamlit will provide a local URL where you can access the application in your browser.

---

## 🚀 Try the Application

You can use the deployed application without setting up the project locally.

**[Open Heart Disease Prediction →](https://heart-disease-prediction-e78ex26dwpsb6wjmlejwbl.streamlit.app)**

Enter the requested medical parameters and submit them to see the model-generated prediction.

---

## 🎯 Learning Outcomes

This project demonstrates practical experience with:

- Supervised machine learning and classification.
- The K-Nearest Neighbors algorithm.
- Feature scaling and numerical preprocessing.
- Working with structured, tabular data.
- Saving and loading trained machine learning artifacts.
- Integrating a trained model into a Streamlit application.
- Deploying a machine learning application for public access.

---

## 🔮 Future Improvements

Potential enhancements include:

- 📊 Add evaluation metrics such as precision, recall, F1-score, and ROC-AUC.
- 📈 Visualize model performance using a confusion matrix.
- ⚙️ Compare KNN with Logistic Regression, Random Forest, and other classifiers.
- 🎛️ Experiment with different values of K and distance metrics.
- 🧪 Add automated tests for input validation and prediction behavior.
- 🎨 Further improve the interface and accessibility.
- 📋 Document the dataset, feature definitions, and model limitations.

---

## ⚠️ Medical Disclaimer

This project is developed **for educational and demonstration purposes only**.

The predictions generated by this application are based on a trained machine learning model and user-provided inputs. They are not a medical diagnosis, a clinically validated assessment, or a substitute for professional medical advice, diagnosis, or treatment.

Do not use this application to make healthcare decisions. Consult a qualified healthcare professional for medical concerns.

---

## 👩‍💻 Author

**Mousumi Badyakar**

- GitHub: [@MousumiBadyakar](https://github.com/MousumiBadyakar)

---

⭐ If you find this project interesting, consider giving the repository a star!