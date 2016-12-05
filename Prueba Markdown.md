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

 “Por sonido se entiende aquel fenómeno mecánico producido por una perturbación de un medio de transmisión (que generalmente es el aire) que tenga ciertas características para ser percibido por el oído humano.  Veamos un ejemplo. La vibración es transmitida en el aire por una cuerda vibrante (fig. 1.6). Esta se desplaza hacia adelante y hacia atrás, y durante este desplazamiento comprime las partículas de aire (moléculas) por un lado y las expande por el otro. Sucesivamente, el movimiento se invierte, y las moléculas que antes habían sido comprimidas se expanden, y viceversa. 

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

El segundo parámetro fundamental del sonido es la **amplitud**, la cual da informaciones sobre la variación de presión sonora y permite distinguir un sonido de fuerte intensidad de uno de intensidad débil. 
La presión sonora más débil que el oído es capaz de percibir es denominada **umbral de audición**, mientras que la presión sonora máxima que un oyente puede soportar se llama **umbral del dolor**, ya que si se sobrepasa este nivel, se producen una verdadera sensación de dolor físico y daños permanentes al órgano del oído. 
Si observamos el fenómeno representado en la figura 1.10, podemos ver que el valor máximo de la presión es denominado **amplitud de pico** de la onda sonora, mientras que el valor de la presión en un punto cualquiera es llamado **amplitud instantánea**. 
Cuando se indica la amplitud de un sonido, se hace referencia al valor de la amplitud de pico del mismo (fig. 1.10). 

Fig. 1.10: amplitud de un sonido

Por ejemplo, si indicamos una amplitud de pico = 1, tendremos una onda que parte de una amplitud instantánea = 0 (en el instante t0); después, la amplitud instantánea inicia a crecer, llega al máximo en el instante t1 (valor 1), después decrece hasta volver al valor 0 en el instante t2, sigue decreciendo y llega al mínimo en el instante t3 (-1), para después volver a subir hasta el valor 0 en el instante t4, y así sucesivamente. Esta es la representación de la amplitud de una onda sonora en función del tiempo. El proceso de digitalización transforma tal amplitud en una serie de números comprendidos entre 1 y -1. 

Los valores obtenidos de este modo pueden ser usados para representar gráficamente la forma de onda (fig. 1.11). La posición en la cual se encuentra el ciclo de onda en un determinado instante es llamada **fase**.
Ahondaremos en el concepto de fase en el parágrafo 2.1. 

Fig. 1.11: representación digital de una forma de onda.

Haciendo una confrontación con la onda real (es decir, con la sucesión de compresiones y expansiones de las moléculas de aire), podemos ver que la compresión corresponde a los números positivos y la expansión a los números negativos, mientras que el valor 0 indica una presión no perturbada (la ausencia de señal corresponde digitalmente a una secuencia de ceros). Convencionalmente los valores de amplitud son expresados en números con la coma, y varían entre 0 y 1: si indican 1 (o sea, el valor máximo) como valor de amplitud de pico, tendremos oscilaciones entre 1 y -1 (como en el ejemplo citado); si colocamos 0.5 como valor de amplitud de pico (o sea, la mitad de la amplitud máxima), tendremos oscilaciones entre 0.5 y -0.5, etc. (fig. 1.12). 

Fig. 1.12: dos sonidos de amplitud diferente. 

Si la amplitud de una onda dirigida hacia la tarjeta de sonido supera el valor máximo permitido por el sistema, y por ejemplo, oscila entre 1.2 y -1.2, todos los valores superiores a 1 o inferiores a -1 son posicionados, respectivamente, en el máximo y en el mínimo, esto es, son  “comprimidos” en los valores 1 y   -1 . De este modo la onda se deforma, y en consecuencia, el sonido resulta distorsionado  (fig. 1.13).

Fig. 1.13: forma de onda “comprimida”

En la mayor parte de programas también es posible indicar la amplitud en **dB SPL**: dB significa *decibel*, mientras que el acrónimo SPL significa Sound Pressure Level (nivel de presión sonora). La medición de la amplitud se refiere a la variación de la presión respecto al valor de presión normal, en cambio, el nivel de presión sonora es la *razón* entre la presión sonora en un determinado instante y un nivel de presión de referencia. En el audio digital, en general, el nivel de referencia es 0 dB SPL: se considera 0 dB SPL el máximo nivel de presión reproducible (correspondiente a la máxima amplitud), mientras que los valores inferiores son indicados con un número *negativo*. 

La amplitud = 1, por ejemplo, corresponde a 0 dB SPL, mientras que la amplitud = 0.5 corresponde, aproximadamente, a -6 dB; la amplitud = 0.25 corresponde, con una pequeña aproximación, a -12 dB, etc. De esto se deduce que una disminución de 6 dB corresponde a una reducción a la mitad de la amplitud, cualquiera que sea el valor de la misma. Este tipo de medición es muy útil, ya que puede ocurrir que tengamos que trabajar con sonidos de los cuales desconocemos la amplitud, pero ya sabemos que si queremos duplicarla, tendremos que aumentarla 6 dB. La medición en dB, al contrario de otras mediciones, no es absoluta sino relativa; es decir, nos permite medir y variar la razón entre dos niveles de presión sonora sin conocer los valores absolutos. 

A propósito de razón, otra regla útil es que, para reducir un cierto valor de amplitud un factor 10 (o sea, reducirlo a un décimo) tenemos que disminuirlo 20 dB; y naturalmente, para decuplicarlo, hay que aumentarlo 20 dB: de esto se deriva que un aumento de 40 dB aumenta 100 veces la amplitud; 60 dB la aumenta 1000, y así sucesivamente. 
Para una explicación más exhaustiva, ver “Detalles técnicos” al final del subtema 1.2. 
En la siguiente tabla se pueden observar algunos valores de amplitud comprendidos entre 0 y 1, junto con sus correspondientes valores de amplitud en dB SPL.

Tabla B: relación de las proporciones de amplitud contra los valores dB. 

Como ya hemos dicho, el decibel no es una cantidad absoluta, sino la expresión de la razón entre dos cantidades; por eso no existe un cero dB absoluto, pero sí es posible elegir el cero como punto de referencia respecto al cual medir un determinado nivel de presión sonora. A diferencia del audio digital, donde por lo general el 0 dB es el máximo valor reproducible en un sistema dado, en acústica se hace referencia a menudo al 0 dB como a un límite mínimo de la escala de la amplitud, indicando los valores superiores con un número *positivo*.

El siguiente listado ilustra, de manera aproximada, los niveles de presión sonora en dB de algunos fenómenos (medidos a 1 metro de distancia). Como se puede notar en este caso, el valor de 0 dB no representa el nivel de presión máxima (lo que sí ocurre en el caso del audio digital, en el cual los valores de amplitud por debajo del valor máximo se representan con valores negativos: -10 dB, -20 dB, etc); por el contrario, el 0 dB se indica como punto de referencia para referirse  “al sonido más débil perceptible”,  siendo todos los demás valores positivos. 

140	umbral del dolor

130	jet en fase de despegue

120 concierto de rock
110 *fff* de orquesta sinfónica
100 camión
90	calle ruidosa
80	tienda
70 	oficina
60 	conversación normal
50 	casa silenciosa
40	noche en el campo
30	crujido de hojas
20	viento	
10	viento débil
0	el sonido más débil perceptible

####   EJEMPLO INTERACTIVO 1B • AMPLITUD

Fig. 1.14: cuatro sonidos con amplitudes duplicadas progresivamente. 

Desde el punto de vista psicoacústico, la intensidad influencia también la percepción de la altura: sin entrar en detalles, será suficiente mencionar el hecho de que por encima de 2000 Hz, si aumentamos la intensidad de un sonido manteniendo estable la frecuencia, obtendremos una percepción de la altura tendencialmente alta; por el contrario, por debajo de 1000 Hz, entre más se aumente la intensidad, más decrecerá la altura percibida. Por otra parte, también la frecuencia influye en la percepción de la intensidad: la sensibilidad del oído humano disminuye en las frecuencias más altas, aumenta en las frecuencias medias y disminuye mucho en las bajas. Esto quiere decir que para tener la misma percepción  de intensidad, será necesaria una presión diversa según la frecuencia; o sea que será necesaria una mayor presión en las frecuencias bajas respecto a la necesaria para las frecuencias medias. Existe una representación gráfica de la sensibilidad del oído humano en las diferentes frecuencias en que este fenómeno ha sido analizado, teniendo en cuenta diferentes presiones sonoras. 

En la figura 1.15 vemos el diagrama de **curvas isofónicas**, es decir, de curvas de igual sensación sonora. En el eje vertical están presentes los niveles de presión en dB; en el eje horizontal están las frecuencias. Las curvas son medidas en **phon**e indican, en las diferentes frecuencias del campo audible, qué presión sonora es necesaria para producir en el oyente la misma sensación de intensidad. 

Fig. 1.15: diagrama de curvas isofónicas (ISO 226:2003)

La frecuencia de 1000 Hz ha sido elegida como frecuencia de referencia. En esta frecuencia, phon y dB coinciden (100 dB corresponden a la sensación de 100 phon, 80 dB a 80 phon, etc). Si seguimos la curva isofónica a 60 phon, por ejemplo, veremos que a 1000 Hz son necesarios 60 dB, pero entre más bajemos en frecuencia, más dB serán necesarios para que un oyente medio tenga la misma sensación sonora. 

