# DeepLearningPT
Entrega de la práctica del módulo de Deep-Learning
La versión correspondiente a la segunda entrega es la DeepLearningPTv03_02
### Objetivo
El objetivo de la práctica final del módulo de Deep Learning consiste en predecir el precio de habitaciones de AirBnb utilizando para ello todas las características disponibles en el dataset facilitado.
El propósito final es tener un sistema que se combinen distintos tipos de características (numéricas, texto, imágenes...) y que se explique cómo se ha realizado.

### Conjunto de datos

El conjunto de datos escogido es el del [link](https://public.opendatasoft.com/explore/dataset/airbnb-listings/export/?disjunctive.host_verifications&disjunctive.amenities&disjunctive.features&q=Madrid&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJ5QXhpcyI6Imhvc3RfbGlzdGluZ3NfY291bnQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20ifV0sInhBeGlzIjoiY2l0eSIsIm1heHBvaW50cyI6IiIsInRpbWVzY2FsZSI6IiIsInNvcnQiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiJyb29tX3R5cGUiLCJjb25maWciOnsiZGF0YXNldCI6ImFpcmJuYi1saXN0aW5ncyIsIm9wdGlvbnMiOnsiZGlzanVuY3RpdmUuaG9zdF92ZXJpZmljYXRpb25zIjp0cnVlLCJkaXNqdW5jdGl2ZS5hbWVuaXRpZXMiOnRydWUsImRpc2p1bmN0aXZlLmZlYXR1cmVzIjp0cnVlfX19XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D&location=16,41.38377,2.15774&basemap=jawg.streets), extraído de Airbnb mediante técnicas de scraping. Se ha va a utilizar el extract (“Only the 14780 selected records”), ya que minimiza el tiempo de ejecución y evita problemas de memoria en equipos con menos prestaciones.

### Tarea

Implementar un algoritmo predictivo que sea capaz de estimar el precio de las habitaciones utilizando para ello datos de distintos tipos y técnicas de Deep Learning (redes neuronales profundas).

Criterios a seguir:
- Características utilizadas como input del modelo.
- Arquitecturas probadas y experimentos realizados.
- Procesamiento de los datos para adecuarlos al modelo.
- Explicación de los pasos realizados.
- Limpieza del código.

### Desarrollo

Este proyecto ha sido desarrollado en Google Colab y este repositorio se ha creado directamente desde colab


### Nota

Proyecto realizado con Python 3 utilizando diferentes librerías, a destacar Pandas, Keras, Numpy, Sklearn

Los comentarios del proyecto se han ido anotando junto con el código.

Esta versión presentada es la tercera, se han hecho bastantes pruebas y se ha trabajado duro para poder ralizar un buen trabajo, pero al final ha salido menos de lo que esperaba. Pensaba que llegaría al final y conseguiría unos resultados aceptables, pero me he quedado a las puertas de poder combinar imágenes y datos en una regresión para poder hacer una predicción de precios de alquiler combinando las imágenes con las variables numéricas y categóricas.
Se ha hecho una revisión de la versión 3, donde se ha podido avanzar un poco más, pero si logros espectaculares.
