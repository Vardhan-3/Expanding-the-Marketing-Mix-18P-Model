# Expanding the Marketing Mix: 18P Model using ANT Colony Optimization

## 📌 Project Overview
This project presents a novel extension of the traditional marketing mix model by introducing an **18P Framework**, integrating **Probability** and **Prediction** into the existing 4P and 16P models.

The system leverages:
- 📊 Machine Learning (Logistic Regression, Random Forest, XGBoost)
- 🐜 Ant Colony Optimization (ACO)
- 📈 Predictive Analytics

to **predict consumer purchasing behavior** and optimize marketing strategies.

---

## 🎯 Objectives

- Extend marketing mix from **4P → 16P → 18P**
- Integrate **Probability & Prediction** into marketing decisions
- Apply **ACO for feature selection**
- Improve **consumer purchase prediction accuracy**
- Optimize **marketing ROI and targeting**

---

## 🧠 Key Contributions

- ✅ Proposed **18P Marketing Mix Model**
- ✅ Integrated **ACO for feature selection & optimization**
- ✅ Built **AI-driven predictive framework**
- ✅ Achieved improved accuracy using **XGBoost + ACO**
- ✅ Developed **data-driven marketing strategy system**

---

## 📊 Dataset Used

- **UCI Online Shoppers Purchasing Intention Dataset**
- 12,330 records
- 18 features:
  - Behavioral: Page views, session duration
  - Transactional: Revenue, page value
  - Demographic: Visitor type, region

---

## 🏗️ System Architecture

### 🔄 Workflow Pipeline

1. Data Collection  
2. Data Cleaning & Normalization  
3. Feature Selection using ACO  
4. Model Training (ML Models)  
5. Prediction & Evaluation  
6. Marketing Insights Generation  
7. Real-time Strategy Optimization  

---

## 🧩 Architecture Flow

- Input Data → Preprocessing → ACO Feature Selection → ML Models → Prediction → Decision System

---

## 🐜 Ant Colony Optimization (ACO)

### 📌 Why ACO?
- Handles high-dimensional data
- Reduces redundancy
- Improves model accuracy
- Avoids overfitting

---

### 📐 Feature Selection Probability Formula

P(i,j) ∝ (τᵢⱼ^α) * (ηᵢⱼ^β) * (1 - Rᵢⱼ)^γ

Where:
- τ → Pheromone level  
- η → Feature importance  
- R → Redundancy penalty  
- α, β, γ → Control parameters  

---

### 🔁 Pheromone Update Formula


τᵢⱼ = (1 - ρ) * τᵢⱼ + Δτᵢⱼ * Wᵢⱼ


---

### ⚖️ Feature Stability Weight


Wᵢⱼ = 1 / (1 + e^{-θFᵢⱼ})

## 📈 Results

| Model              | Accuracy Before | Accuracy After ACO | ROC-AUC |
|-------------------|---------------|--------------------|--------|
| Logistic Regression | 88.76%       | 90.12%            | 0.892  |
| Random Forest       | 91.31%       | 93.07%            | 0.918  |
| XGBoost            | 92.34%       | 94.85%            | 0.937  |

---

