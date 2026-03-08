# ☕ RoastAI — Coffee Bean Classification with Deep Learning 🥉

**Authors:** Diego Aguiar, Mariana Sambucetti, Catalina Vaz Martins

**Course:** MIT Global Teaching Labs — AI Uruguay 2026 (Taller intensivo)

**Period:** January 12–23, 2026

**🏆 3rd Place — MIT GTL AI Uruguay 2026**

---

## 📋 Descripción

Deep learning project for classifying coffee bean roast levels using computer vision. The model uses a fine-tuned ResNet18 architecture trained on images of coffee beans to identify different roast levels. Grad-CAM visualizations are used to interpret what the model "sees" when making predictions.

*Proyecto de deep learning para clasificar el nivel de tostado de granos de café usando visión por computadora. El modelo utiliza una arquitectura ResNet18 con fine-tuning, entrenada con imágenes de granos de café. Se utilizan visualizaciones Grad-CAM para interpretar qué "ve" el modelo al hacer predicciones.*

---

## 🎯 Objetivos

- Build a CNN-based classifier for coffee bean roast levels
- Apply transfer learning with ResNet18
- Use Grad-CAM to visualize and interpret model decisions
- Evaluate model performance across different roast categories

---

## 📊 Datos

- **Source:** Coffee bean dataset (downloaded via Kaggle in the notebook)
- **Content:** Images of coffee beans at different roast levels
- **Note:** The dataset includes images taken by the team as well as external sources

---

## 📈 Resultados principales

| Metric | Value |
|--------|-------|
| Test Accuracy | **98.59%** |
| Correct predictions | 350/355 |
| Best epoch | 3 (early stopping at epoch 5) |
| Best validation loss | 0.0436 |

- **Model:** ResNet18 with transfer learning, trained for 5 epochs (early stopping with patience=2)
- **Roast levels classified:** Green (unroasted), Light, Medium, Dark
- **Grad-CAM analysis:** Center attention score of 0.507, confirming the model focuses on the beans themselves (color/texture) rather than backgrounds or borders
- **Training time:** ~1-2 hours on CPU, significantly faster on GPU (T4)
- **Duplicate detection:** Implemented hash-based duplicate detection to ensure data integrity between train/test sets

---

## 🛠️ Tecnologías

- Python (PyTorch, torchvision)
- ResNet18 (transfer learning)
- Grad-CAM (model interpretability)
- Scikit-learn (evaluation metrics)
- Matplotlib, Seaborn
- Google Colab (GPU T4)

---

## 📁 Estructura del proyecto

```
04-roast-ai/
├── RoastAI_Complete_Training_GradCAM_CPU_v4x2_epochs.ipynb    # Notebook principal
├── RoastAI_Complete_Training_GradCAM_CPU_v4x2_epochs.html     # Notebook en HTML (ver en navegador)
├── docs/
│   └── RoastAI_ProjectPresentation.pptx                        # Presentación del proyecto
└── README.md
```

---

## ▶️ Cómo ejecutar

1. Abrir `RoastAI_Complete_Training_GradCAM_CPU_v4x2_epochs.ipynb` en [Google Colab](https://colab.research.google.com)
2. Configurar la GPU: Runtime > Change runtime type > **T4 GPU**
3. Ejecutar las celdas en orden — el dataset se descarga automáticamente desde Kaggle
4. Tiempo estimado: 20–40 minutos dependiendo de la GPU

---

## 🔗 Volver al [Portfolio principal](../README.md)
