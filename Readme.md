# Healthcare Prediction Hub

An AI powered Healthcare Prediction Hub that predicts multiple diseases using Machine Learning and Deep Learning models through a single web application.

The project combines image based and clinical data prediction into one platform, enabling users to analyze different diseases efficiently. 


# Features

- Brain Tumor Prediction using MRI Images (CNN)
- Asthma Emergency Department Risk Prediction
- Breast Cancer Prediction
- Heart Disease Prediction
- Chronic Kidney Disease Prediction
- Thyroid Disease Prediction
- Image Upload Support
- Clinical Data Prediction
- Deep Learning Model Integration


# Technologies Used

## Programming Language

- Python 3.9+

## Machine Learning

- Scikit-learn
- TensorFlow
- Keras

## Deep Learning

- Convolutional Neural Network (CNN)

## Data Processing

- Pandas
- NumPy

## Image Processing

- OpenCV

## Web Framework

- Streamlit

## Model Storage

- Joblib


# Machine Learning Models Used

|     Disease     |            Algorithm            |
|-----------------|---------------------------------|
| Brain Tumor     | CNN                             |
| Asthma ED Risk  | ANN, Naive Bayes                |
| Breast Cancer   | KNN, SVM, Random Forest, MLP    |
| Heart Disease   | ANN, Naive Bayes, Random Forest |
| Chronic Kidney  | Naive Bayes, Random Forest      |
| Thyroid Disease | ANN, SVM, Naive Bayes           |


# Workflow

```
User Input
      │
      ▼
Disease Selection
      │
      ▼
Data Validation
      │
      ▼
Data Preprocessing
      │
      ▼
Load Trained Model
      │
      ▼
Prediction
      │
      ▼
Display Result
```


# Project Structure

```
Healthcare_Prediction_Hub/
│
├── asthmaproject/
│   ├── ANN.py
│   ├── NB.py
│   ├── streamlit_app.py
│   ├── enhance_dataset.py
│   ├── load_ann_model.py
│   ├── asthma/
│   ├── annmodel/
│   └── requirements.txt
│
├── brainproject/
│   ├── app.py
│   ├── brain_cancer/
│   ├── model/
│   ├── accuracy_results.txt
│   └── requirements.txt
│
├── breastproject/
│   ├── models/
│   ├── streamlit_app.py
│   └── dataset/
│
├── heartproject/
│   ├── models/
│   ├── streamlit_app.py
│   └── dataset/
│
├── kidneyproject/
│   ├── models/
│   ├── streamlit_app.py
│   └── dataset/
│
├── thyroidproject/
│   ├── models/
│   ├── streamlit_app.py
│   └── dataset/
│
├── datasets/
│
└── requirements.txt
```


# Installation

## 1. Clone Repository

```bash
git clone repo link here
```

## 2. Navigate into Project

```bash
cd Healthcare_Prediction_Hub
```

## 3. Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### macOS/Linux

```bash
python3 -m venv venv

source venv/bin/activate
```

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

If each disease module contains its own requirements file, install them as needed.

Example:

```bash
pip install -r asthmaproject/requirements.txt
```

# Running the Application

Navigate to the required disease module.

Example:

```bash
cd asthmaproject
```

Run Streamlit

```bash
streamlit run streamlit_app.py
```

For Brain Tumor

```bash
cd brainproject

streamlit run app.py
```

# Applications

- Hospitals
- Clinics
- Healthcare Professionals
- Medical Researchers
- Educational Demonstrations

