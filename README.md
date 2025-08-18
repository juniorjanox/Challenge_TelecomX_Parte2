# 🚀 Telecom X – Parte 2: Predicción de Cancelación (Churn)

Este proyecto corresponde a la **segunda parte** del Challenge de Data Science **Telecom X**.  
En esta etapa, el objetivo es construir un **pipeline de Machine Learning** que permita predecir qué clientes tienen mayor probabilidad de cancelar sus servicios (*Churn Prediction*).

---

## 📌 Flujo del Proyecto

### 1️⃣ Extracción de datos tratados
- Se reutiliza el archivo **`telecom_tratado.csv`** obtenido en la **Parte 1** (datos limpios, corregidos y estandarizados).  

---

### 2️⃣ Preprocesamiento
- Limpieza final de valores faltantes o inconsistentes.  
- **Codificación** de variables categóricas (One-Hot Encoding / Label Encoding).  
- **Normalización / escalado** de variables numéricas para algoritmos sensibles a las magnitudes.  

---

### 3️⃣ Análisis de correlación y selección de variables
- Construcción de una **matriz de correlación**.  
- Identificación de las variables con mayor impacto en la **evasión de clientes (Churn)**.  

---

### 4️⃣ Entrenamiento de modelos
- Se entrenan al menos **2 clasificadores**:  
  - Regresión Logística  
  - Random Forest  
  - (Opcional) XGBoost u otro modelo de interés.  
- Validación cruzada para evaluar la robustez de los resultados.  

---

### 5️⃣ Evaluación de modelos
Se comparan los modelos con las siguientes métricas:  
- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1-score**  
- **ROC-AUC**  

---

### 6️⃣ Interpretación
- Análisis de la **importancia de las variables** en los modelos.  
- Identificación de **factores clave** que explican la evasión de clientes.  

---

### 7️⃣ Conclusión estratégica
- Se presentan **insights accionables para el negocio**.  
- Recomendaciones de **estrategias de retención**, basadas en los hallazgos de los modelos predictivos.  

---

## 📂 Estructura del Proyecto

