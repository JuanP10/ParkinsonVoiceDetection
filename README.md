# ParkinsonVoiceDetection

Este repositorio contiene un proyecto de análisis y clasificación de datos vocales para la detección de la enfermedad de Parkinson. Utilizando medidas específicas de calidad vocal y procesamiento de señales, el objetivo es encontrar patrones en los datos que permitan predecir la presencia de Parkinson. Este proyecto está diseñado en JupyterLab para una exploración y documentación detallada de los datos y análisis.

## Descripción del Proyecto
La enfermedad de Parkinson es un trastorno neurológico progresivo que afecta la coordinación y el control motor de los músculos. Uno de los primeros síntomas puede observarse en los cambios en la calidad vocal. Este proyecto utiliza un conjunto de datos que contiene mediciones de calidad de voz, tales como **MDVP: Jitter**, **MDVP: Shimmer**, **NHR** y **HNR**, que son indicadores clave en el diagnóstico de Parkinson.

### Objetivo
- Realizar un análisis exploratorio y visualización de datos para comprender los patrones asociados a la presencia de Parkinson.
- Implementar modelos de clasificación que ayuden a predecir la presencia de la enfermedad.

## Datos
El dataset ha sido obtenido de la [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). Incluye 195 registros de datos de voz, con:
- 147 registros de personas con Parkinson.
- 48 registros de personas sin Parkinson.

Cada registro contiene 22 características vocales y una etiqueta de estado (`status`) que indica si la persona tiene Parkinson (1) o no (0).

## Requerimientos
Este proyecto requiere **Python 3** y las siguientes bibliotecas:
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`
- `jupyterlab`

Instálalas ejecutando:
pip install pandas seaborn matplotlib scikit-learn jupyterlab



