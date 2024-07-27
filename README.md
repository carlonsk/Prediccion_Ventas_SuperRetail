# Proyecto Series Temporales TodoVentas S.A.

## Descripción del Proyecto

Este proyecto tiene como objetivo predecir el nivel de ventas totales en el Reino Unido para el próximo mes. Utilizamos una muestra representativa de las ventas diarias por producto en los mercados más importantes durante los últimos años para construir y evaluar un modelo predictivo adecuado.

## Algoritmos Utilizados

- **SARIMAX**: Un modelo estadístico que combina la Autorregresión Integrada con la Media Móvil estacional, utilizado para capturar patrones y estacionalidades en datos de series temporales.
- **Prophet**: Un algoritmo desarrollado por Facebook para la descomposición y predicción de series temporales, particularmente efectivo para datos con fuertes tendencias y estacionalidades.
- **XGBoost**: Un algoritmo de aprendizaje automático basado en árboles de decisión, optimizado para velocidad y rendimiento, utilizado aquí para realizar predicciones basadas en características derivadas de los datos de series temporales.

## Librerías Utilizadas

- `pandas`, `numpy`: Para la manipulación y análisis de datos.
- `plotly`, `matplotlib`, `seaborn`: Para la visualización de datos.
- `prophet`: Para la implementación del modelo Prophet.
- `statsmodels`: Para la implementación del modelo SARIMAX y otras herramientas de análisis de series temporales.
- `xgboost`: Para la implementación del modelo XGBoost.
- `sklearn`: Para la evaluación del rendimiento del modelo y la preparación de datos.
