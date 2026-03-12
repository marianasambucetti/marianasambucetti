# 🚦 Análisis de Siniestros de Tránsito en Montevideo (2022)

**Autores:** Diego Aguiar, Andrea Aranda, Gerardo Gonzalez, Mariana Sambucetti

**Curso:** Fundamentos de Programación para Ciencia de Datos — UTEC (Especialización en Ciencia de Datos e IA)

**Período:** Marzo – Mayo 2025

---

## 📋 Descripción

Análisis exploratorio de datos (EDA) sobre los siniestros de tránsito ocurridos en Montevideo durante el año 2022. El proyecto busca identificar patrones temporales (días y horarios de mayor incidencia), zonas con mayor concentración de casos y los perfiles más frecuentes de las personas involucradas.

*Exploratory data analysis (EDA) on traffic accidents in Montevideo during 2022. The project identifies temporal patterns, high-risk areas, and profiles of people involved in traffic incidents.*

---

## 🎯 Objetivos

- Identificar los días de la semana y horas del día con mayor cantidad de siniestros
- Detectar las zonas de Montevideo con mayor concentración de casos
- Analizar los roles más frecuentes de las personas involucradas (conductor, pasajero, peatón)
- Evaluar el uso de elementos de protección (casco, cinturón)

---

## 📊 Dataset

- **Fuente:** Datos abiertos de la Intendencia de Montevideo (catálogo de datos abiertos)
- **Registros:** Personas lesionadas en siniestros de tránsito en Montevideo, año 2022
- **Variables principales:** Fecha, edad, rol, calle, zona, tipo de resultado, tipo de siniestro, uso de protección, sexo, hora, coordenadas geográficas

Ver el archivo [`data/metadata-siniestros.txt`](./data/metadata-siniestros.txt) para la descripción completa de cada variable.

---

## 📈 Hallazgos principales

- **Temporalidad:** Los miércoles son el día con más siniestros (1,303 casos). La tarde es la franja horaria más crítica, seguida por la noche.
- **Perfiles de riesgo:** La edad promedio de los involucrados es 35 años. Los hombres representan la mayor proporción de siniestros en todas las categorías. Los birrodados (motos) son el vehículo más involucrado (57.7% en zona urbana).
- **Zonas:** El 72.6% de los heridos leves ocurren en zona urbana. Los hotspots se concentran en Centro, Cordón, Tres Cruces y Villa Española.
- **Gravedad:** La gran mayoría son heridos leves (6,824 casos). Los fallecidos son 97 en total (66 en el lugar + 31 en centros de asistencia).
- **Protección:** Se detectó bajo uso de casco y cinturón, especialmente en motociclistas.
- **Técnicas estadísticas:** Tests de normalidad (Shapiro-Wilk, Kolmogorov-Smirnov), Chi-cuadrado de independencia, V de Cramér, Test ADF y KPSS para estacionariedad, análisis geoespacial con mapas interactivos.

---

## 🛠️ Tecnologías

- Python (Pandas, NumPy)
- Matplotlib, Seaborn, Plotly
- Google Colab

---

## 📁 Estructura del proyecto

```
01-siniestros-montevideo/
├── Entrega_04_Final.ipynb          # Notebook principal con el análisis completo
├── data/
│   ├── preprocesamiento_siniestros2022.csv   # Dataset preprocesado
│   └── metadata-siniestros.txt               # Descripción de variables
├── docs/
│   └── Ultimo-_Montevideo_se_mueve_24_05.pptx  # Presentación del proyecto
└── README.md
```

---

## ▶️ Cómo ejecutar

1. Abrir `Entrega_04_Final.ipynb` en [Google Colab](https://colab.research.google.com)
2. Subir el archivo `data/preprocesamiento_siniestros2022.csv` cuando se solicite
3. Ejecutar las celdas en orden

---

## 🔗 Volver al [Portfolio principal](../README.md)
