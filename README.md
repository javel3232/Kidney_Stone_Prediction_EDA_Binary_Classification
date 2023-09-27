# *Proyecto Sustituto Modelos 1*

En el presente repositorio encontraras las fases que se llevaran a cabo para la construcción y ejecucion del proyecto.

En la carpeta llamada Fase-1 encontraras los archivos utilizados en el proyecto, asi como un archivo llamado README.md con las instrucciones especificas de como ejecutarlo correctamnete.

# *Contextualización y Descripción:*

## *1. Introducción*
Este Poyecto demuestra la implementación de dos modelos de machine learning: XGBoost y Regresión Logística, utilizando la biblioteca scikit-learn en Python. Los modelos se aplican a un conjunto de datos de análisis de orina. El objetivo es realizar un análisis predictivo para determinar la presencia de cálculos en el riñon.

## *2. Bibliotecas y Dependencias Requeridas*
- Versión de Python: 3.x
- Paquetes:
- Pandas 
- Matplotlib 
- NumPy 
- SciPy
- Scikit-learn
- XGBoost
- IPython

## *3. Preprocesamiento de Datos*

### *Carga y Preparación de Datos:*

- Se carga el conjunto de datos desde los archivos: train.csv y test.csv.
- Se elimina la columna 'id' ya que no es necesaria para el análisis.

### *Mapa de Correlaciones:*

- Se presenta la visualización  del mapa de correlaciones y de sus características en el conjunto de datos de entrenamiento.

## *4. Modelo XGBoost*

### *Entrenamiento del Modelo:*

- Se divide el conjunto de datos en conjuntos de entrenamiento y prueba.
- Se entrena un modelo XGBoost usando XGBClassifier.
- Se evalúa la precisión del modelo utilizando predicciones en el conjunto de prueba.

### *Ajuste de Hiperparámetros:*

- Se realiza el ajuste de hiperparámetros utilizando GridSearchCV para optimizar el modelo XGBoost.

## *5. Modelo de Regresión Logística*

### *Entrenamiento del Modelo:*

- Se realiza el escalado y procesamiento de las características usando StandardScaler y PolynomialFeatures.
- Se entrena un modelo de Regresión Logística con los mejores hiperparámetros obtenidos de GridSearchCV.

### *Evaluación del Modelo:*

- Se evalúa la precisión del modelo de Regresión Logística, la matriz de confusión y la puntuación ROC AUC.

## *6. Preparación para la Presentación*

### *Preparación de los Datos de Prueba:*

- Se procesan las características numéricas en el conjunto de datos de prueba de manera similar a los datos de entrenamiento.
