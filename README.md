Proyecto ML - Machine Learning - Beatriz Cartiel

---

### 📌 Problema / Problem Statement

**ES**: Las enfermedades cardíacas son una de las principales causas de muerte en el mundo. Este proyecto busca construir un modelo predictivo que, a partir de variables clínicas, permita identificar pacientes con riesgo de padecer enfermedad cardíaca.

**EN**: Heart disease is one of the leading causes of death worldwide. This project aims to build a predictive model that, based on clinical variables, can identify patients at risk of developing heart disease.

---

### 🗂️ Dataset

**ES**: El dataset utilizado es el **Cleveland Heart Disease dataset**, disponible públicamente en el repositorio de la UCI Machine Learning. Contiene variables como edad, sexo, presión arterial, colesterol, frecuencia cardíaca máxima, entre otras.

**Acceso al dataset**:  
https://archive.ics.uci.edu/dataset/45/heart+disease
Se incluye una muestra en `src/data_sample/heart_disease_cleveland_sample.csv`.

**EN**: The dataset used is the **Cleveland Heart Disease dataset**, publicly available in the UCI Machine Learning Repository. It includes variables such as age, sex, blood pressure, cholesterol, maximum heart rate, among others.

**Dataset access**:  
https://archive.ics.uci.edu/ml/datasets/heart+Disease  
A sample is included in `src/data_sample/heart_disease_cleveland_sample.csv`.

---

### 🧪 Solución Adoptada / Adopted Solution

**ES**:  
1. **EDA** para conocer los datos y su distribución.  
2. **Preprocesamiento**: limpieza, imputación de valores faltantes y escalado.  
3. **Selección de variables** mediante análisis de correlación y modelos base.  
4. **Entrenamiento** de modelos supervisados (Logistic Regression, Random Forest, etc.).  
5. **Evaluación** y selección del mejor modelo.  
6. **Exportación** del modelo final con `joblib`.

**EN**:  
1. **EDA** to understand data and distribution.  
2. **Preprocessing**: cleaning, missing value imputation, and scaling.  
3. **Feature selection** via correlation analysis and baseline models.  
4. **Training** of supervised models (Logistic Regression, Random Forest, etc.).  
5. **Evaluation** and selection of the best model.  
6. **Model export** using `joblib`.

---

### 🗃️ Estructura del repositorio / Repository Structure

```bash
ML_heart-disease/
│
├── src/
│   ├── data_sample/            # Muestra del dataset (sample data)
│   ├── img/                    # Imágenes usadas en el proyecto (project images)
│   ├── models/                 # Modelos entrenados guardados (trained models)
│   ├── notebooks/              # Notebooks de trabajo (working notebooks)
│   ├── results_notebook/      # Notebook final limpio y ejecutable (final clean notebook)
│ 
│
├── README.md
```

---

### 🎯 Objetivo del Proyecto / Project Goal

**ES**: Evaluar la capacidad de desarrollar un proyecto completo de Machine Learning, desde el planteamiento del problema hasta la creación del modelo final y su evaluación.

**EN**: Evaluate the ability to develop a complete Machine Learning project, from problem formulation to final model creation and evaluation.
## Uso

-- 
### 🚀 Como ejecutar este proyecto / How to Run the Project

**ES**:
1. Clona este repositorio:
   ```bash
   git clone https://github.com/Bcarti/ML_HeartDiseasePrediction/tree/main
   ```
2. Accede al directorio del proyecto:
   ```bash
   cd ML_HeartDiseasePrediction
   ```
3. Abre Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Ejecuta el archivo `main.ipynb ` desde la interfaz de Jupyter.

**EN**:

1. Clone this repository:
   ```bash
   git clone https://github.com/Bcarti/ML_HeartDiseasePrediction/tree/main
   ```
2. Navigate to the project directory:
   ```bash
   cd ML_HeartDiseasePrediction
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run the `main.ipynb` file from the Jupyter interface.

## Autor / Author

Beatriz Cartiel

