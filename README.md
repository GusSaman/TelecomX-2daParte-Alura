# Proyecto Telecom X - Parte 2: Predicción de Cancelación (Churn)

## Propósito
Predecir la cancelación de clientes (churn) en Telecom X para implementar estrategias de retención.

## Estructura
- `TelecomX_2daParte.ipynb`: Análisis y modelado.
- `datos_tratados.csv`: Datos limpios y transformados.
- `visualizaciones/` (opcional): Gráficos generados.

## Preparación de Datos
- Variables categóricas codificadas con one-hot.
- Verificación de nulos y duplicados.
- División en entrenamiento (70%) y prueba (30%).
- Normalización aplicada a modelos sensibles a escala.
- SMOTE aplicado para balancear clases.

## Modelos
- Regresión Logística y Random Forest.
- Métricas: Accuracy, Precision, Recall, F1-score y matriz de confusión.
- Variables más relevantes: tenure, Charges.Total, tipo de contrato, servicios adicionales.

## Insights
- Menor tiempo de permanencia y contratos cortos aumentan el churn.
- Clientes de mayor gasto y sin servicios adicionales presentan mayor riesgo.
- Visualizaciones: boxplots, violinplots, histogramas y matriz de correlación.

## Instrucciones
1. Instalar bibliotecas: `pandas`, `numpy`, `scikit-learn`, `imbalanced-learn`, `seaborn`, `matplotlib`.
2. Ejecutar el cuaderno `TelecomX_2daParte.ipynb` con `datos_tratados.csv` disponible.

