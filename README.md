# Prediccion-de-lluvia-en-Veracruz
Proyecto de Machine Learning para predecir precipitación en Veracruz

Este proyecto integra datos climáticos como la radiacion, emisiones contaminantes y registros históricos de precipitación para predecir días de lluvia en el estado de Veracruz.

## Herramientas utilizadas
- **Lenguaje:** Python (Google Colab)
- **Librerías:** Pandas, Scikit-learn, XGBoost, TensorFlow/Keras.

## Metodología
**Limpieza:** Interpolación lineal para completar datos faltantes de radiación y humedad.
**Ingeniería de Variables:** Creación de 'Lags' de radiación solar para capturar efectos del día anterior.
**Modelado:** Se entrenaron 4 modelos:

1. Regresión Logística

<img width="518" height="394" alt="image" src="https://github.com/user-attachments/assets/2c3854d9-2a40-491f-9979-5a51b4a1e02e" />

  
2.  Random Forest

<img width="518" height="393" alt="image" src="https://github.com/user-attachments/assets/a206189c-b454-4eae-b1eb-4f9fafb0804a" />

  
3.  XGBoost

<img width="518" height="393" alt="image" src="https://github.com/user-attachments/assets/3cab6577-faff-42db-860b-9d33a843cd7f" />

  
5.  Red Neuronal LSTM

<img width="499" height="374" alt="image" src="https://github.com/user-attachments/assets/5fd6ae95-af15-460e-b76b-58a6209490a2" />


Entrenamiento: 2011-2019 / Prueba: 2020-2021
