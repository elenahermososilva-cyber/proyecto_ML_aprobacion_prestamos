# Predicción de Riesgo Crediticio y Aprobación de Préstamos (`loan_status`)

Proyecto completo de **Machine Learning** desarrollado para el Máster de FP en Inteligencia Artificial y Big Data, orientado a predecir el riesgo de impago / aprobación de solicitudes de préstamo a partir del perfil socioeconómico, las condiciones del préstamo y el historial crediticio del solicitante.

## Enlaces y Entrega

* **Vídeo explicativo en YouTube (máx. 10 min):** `[https://youtu.be/jLEIvZD0Adg]`

---

## Estructura del Proyecto (7 Apartados)

1. **Obtención de datos:** origen del conjunto de datos (datos simulados/sintéticos de perfiles crediticios), contexto de generación y carga en estructura tabular (`pandas.DataFrame`) de forma reproducible.
2. **Descripción de los datos:** diccionario completo de variables (demográficas, financieras, del préstamo, historial crediticio y variable objetivo `loan_status`), tipos de datos y significado de cada categoría o unidad.
3. **Exploración y visualización de los datos (EDA):** análisis de valores nulos, duplicados, distribuciones, valores atípicos, correlaciones numéricas y visualizaciones de distinta tipología para detectar patrones y desbalanceo de clases.
4. **Exposición del objetivo:** definición formal del problema de clasificación binaria (`loan_status`), justificación basada en la exploración previa e implicaciones de los errores de clasificación en riesgo crediticio.
5. **Preparación de los datos para ML:** limpieza de registros anómalos/duplicados, imputación y tratamiento de nulos, codificación de variables categóricas, escalado y división estratificada *train/test* (`stratify=y`) evitando fuga de datos (*data leakage*).
6. **Entrenamiento del modelo y comprobación del rendimiento:** entrenamiento de un modelo *baseline* y modelos alternativos (p. ej., Regresión Logística, Árbol de Decisión / Random Forest / Gradient Boosting), evaluados con métricas adaptadas a clasificación desbalanceada (*Precision*, *Recall*, *F1-score*, matriz de confusión y *ROC-AUC*).
7. **Conclusiones:** síntesis de hallazgos clave, comparación de modelos, variables más influyentes, limitaciones del dataset simulado y líneas de mejora.

---

## Requisitos y Entorno

* **Python 3.10+** (ejecutable en **Google Colab** o entorno local).
* Bibliotecas habituales: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.

Instalación en entorno local (opcional):

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
