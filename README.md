# 🚗 Predicting Electric Vehicle Adoption using Driving Behaviour Analysis

## 📌 Project Overview

This project was completed in collaboration with **Motability Operations** to analyze vehicle telematics data and identify **Internal Combustion Engine (ICE)** users whose driving behaviour is compatible with **Electric Vehicle (EV)** adoption.

The project combines **unsupervised** and **supervised machine learning** techniques to classify drivers based on their travel patterns and support data-driven decision-making for EV transition.

---

## 🎯 Business Problem

Motability Operations aims to understand:

> **What percentage of ICE vehicle users have driving patterns similar to existing EV users?**

By identifying suitable ICE users, the organization can better support customers in transitioning to electric vehicles while considering practical driving behaviour.

---

## 📊 Dataset

The dataset contains approximately **200,000 vehicle trip records** with 11 features collected from vehicle telematics.

### Features

- Vehicle Identification ID
- Fuel Type
- Start Location
- End Location
- Average Speed
- Maximum Speed
- Trip Start Date & Time
- Trip End Date & Time
- Trip Length (Minutes)

---

## 🧹 Data Preparation

The raw dataset was preprocessed using Python.

### Data Cleaning

- Removed missing values
- Removed invalid records
- Standardized feature formats

### Feature Engineering

- Aggregated trips by vehicle
- Reverse geocoded locations
- Generated behavioural features
- Created datasets for cluster analysis
- Prepared training and testing datasets

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🤖 Machine Learning Workflow

### 1. Data Preprocessing

- Data Cleaning
- Feature Engineering
- Data Aggregation
- Train-Test Split

---

### 2. Unsupervised Learning

**K-Means Clustering**

The elbow method was used to determine the optimal number of clusters.

Purpose:

- Group vehicles with similar driving behaviour
- Identify low-speed and high-speed driving patterns

---

### 3. Feature Importance

A **Random Forest Classifier** was used to determine the most influential driving behaviour features before training the classification model.

---

### 4. Supervised Learning

An **MLP (Multi-Layer Perceptron) Classifier** was trained to classify driving behaviour based on engineered features.

---

### 5. Hybrid Approach

The final solution combines:

- K-Means Clustering
- Random Forest Feature Selection
- Multi-Layer Perceptron Classification

This hybrid approach improves behavioural segmentation before classification.

---

## 📈 Model Performance

| Model | Purpose |
|--------|---------|
| K-Means | Behaviour Clustering |
| Random Forest | Feature Importance & Classification |
| MLP Classifier | Driver Classification |

### Best Model

**Random Forest Classifier**

Accuracy:

**75%**

---

## 📌 Project Workflow

```

Vehicle Trip Data
│
├── Data Cleaning
├── Feature Engineering
├── Reverse Geocoding
├── Data Aggregation
│
├── K-Means Clustering
│
├── Random Forest
│
├── Feature Importance
│
└── MLP Classifier
│
└── Driver Classification

```

---

## 📊 Key Insights

- Driver behaviour can be grouped into distinct clusters.
- Speed and trip characteristics are important predictors of driving behaviour.
- Combining clustering with classification improves model performance.
- Machine learning can help identify ICE users with travel patterns compatible with EV ownership.

---

## 📁 Repository Structure

```

Motability-EV-Adoption-Prediction/

│
├── Motability_IGP_Final_MLP_Classifier.ipynb
├── Project_Report.pdf
├── Project_Presentation.pdf
├── data/
├── images/
├── README.md
└── requirements.txt

```

---

## 📚 Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Unsupervised Learning
- Supervised Learning
- Feature Selection
- Model Evaluation
- Business Problem Solving
- Data Visualization
- Machine Learning Pipeline

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation for improved model reliability
- XGBoost and LightGBM model comparison
- Deployment as an interactive web application
- Interactive dashboard using Power BI or Streamlit

---

## 👥 Team Project

This project was completed as part of an academic collaboration with **Motability Operations**, applying machine learning techniques to support data-driven insights for electric vehicle adoption.

---

## 📬 Contact

**Himanshukumar Prajapati**

- LinkedIn: *(Add your LinkedIn profile)*
- GitHub: *(Add your GitHub profile)*

---

⭐ If you found this project interesting, consider giving it a star.
