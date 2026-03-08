# 🎓 Potential Customers Prediction (ExtraaLearn)

**Author:** Mariana Sambucetti

**Course:** Data Science and Machine Learning: Making Data-Driven Decisions — MIT IDSS

**Module:** Classification and Hypothesis Testing

**Period:** October 30 – November 10, 2025

---

## 📋 Descripción

Supervised machine learning project for an EdTech company (ExtraaLearn) to predict which leads are most likely to convert into paying customers. The model helps optimize marketing spend by identifying high-potential leads.

*Proyecto de aprendizaje automático supervisado para una empresa EdTech (ExtraaLearn) para predecir qué leads tienen mayor probabilidad de convertirse en clientes. El modelo permite optimizar el gasto en marketing identificando leads de alto potencial.*

---

## 🎯 Objetivos

- Analyze the factors that drive lead conversion
- Build and compare classification models (Decision Tree, Random Forest)
- Identify the most important features for predicting customer conversion
- Provide actionable recommendations for the marketing team

---

## 📊 Datos

- **Source:** ExtraaLearn (simulated EdTech dataset)
- **Features:** Demographics, website interactions, time spent on site, profile completion, and other behavioral indicators
- **Target:** Whether the lead converted into a paid customer

---

## 📈 Resultados principales

**Models compared:** Decision Tree (baseline), Decision Tree (pruned/tuned), Random Forest (baseline), Random Forest (tuned)

**Best model: Random Forest (Tuned)**

| Metric | Decision Tree (Tuned) | Random Forest (Tuned) |
|--------|:----:|:----:|
| Train Accuracy | 0.79 | 0.84 |
| Test Accuracy | 0.79 | 0.83 |
| Precision (class 1) | 0.60 | 0.66 |
| Recall (class 1) | 0.90 | 0.86 |
| F1-score (class 1) | 0.72 | 0.75 |

- **Top predictive features:** Time spent on website, first interaction via website, page views per visit, age, and profile completion level.
- **Key insight:** Digital engagement variables are the strongest predictors of lead conversion. Leads who spend more time on the website and interact online are significantly more likely to convert.
- **Business impact:** The model enables proactive, data-driven lead management by identifying high-potential leads early in the funnel.

---

## 🛠️ Tecnologías

- Python (Pandas, NumPy)
- Scikit-learn (Random Forest, Decision Trees, classification metrics)
- Matplotlib, Seaborn
- Google Colab

---

## 📁 Estructura del proyecto

```
03-potential-customers/
├── M_Sambucetti_Learner_Notebook_Full_Code_Version_Potential_Customers_Prediction.ipynb    # Notebook principal
├── M_Sambucetti_Learner_Notebook_Full_Code_Version_Potential_Customers_Prediction.html     # Notebook en HTML
├── data/
│   └── 02_-_Dataset_-_Potential_Customers_Prediction.csv
└── README.md
```

---

## ▶️ Cómo ejecutar

1. Abrir `M_Sambucetti_Learner_Notebook_Full_Code_Version_Potential_Customers_Prediction.ipynb` en [Google Colab](https://colab.research.google.com)
2. Subir el archivo `data/02_-_Dataset_-_Potential_Customers_Prediction.csv` cuando se solicite
3. Ejecutar las celdas en orden

---

## 🔗 Volver al [Portfolio principal](../README.md)
