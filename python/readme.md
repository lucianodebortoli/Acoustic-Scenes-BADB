# CNN Model

## Base de datos:
* TUT 2017
* TUT 2018

Se seleccionan y combinan algunas de las clases de las bases de datos para formar una nueva base de datos "COMBI".

<img src="images/combi.png" height="350">

## Descriptores
A partir de cada audio se extrae un espectrograma en escala Mel, con 128 componentes de frecuencia. <br/>
Cada espectrograma tiene 128 componentes temporales que representan 2.7 segundos de audio. <br/>
El espectrograma se obtiene calculando una FFT cada 1024 muestras de audio,
utilizando ventanas hanning de 2048 muestras de tamaño. <br/>

## Modelo:
Para el modelo clasificador se utiliza una arquitectura de tipo CNN.

<img src="images/model.png" height="350">

<img src="images/augment.png">

<img src="images/training.png" height="350">

<img src="images/confusion.png">
