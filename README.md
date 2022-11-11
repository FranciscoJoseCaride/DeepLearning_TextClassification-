# DeepLearning_TextClassification-
A Deep Learning model (LSTM) for text classification.

Alguna vez tuve que armar un modelo que haga una clasificación binaria para distintos textos de un corpus. Era un modelo de Churn que clasificaba si un cliente iba a pedir la baja del servicio en un corto plazo en función de cómo había sido su atención ante un requerimiento para el sector de Seguros. Para clasificar programe una Red Neuronal LSTM en Pytorch, acá te dejo el código para que puedas adaptarla a tu proyecto.

El código toma como entrada un csv de dos columnas, una con el texto y la otra con la clasificación. Para usarla necesitas los datos y tunear la arquitectura e hiperparámetros según corresponda (cuando veas el código vas a ver que está bastante servido). También te dejo el requirements.txt para que instales la versión de Pytorch que uso.
