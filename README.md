# 🧠 Multiple Disease Prediction System

This project is a **Streamlit-based web application** that uses **machine learning models** to predict the likelihood of three major diseases based on user input:

* 🩺 **Diabetes**
* ❤️ **Heart Disease**
* 🗣️ **Parkinson's Disease**

It provides an accessible interface for early health screening and educational awareness, built using Python, Streamlit, and pre-trained models.


## 📌 Project Features

* 🔍 **Three Disease Prediction Modules**:

  * **Diabetes**: Based on health parameters like glucose level, BMI, age, etc.
  * **Heart Disease**: Uses features such as cholesterol, resting BP, ECG, and chest pain type.
  * **Parkinson’s**: Leverages voice measurements and motor control indicators.

* ⚙️ **Machine Learning Models**:

  * Trained with **scikit-learn** classifiers (Logistic Regression and SVM).
  * Models were serialized using **`joblib`** for deployment.

* 🖥️ **Streamlit Interface**:

  * Intuitive sidebar navigation
  * Real-time predictions with dynamic input sliders and fields
  * Deployed locally via `streamlit run`

* [Click here to run it live on server](https://disease-prediction-app-d8d7f9ce4286.herokuapp.com)

## 📁 Folder Structure

```
├── multiple_disease_pred.py       # Main Streamlit app
├── diabetes_model.pkl             # Trained model for diabetes
├── heart_model.pkl                # Trained model for heart disease
├── parkinsons_model.pkl           # Trained model for Parkinson's
├── requirements.txt               # Required Python packages
```


## 🚀 How to Run the App

1. **Clone the repository**:

```bash
git clone https://github.com/zooviee/multiple-disease-prediction.git
cd Multiple-Disease-Prediction-System
```

2. **Install dependencies**:

```bash
pip install -r requirements.txt
```

3. **Run the app**:

```bash
streamlit run multiple_disease_pred.py
```

4. Visit `http://localhost:8501` in your browser.


## 🧪 ML Pipeline Summary

* Preprocessing: StandardScaler used for normalization
* Model Selection: Accuracy, precision, and recall considered
* Training: Models trained on publicly available datasets
* Persistence: Saved using `joblib` for reuse during prediction


## 📊 Use Case

This app is designed for:

* Educational demonstrations
* Health-tech exploration
* Non-diagnostic early screening

> ⚠️ **Disclaimer**: This tool is **not a replacement for professional medical advice or diagnosis**. It’s built for **learning and awareness** purposes only.

