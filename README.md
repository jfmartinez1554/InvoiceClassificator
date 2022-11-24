[![en](https://img.shields.io/badge/lang-English-blue.svg)](https://github.com/jfmartinez1554/InvoiceClassificator/blob/main/README.eng.md)

# Clasificador de facturas

## Autores:
- Laura Sánchez (https://github.com/LauraSanchez9585)
- Juan S. Gallego (https://github.com/jsgallego)
- Juan F. Martínez (https://github.com/jfmartinez1554)

Esyte repositorio contiene la iteración final de un modelo de Machine Learning para la Clasificación de facturas. También puede ser usado cómo punto de partida para la clasificación de documentos.

## Preparación de los datos:

- Para usar este repositorio de forma efectiva se necesita de un dataset que contenga al menos la categoría que se desea clasificar y el texto bruto extraído de las facturas y/o documentos. En nuestro caso extraímos el texto de las facturas mediante un OCR y posteriormente agrupamos todos los textos con las categorías de cada factura en un archivo .csv que posteriormente usamos cómo nuestro dataset.

## Cómo usarlo:

- Actualice las variables globales presentes en el Notebook "Utils".
- Actualice los diccionarios y funciones utilitarias del notebook "Utils" dependiendo de su lenguaje y/o preferencias.
- Usando el notebook de "ClassificationModels" entrene y exporte tódos losmodelos necesarios para la clasificación (TFIDF Vectorizer, SVM y NN) y finalmente compare el desempeño de los modelos para su dataset.
- Usando los modelos exportados previamente puede usar los notebooks "UsageExample" o "FinalAlgorithm" para probar la clasificación de sus propios documentos!




