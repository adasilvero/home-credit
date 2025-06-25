# home-credit

Este repositorio contiene el desarrollo de un modelo de predicción de morosidad utilizando el dataset de Home Credit Default Risk.

## Contenido
- `home_credit_v1.ipynb`: Primera versión del modelo. Este nodelo incluye la ejecución del algoritmo de regresion lineal y random forest. Se nota visiblemente que los datos estan desbalanseados al ver la matiz de confusión
- `home_credit_DEA.ipynb`: Versión anterior eliminada por el nombre del archivo.
  
## Objetivo
Predecir la probabilidad de morosidad de un cliente, analizando variables financieras y del historial de crédito.

## Tecnologías usadas
- Python
- Pandas
- Scikit-learn
- XGBoost

## Cómo usar
1. Clona este repositorio
2. Abre el notebook `home_credit_v1.ipynb`
3. Asegúrate de tener las siguientes dependencias instaladas:

```bash
pip install pandas numpy scikit-learn xgboost
