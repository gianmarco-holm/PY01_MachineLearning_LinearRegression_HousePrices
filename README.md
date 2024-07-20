# Modelo de Regresión Lineal de Precios de Casa

## Descripción del Proyecto

Este proyecto utiliza técnicas de machine learning, específicamente un modelo de regresión lineal, para predecir los precios de las casas en Boston utilizando el conjunto de datos del Boston Housing Dataset. El objetivo es desarrollar un modelo que pueda proporcionar estimaciones precisas del valor mediano de las viviendas ocupadas por sus propietarios basándose en diversas características socioeconómicas y ambientales del entorno.

## Contenido

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Contenido](#contenido)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Resultados](#resultados)
- [Conclusión](#conclusión)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Requisitos

- Python 3.x
- Librerías:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - plotly
  - scikit-learn
  - regressors
  - pickle

## Instalación

1. Puedes descargar el archivo y correrlo en Google Colab

## Uso
Carga los datos:

```python
# No es necesario descargar el archivo csv, con este codigo lo puedes cargar directamente
import pandas as pd

df = pd.read_csv('https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.data', header=None, sep='\s+')
df.columns = ['CRIM', 'ZN', 'INDUS', 'CHAS', 'NOX', 'RM', 'AGE', 'DIS', 'RAD', 'TAX', 'PTRATIO', 'B', 'LSTAT', 'MEDV']
df.head()
```

## Resultados
Los resultados del modelo se presentan mediante gráficos de dispersión, matrices de correlación y gráficos de residuos para visualizar la precisión y las predicciones del modelo.

## Conclusión
El modelo inicial tiene un coeficiente de determinación (R²) de aproximadamente 0.50, lo cual es aceptable para la predicción de gastos hospitalarios. Se recomienda seguir afinando el modelo inicial y probar con diferentes características y técnicas para mejorar la precisión.

## Contribuciones
Las contribuciones son bienvenidas. Para grandes cambios, por favor abre un issue primero para discutir lo que te gustaría cambiar.

