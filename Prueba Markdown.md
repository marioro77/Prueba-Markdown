# 1T
# INTRODUCCIÓN A LA SÍNTESIS DE SONIDO

## 1.1	SÍNTESIS Y PROCESAMIENTO DE SEÑALES
## 1.2	FRECUENCIA, AMPLITUD Y FORMA DE ONDA
## 1.3	VARIACIÓN DE FRECUENCIA Y AMPLITUD EN EL TIEMPO: ENVOLVENTES ACÚSTICOS Y GLISSANDI
## 1.4	RELACIÓN ENTRE FRECUENCIA E INTERVALO MUSICAL
## 1.5	BREVES NOTAS SOBRE EL TRABAJO CON  SONIDOS SINTETIZADOS.
## 1.6	BREVES NOTAS SOBRE EL PANNING.

# 1T
# INTRODUCCIÓN A LA SÍNTESIS DE SONIDO

## PRERREQUISITOS PARA EL CAPÍTULO

* Habilidades básicas de uso del computador (operar un computador, administrar archivos y directorios, tarjeta de sonido, etc.)

* Conocimiento mínimo de teoría musical (semitonos, octavas, tiempos, etc)

## OBJETIVOS DE APRENDIZAJE

### Conocimientos

* Aprender sobre las rutas de señal usadas en la síntesis de sonido y el procesamiento de señales

* Aprender sobre los principales parámetros del sonido y sus características

* Aprender sobre cómo altura e intensidad de sonido son codificados digitalmente

* Aprender sobre la relación entre intervalos musicales en diferentes sistemas de afinación

* Conocer diferentes formatos de archivos de audio

### Habilidades

* Ser capaz de identificar auditivamente cambios de frecuencia y amplitud y describir sus características

* Ser capaz de identificar las etapas del envolvente de un sonido o de un glissando

## CONTENIDOS

* \(teoría\) 

* (teoria)

## ACTIVIDADES

* Ejemplos interactivos

## PRUEBA

* Preguntas con respuestas cortas
* Escucha y análisis
*-----------------------*

## 1.2 FRECUENCIA, AMPLITUD Y FORMA DE ONDA

La frecuencia, la amplitud y la forma de onda son tres parámetros fundamentales del sonido. Cada uno de estos parámetros influye en la percepción sonora del oyente, en particular: 

	a)	en la posibilidad de distinguir un sonido grave de uno agudo (frecuencia).
	b)	en la posibilidad de distinguir un sonido de fuerte intensidad de uno de intensidad menor (amplitud).
	c)	en la posibilidad de distinguir timbres diferentes (forma de onda) 

Veamos una tabla (extraída de Bianchini, R., 2003) de las correspondencias entre características físicas del sonido, parámetros musicales y sensaciones sonoras. 



TABLA A: correspondencia entre características del sonido, parámetros musicales y sensación sonora. 

### FRECUENCIA

La **frecuencia** es el parámetro físico que determina la altura de un sonido, es decir, la característica que permite distinguir un sonido agudo de uno grave. La gama de frecuencias audibles del ser humano se extiende, aproximadamente, de 20 a 20000 Hertz, es decir, de 20 a 20000 ciclos por segundo (explicaremos de qué se trata más adelante): por debajo de la mínima frecuencia perceptible, 20 ciclos por segundo, se encuentran los infrasonidos; por encima de la frecuencia máxima, 20000 ciclos por segundo, se encuentran los ultrasonidos.  Si nos concentramos en el campo de las frecuencias audibles, o sea, de los sonidos, podremos afirmar que entre mayor sea la frecuencia, más agudo será el sonido. 

¿Pero qué se entiende por Hertz o “ciclos por segundo”? Para responder a esta pregunta, hacemos referencia a la definición de sonido de Riccardo Bianchini:  

 “Por sonido se entiende aquel fenómeno mecánico producido por una perturbación de un medio de transmisión (generalmente el aire) que tenga ciertas características para ser percibido por el oído humano.  Veamos un ejemplo. La vibración es transmitida en el aire por una cuerda vibrante (fig. 1.6). Esta se desplaza hacia adelante y hacia atrás, y durante este desplazamiento comprime las partículas de aire (moléculas) por un lado y las expande por el otro. Sucesivamente, el movimiento se invierte, y las moléculas que antes habían sido comprimidas se expanden, y viceversa. 

 Las compresiones y las expansiones (es decir, las perturbaciones del aire que inicialmente estaba en estado de quietud) se propagan después, con una cierta velocidad, a través del aire alrededor *en todas las direcciones*, dando lugar a *ondas esféricas*. Inicialmente, la densidad de las moléculas de aire es constante, o sea que en cada unidad de volumen (por ejemplo en un cm³) hay el mismo número de moléculas. 

Fig. 1.6: vibración de una cuerda

Esta densidad puede ser expresada por un valor de *presión*. Cuando el aire es perturbado, el valor de presión ya no es constante sino que varía de punto a punto: aumenta donde las moléculas son comprimidas, disminuye donde las moléculas son expandidas (fig. 1.7). 

Fig. 1.7: compresión y rarefacción de las moléculas de aire

El fenómeno puede ser estudiado tanto desde el punto de vista del espacio (observando el valor de la presión en diferentes puntos en un determinado instante) como desde el punto de vista del tiempo (midiendo el valor de la presión en un mismo punto en función del tiempo). Por ejemplo, si imaginamos que nos encontramos en un determinado punto, asistiremos a una sucesión de compresiones y expansiones del aire (fig. 1.8). 

Fig. 1.8: representación gráfica de compresión y rarefacción

En el instante t-1, o sea antes del instante t0, la presión del aire está en su valor normal, dado que la perturbación todavía no ha llegado a nuestro punto de observación. En el instante t0 la perturbación llega a nuestro punto de observación, inicia a crecer, llega al máximo en el instante t1, luego decrece hasta volver al valor normal en el instante t2, sigue decreciendo y llega al valor mínimo en el instante t3, para después volver a subir hasta el valor normal en el instante t4, y así sucesivamente. 

Hasta aquí se ha descrito un **ciclo** del fenómeno. Si esto se repite siempre del mismo modo, se dice que el fenómeno es periódico.   El tiempo necesario para que se complete un ciclo es denominado **periodo**,   se indica con el símbolo T y se mide en segundos (s) o en milisegundos (ms). Lo inverso de periodo, es decir, el número de ciclos que se completan en un segundo, es denominado *frecuencia*, y se mide en Hertz (Hz)  o ciclos por segundo (cps). 

Si por ejemplo una onda sonora tiene un periodo T= 0.01 s (1/100 de segundo), su frecuencia será:
 1/T = 1/0.01 = 100 Hz (o 100 ciclos por segundo)”(ibidem).

Escuchemos los sonidos del ejemplo interactivo  número 1A, observando la figura 1.9: podemos constatar que, entre mayor sea el número de ciclos por segundo (Hz), más agudo será el sonido correspondiente.

Fig. 1.9: cuatro sonidos de frecuencia diferente.  

#### EJEMPLO INTERACTIVO 1A • FRECUENCIA 					                                    

Desde el momento en que se propaga en el espacio, una onda tiene una *longitud* que es inversamente proporcional a su frecuencia. Aclaremos este concepto: la velocidad del sonido en el aire (o sea, la velocidad con la cual se propagan las ondas sonoras a partir de la fuente) es de aproximadamente 344 metros por segundo.   Esto significa que una hipotética onda de 1 Hz tendría una longitud de aproximadamente 344 metros, ya que cuando ha completado un ciclo ha pasado un segundo, y en este tiempo se ha extendido en el espacio por una longitud de 344 metros. Una onda de 10 Hz, en cambio, en un segundo realiza 10 ciclos que se disponen en el espacio de 344 metros, ocupando cada uno 34.4 metros, es decir un décimo del espacio total. Siguiendo el mismo razonamiento, una onda de 100 Hz mide 3.44 metros: como se puede ver, aumentando la frecuencia disminuye la longitud, y por lo tanto, como ya se ha dicho, las dos magnitudes son inversamente proporcionales.  

### AMPLITUD