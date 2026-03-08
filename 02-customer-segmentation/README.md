# 🎯 Customer Personality Segmentation

**Author:** Mariana Sambucetti

**Course:** Data Science and Machine Learning: Making Data-Driven Decisions — MIT IDSS

**Module:** Making Sense of Unstructured Data

**Period:** October 7–20, 2025

---

## 📋 Descripción

Customer segmentation project using unsupervised machine learning techniques. The goal is to identify distinct customer groups based on personality traits, demographics, and purchasing behavior to enable targeted marketing strategies.

*Proyecto de segmentación de clientes utilizando técnicas de aprendizaje automático no supervisado. El objetivo es identificar grupos de clientes diferenciados según personalidad, demografía y comportamiento de compra.*

---

## 🎯 Objetivos

- Analyze customer demographics and purchasing patterns
- Apply dimensionality reduction techniques (PCA) to simplify the feature space
- Segment customers using K-Means clustering
- Profile each segment to derive actionable business insights

---

## 📊 Datos

- **Source:** Customer Personality Analysis dataset
- **Features:** Demographics (age, education, marital status, income), purchasing behavior (spending on various product categories), campaign response, and channel preferences

---

## 📈 Resultados principales

- **Model:** K-Means Clustering with k=4, after dimensionality reduction with PCA
- **Cluster selection:** Elbow method (k=4) + Silhouette analysis
- **4 customer segments identified:**
  - **Cluster 0 — Affluent Traditional Buyers:** High income, strong spending on wines, prefer in-store and catalog purchases. High loyalty potential.
  - **Cluster 1 — Budget-Conscious Families:** Lower income, larger families, minimal spending. Price-sensitive, respond to deals and promotions.
  - **Cluster 2 — High-Value Digital Shoppers:** High income, active across all purchase channels (web, catalog, store). Strong engagement with campaigns.
  - **Cluster 3 — Low-Engagement Customers:** Low income, minimal purchases across all categories. Require re-engagement strategies.
- **Business recommendations:** Loyalty programs for Cluster 0, targeted promotions for Cluster 1, omnichannel strategies for Cluster 2, and re-engagement campaigns for Cluster 3.

---

## 🛠️ Tecnologías

- Python (Pandas, NumPy)
- Scikit-learn (KMeans, PCA)
- Matplotlib, Seaborn
- Google Colab

---

## 📁 Estructura del proyecto

```
02-customer-segmentation/
├── M_Sambucetti_Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.ipynb    # Notebook principal
├── M_Sambucetti_Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.html     # Notebook en HTML
├── data/
│   └── 04_-_Dataset_-_Customer_Personality_Segmentation.csv
└── README.md
```

---

## ▶️ Cómo ejecutar

1. Abrir `M_Sambucetti_Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.ipynb` en [Google Colab](https://colab.research.google.com)
2. Subir el archivo `data/04_-_Dataset_-_Customer_Personality_Segmentation.csv` cuando se solicite
3. Ejecutar las celdas en orden

---

## 🔗 Volver al [Portfolio principal](../README.md)
