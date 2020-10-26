# HackTeamEc Detector de trafico malicioso
 El objetivo es clasificar el tráfico de red entre actividad normal o ataque con técnicas de Machine Learning.
 
 # Reto Detectando Trafico de red Malicioso usando Técnicas de Machine Learning
Se encuentra desarrollado en Python 3, se usa las siguientes librerías:
- Numpy
- Pandas
- Pycaret
- Matplotlib

## Notas
El entrenamiento se realiza sobre el dataset llamado Train.txt, para la validación se usa el dataset llamado Test.txt

El notebook desarrollado donde se entrena el modelo se llama Detectando_trafico_malicioso.ipynb. 

## Resultados
Se entrena un modelo LightGBM para realizar la clasificación binaria obteniendo los siguientes resultados:

- Accuracy en Train Set: 0.9999
- Accuracy en Test Set: 0.8828
