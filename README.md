# 🩺 Predicción de Diabetes con Regresión Logística

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-6.x-blue?logo=jupyter)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-blue?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-blue?logo=matplotlib)
![Polars](https://img.shields.io/badge/Polars-1.x-blue?logo=polars)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue?logo=Kaggle)

Un proyecto simple de Machine Learning que utiliza **Regresión Logística** para predecir si un paciente tiene diabetes, usando el conjunto de datos clásico de Kaggle: [`diabetes.csv`](https://www.kaggle.com/datasets/mathchi/diabetes-data-set).

---

## 🧪 Objetivo

> Predecir la presencia de diabetes en pacientes a partir de factores médicos como glucosa, edad, IMC, presión arterial, etc.

---

## 📁 Estructura del código

### ✅ 1. Carga y análisis de datos

🔹 Lectura del archivo CSV con **Polars**  
🔹 Exploración y preparación de los datos

### ✅ 2. Entrenamiento del modelo

🤖 Entrenamiento con **LogisticRegression** de `scikit-learn`  
📊 División en datos de entrenamiento y prueba

### ✅ 3. Predicción y evaluación

🔍 Precisión del modelo  
📈 Gráfico comparando datos reales vs predicciones

### ✅ 4. Predicción de nuevos pacientes

🧍 Introducción manual de un paciente  
📉 Predicción binaria (`0` o `1`) y probabilidad

---

## 📊 Visualizaciones

El código genera un gráfico doble con `matplotlib`:

- 🔵 Datos reales (entrenamiento)
- 🟠 Predicciones del modelo (prueba)

Utilizando variables clave como **Glucosa** e **IMC** para facilitar la interpretación visual.

---

## 🛠️ Herramientas usadas

| Librería       | Propósito                       |
| -------------- | ------------------------------- |
| `polars`       | Manipulación eficiente de datos |
| `scikit-learn` | Modelado y predicción           |
| `matplotlib`   | Visualización de datos          |

---

## 🚀 Cómo usarlo

1. Clonar el repositorio
2. Abrí el archivo `logistica.ipynb`
3. Instalar las dependencias
4. Ejecutar cada celda paso a paso

---

## 💡 Autor

Creado por [Alexis Albarenga](https://github.com/Alexis217) – Para el trabajo practico de Python para ciencia de datos.

---
