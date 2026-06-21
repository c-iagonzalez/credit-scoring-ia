# 🏦 Proyecto de Credit Scoring con Machine Learning

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar datos relacionados con riesgo crediticio para identificar patrones asociados al incumplimiento de obligaciones financieras y comprender los factores que influyen en la capacidad de pago de los clientes.

A través de técnicas de análisis exploratorio de datos (EDA), se busca generar insights de negocio y preparar la información para el desarrollo de modelos predictivos de riesgo crediticio.

---

## 🎯 Problema de Negocio

Las entidades financieras deben evaluar continuamente el riesgo asociado a la aprobación de créditos.

Una evaluación inadecuada puede generar:

* Incremento en la tasa de incumplimiento.
* Pérdidas financieras.
* Asignación ineficiente de capital.
* Deterioro de indicadores de cartera.

Este proyecto busca apoyar la toma de decisiones mediante el análisis de variables relevantes para la evaluación del riesgo crediticio.

---

## 🚀 Objetivos

* Analizar la calidad y estructura de los datos.
* Identificar valores faltantes y posibles inconsistencias.
* Explorar distribuciones y comportamiento de variables.
* Detectar valores atípicos (outliers).
* Analizar correlaciones entre variables.
* Obtener insights accionables para negocio.
* Preparar los datos para futuros modelos de Machine Learning.

---

## 🛠️ Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* Git
* GitHub

---

## 📂 Estructura del Proyecto

```text
credit-scoring-ia/
│
├── notebooks/
│   └── 01_data_exploration.ipynb
│
├── dashboard/
│
├── images/
│
├── src/
│
├── README.md
│
└── .gitignore
```

---

## 📊 Análisis Exploratorio de Datos

Durante esta fase se realizaron actividades como:

* Revisión de estructura y tipología de datos.
* Análisis descriptivo de variables.
* Identificación de valores nulos.
* Evaluación de distribuciones estadísticas.
* Exploración de relaciones entre variables.
* Preparación de información para modelado.

---

## 💡 Principales Hallazgos

Los hallazgos obtenidos durante el análisis permitirán:

* Comprender el perfil de riesgo de los clientes.
* Identificar variables con mayor capacidad predictiva.
* Mejorar futuros modelos de aprobación crediticia.
* Generar recomendaciones basadas en datos.

---

## 🔮 Próximas Fases

Este proyecto continuará evolucionando con:

* Ingeniería de características (Feature Engineering).
* Modelos de clasificación.
* Regresión Logística.
* Random Forest.
* XGBoost.
* Optimización de hiperparámetros.
* Interpretabilidad del modelo mediante SHAP.

---

## 👨‍💻 Autor

**Carlos Alberto González**

Business Intelligence | Data Analytics | Machine Learning

### Conecta conmigo

* LinkedIn: *[(https://www.linkedin.com/in/carlos-gonzalez-980b44167/)*
* GitHub: https://github.com/c-iagonzalez

---

## ⭐ Objetivo del Proyecto

Este proyecto forma parte de mi portafolio profesional orientado a analítica avanzada, ciencia de datos e inteligencia artificial aplicada a problemas de negocio.

## 📈 Resultados Principales

### Distribución de la Variable Objetivo

Análisis de la proporción entre clientes que incumplen y aquellos que cumplen con sus obligaciones financieras.
![Distribución Target](images/Proporción%200-No%20incumplen%20vs%201-Incumplem.png)

---
### Desempeño del Modelo XGBoost

El modelo XGBoost presentó el mejor desempeño entre los algoritmos evaluados para la clasificación del riesgo crediticio.

![XGBoost ROC AUC](images/ROC%20AUC%20-%20XGBoost.png)

---
### Modelo Ganador
Comparación final y desempeño del modelo seleccionado.
![Modelo Ganador](images/Modelo%20ganador%20ROC%20-%20AUC%20-%20XGBoost.png)

---
### Variables Más Influyentes
Identificación de las variables con mayor impacto en la predicción del incumplimiento crediticio.
![Feature Importance](images/Variables%20de%20mayor%20influencia.png)

## 🏆 Resultados del Modelo
| Métrica           | Modelo Ganador               |
| ----------------- | ---------------------------- |
| Algoritmo         | XGBoost                      |
| Problema          | Clasificación Binaria        |
| Objetivo          | Predicción de Incumplimiento |
| Métrica Principal | ROC-AUC                      |
| Variable Objetivo | TARGET                       |
| Caso de Uso       | Credit Scoring               |

El modelo desarrollado permite identificar clientes con mayor probabilidad de incumplimiento, facilitando la toma de decisiones en procesos de aprobación y gestión de riesgo crediticio.


