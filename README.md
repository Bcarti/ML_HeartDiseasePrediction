# Proyecto ML - Machine Learning - Beatriz Cartiel



### Problema / Problem Statement

**ES**:
Las enfermedades cardíacas son una de las principales causas de mortalidad a nivel mundial. La detección temprana del riesgo cardiovascular permite intervenir antes de que se produzcan eventos graves. Este proyecto tiene como objetivo construir un modelo predictivo, basado en variables clínicas recogidas en pacientes, que permita identificar aquellos con mayor probabilidad de padecer enfermedad cardíaca.

**EN**:
Heart disease is one of the leading causes of mortality worldwide. Early detection of cardiovascular risk enables timely intervention and prevention of severe outcomes. This project aims to build a predictive model, using clinical variables collected from patients, to identify those at higher risk of developing heart disease.

---

### Dataset

**ES**: El dataset utilizado es el **Cleveland Heart Disease dataset**, disponible públicamente en el repositorio de la UCI Machine Learning. El conjunto contiene registros clínicos de pacientes, con variables como:

- **age**: Edad del paciente (en años).
- **sex**: Sexo del paciente (1 = hombre, 0 = mujer).
- **cp**: Tipo de dolor torácico (0 = típico anginoso, 1 = angina atípica, 2 = dolor no anginoso, 3 = asintomático).
- **trestbps**: Presión arterial en reposo al ser admitido en el hospital (mm Hg).
- **chol**: Colesterol sérico (mg/dl).
- **fbs**: Nivel de azúcar en sangre en ayunas (1 = >120 mg/dl, 0 = ≤120 mg/dl).
- **restecg**: Resultado del electrocardiograma en reposo (0 = normal, 1 = con anomalías ST-T, 2 = hipertrofia ventricular izquierda probable).
- **thalach**: Frecuencia cardíaca máxima alcanzada durante el ejercicio.
- **exang**: Angina inducida por el ejercicio (1 = sí, 0 = no).
- **oldpeak**: Depresión del segmento ST inducida por el ejercicio, en relación con el reposo.
- **slope**: Pendiente del segmento ST durante el esfuerzo (0 = ascendente, 1 = plano, 2 = descendente).
- **ca**: Número de vasos mayores (0–3) coloreados mediante fluoroscopia.
- **thal**: Resultado de la prueba de esfuerzo con talio (1 = normal, 2 = defecto fijo, 3 = defecto reversible).
- **target**: Diagnóstico final (0 = ausencia de enfermedad cardíaca, 1 = presencia de enfermedad).

**Acceso al dataset**:  
https://archive.ics.uci.edu/dataset/45/heart+disease
Se incluye una muestra en `src/data_sample/heart_disease_cleveland_sample.csv`.

**EN**: The dataset used is the **Cleveland Heart Disease dataset**, publicly available in the UCI Machine Learning Repository. The dataset contains clinical records of patients, with variables such as:

- **age**: Patient's age (in years).
- **sex**: Patient's sex (1 = male, 0 = female).
- **cp**: Type of chest pain (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic).
- **trestbps**: Resting blood pressure on hospital admission (mm Hg).
- **chol**: Serum cholesterol (mg/dl).
- **fbs**: Fasting blood sugar (1 = >120 mg/dl, 0 = ≤120 mg/dl).
- **restecg**: Resting electrocardiogram results (0 = normal, 1 = ST-T wave abnormality, 2 = probable left ventricular hypertrophy).
- **thalach**: Maximum heart rate achieved during exercise.
- **exang**: Exercise-induced angina (1 = yes, 0 = no).
- **oldpeak**: ST depression induced by exercise relative to rest.
- **slope**: Slope of the ST segment during exercise (0 = upsloping, 1 = flat, 2 = downsloping).
- **ca**: Number of major vessels (0–3) colored by fluoroscopy.
- **thal**: Thallium stress test result (1 = normal, 2 = fixed defect, 3 = reversible defect).
- **target**: Final diagnosis (0 = absence of heart disease, 1 = presence of heart disease).

**Dataset access**:  
https://archive.ics.uci.edu/ml/datasets/heart+Disease  
A sample is included in `src/data_sample/heart_disease_cleveland_sample.csv`.

---

### Solución Adoptada / Adopted Solution

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

### Estructura del repositorio / Repository Structure

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

### Objetivo del Proyecto / Project Goal

**ES**: Evaluar la capacidad de desarrollar un proyecto completo de Machine Learning, desde el planteamiento del problema hasta la creación del modelo final y su evaluación.

**EN**: Evaluate the ability to develop a complete Machine Learning project, from problem formulation to final model creation and evaluation.
## Uso

-- 
### Como ejecutar este proyecto / How to Run the Project

**ES**:
1. Clona este repositorio:
   ```bash
   git clone https://github.com/Bcarti/ML_HeartDiseasePrediction.git
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
   git clone https://github.com/Bcarti/ML_HeartDiseasePrediction.git
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


### Requisitos / Requirements

- Python >= 3.8
- Jupyter Notebook
- Bibliotecas: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, joblib


## Autor / Author

Beatriz Cartiel

