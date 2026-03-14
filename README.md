# Clasificación de calidad de ramen

Este proyecto aplica técnicas de Machine Learning para clasificar productos de ramen como **buenos** o **malos** a partir de sus características.

El objetivo del proyecto es practicar el flujo completo de trabajo de un proyecto de Machine Learning, incluyendo exploración de datos, preprocesamiento, ingeniería de características, entrenamiento de modelos y evaluación de desempeño.

---

## Dataset

El conjunto de datos contiene información sobre distintos productos de ramen, incluyendo variables como:

* Marca
* País de origen
* Estilo
* Puntuación de evaluación

A partir de la puntuación original se construyó una variable objetivo binaria (`is_good`) que clasifica los productos como:

* **Buenos**
* **Malos**

---

## Flujo de trabajo del proyecto

El proyecto sigue una estructura estándar de desarrollo en Machine Learning.

### 1. Exploración y limpieza de datos

* Inspección inicial del dataset
* Identificación y tratamiento de valores faltantes
* Selección y preparación de variables relevantes

### 2. Ingeniería de características

* Creación de la variable objetivo binaria
* Codificación de variables categóricas utilizando distintos métodos:

  * One-Hot Encoding
  * Binary Encoding
  * Target Encoding

### 3. Preprocesamiento de datos

* Estandarización de variables numéricas
* División del dataset en conjuntos de entrenamiento y prueba utilizando muestreo estratificado

### 4. Entrenamiento de modelos

Se implementaron dos modelos de clasificación:

* Regresión Logística
* Support Vector Machine (SVM)

Para mejorar el desempeño de los modelos se realizó búsqueda de hiperparámetros utilizando **GridSearchCV**.

### 5. Evaluación de modelos

El rendimiento de los modelos fue evaluado mediante distintas métricas de clasificación:

* Precisión
* Recall
* F1-score
* Área bajo la curva ROC (ROC-AUC)
* Curva ROC comparativa

---

## Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Estructura del repositorio

```
.
├── Modulo5-Desafio4.ipynb
└── README.md
```

---

## Objetivos de aprendizaje

Este proyecto demuestra experiencia práctica en:

* Preparación y limpieza de datos
* Codificación de variables categóricas
* Entrenamiento de modelos de clasificación
* Ajuste de hiperparámetros
* Evaluación comparativa de modelos

---

## Autor

Rubén Darío
Estudiante de Ingeniería Informática con interés en Machine Learning, Estadística y Ciencia de Datos.
