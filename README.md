[![en](https://img.shields.io/badge/lang-English-blue.svg)](https://github.com/jfmartinez1554/InvoiceClassificator/blob/main/README.eng.md)

# Clasificador de facturas

## Autores:
- Laura Sánchez (https://github.com/LauraSanchez9585)
- Juan S. Gallego (https://github.com/jsgallego)
- Juan F. Martínez (https://github.com/jfmartinez1554)

Este repositorio contiene la iteración final de un modelo de Machine Learning para la Clasificación de facturas. También puede ser usado cómo punto de partida para la clasificación de documentos.

## Preparación de los datos:

Para usar este repositorio de forma efectiva se necesita de un dataset que contenga:
- Doc type: tipo de imagen, si es o no es factura.(en donde 1 es factura, 0 si no)
- Issuer: comercio que expide la factura, en caso de que la imagen sea una no-factura, este campo será nulo.
- Total: valor total de la compra, en caso de que la imagen sea una no-factura este campo será nulo.
- Items: Artículos comprados en cada factura, en caso de que la imagen sea una no-factura este campo será nulo.
- Text: texto de la imagen, este campo se completó mediante el OCR AWS Textract.
- Categoria: Categoría de comercio a la que pertenece la imágen, como: hogar, alimentación, tecnología, etc. En caso de que una imagen sea no-factura la categoría será: no-factura.

## Cómo usarlo:

En este repositorio encontrará un conjunto de notebooks que permitieron el desarrollo del ejercicio, la nomenclatura de estos esta conformada por un número y su nombre; en donde el número corresponde al orden en que debe ser corrido y el nombre corresponde a el proceso que va a desarrollar en el notebook.

- Actualice las variables globales presentes en el Notebook "Utils".
- Actualice los diccionarios y funciones utilitarias del notebook "Utils" dependiendo de su lenguaje y/o preferencias.
- Usando el notebook de "ClassificationModels" entrene y exporte tódos losmodelos necesarios para la clasificación (TFIDF Vectorizer, SVM y NN) y finalmente compare el desempeño de los modelos para su dataset.
- Usando los modelos exportados previamente puede usar los notebooks "UsageExample" o "FinalAlgorithm" para probar la clasificación de sus propios documentos!




