# 📝 Clasificación Automática de Quejas Financieras con DistilBERT

**Autores:** Yuri Biardo, Andrea Aranda, Mariana Sambucetti

**Curso:** Técnicas de Inteligencia Artificial: Deep Learning — UTEC (Especialización en Ciencia de Datos e IA)

**Profesora:** Bruna de Vargas

**Período:** 27 de enero – 26 de febrero de 2026

---

## 📋 Descripción

Clasificador automático de quejas financieras de consumidores utilizando fine-tuning de DistilBERT. El modelo toma el texto libre de una queja enviada al CFPB (Consumer Financial Protection Bureau) y la clasifica en una de 5 categorías de producto financiero. Se logró un **89.89% de accuracy** y **F1 macro de 0.87**.

*Automatic financial complaint classifier using DistilBERT fine-tuning. The model takes free-text consumer complaints submitted to the CFPB and classifies them into one of 5 financial product categories. Achieved **89.89% accuracy** and **0.87 macro F1-score**.*

---

## 🎯 Objetivos

- Construir un clasificador automático de texto para quejas financieras
- Aplicar fine-tuning de un modelo Transformer pre-entrenado (DistilBERT)
- Manejar el desbalance de clases mediante pesos ponderados (Weighted Trainer)
- Evaluar el modelo con métricas robustas (F1 macro, matriz de confusión)

---

## 📊 Resultados principales

| Métrica | Valor |
|---------|-------|
| Accuracy | 89.89% |
| F1 Macro | 0.87 |
| F1 Weighted | 0.90 |

| Categoría | Precision | Recall | F1-Score |
|-----------|-----------|--------|----------|
| credit_reporting | 0.93 | 0.95 | 0.94 |
| retail_banking | 0.89 | 0.90 | 0.89 |
| mortgages_and_loans | 0.88 | 0.83 | 0.85 |
| debt_collection | 0.85 | 0.80 | 0.82 |
| credit_card | 0.83 | 0.82 | 0.82 |

---

## 📊 Dataset

- **Fuente:** [Consumer Complaints Dataset for NLP](https://www.kaggle.com/datasets/shashwatwork/consume-complaints-dataset-fo-nlp) (Kaggle)
- **Registros:** 162,411 quejas reales del CFPB
- **Categorías:** credit_card, credit_reporting, debt_collection, mortgages_and_loans, retail_banking
- **Nota:** El dataset se descarga automáticamente desde Kaggle en el notebook (requiere API key)

---

## 🛠️ Tecnologías

- Python (PyTorch, Hugging Face Transformers)
- DistilBERT (distilbert-base-uncased)
- Scikit-learn (métricas de evaluación)
- Matplotlib, Seaborn
- Google Colab (GPU T4)

---

## 📁 Estructura del proyecto

```
05-clasificacion-quejas/
├── ProyectoFinal_Clasificacion_Quejas.ipynb     # Notebook principal
├── ProyectoFinal_Clasificacion_Quejas.html      # Notebook en HTML (ver en navegador)
├── requirements.txt                              # Dependencias
├── README.txt                                    # Instrucciones de ejecución
├── docs/
│   ├── Final_Project_Proposal.pdf                # Propuesta del proyecto
│   ├── Final_Project_Written_Report.pdf           # Reporte escrito completo
│   └── ProyectoFinal_PPT.pdf                     # Presentación
└── README.md
```

---

## ▶️ Cómo ejecutar

1. Abrir `ProyectoFinal_Clasificacion_Quejas.ipynb` en [Google Colab](https://colab.research.google.com)
2. Configurar la GPU: Runtime > Change runtime type > **T4 GPU**
3. Obtener credenciales de Kaggle: [kaggle.com](https://www.kaggle.com) > Profile > Settings > API > Create New Token
4. Ejecutar las celdas en orden — cuando se solicite, subir el archivo `kaggle.json`
5. Tiempo estimado: 30–40 minutos para entrenamiento completo

---

## 🔗 Volver al [Portfolio principal](../README.md)
