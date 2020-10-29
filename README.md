# Baterias

Los multirrotores, o drones, son alimentados por baterías de polímeros de litio, normalmente llamadas LiPo, que son capaces de guardar y entregar una buena cantidad de potencia  En este repositorio iré actualizando la información relacionada con las baterías LiPo para tu quad, y también a elegirlas y a manejarlas con seguridad.

- Que es una LiPo o bateria para drone?

LiPo es un tipo de bateria basada en litio con polimero. Es lo más utilizado en drones ya que tienen un alta capacidad de carga relativa a su peso y permiten descargas de corriente muy altas.  

Todas las buenas baterías LiPo cuentan con un cableado principal y un cableado de balance, y llevan imporesas en su cubierta sus especificaciones: su capacidad expresada en miliamperios hora (mAh), su voltaje, bien indicado explícitamente o bien implícitamente si sólo se menciona el numero de celdas (1S, 2S, etc.) y su capacidad de descarga, esto es, la velocidad a la que es capaz de entregar la energía sin dañarse.

<img src="https://www.prometec.net/wp-content/uploads/2018/02/g2.jpg">

- Que es la C en las baterias LiPo?  

Se utiliza la C como una base para saber a que corriente puedes cargar/ descargar una bateria. O cuanta corriente te puede dar en algun punto la bateria cuando demandes energia de ella, dependiendo de la corriente de tu bateria. 

Una bateria de 4S de 1300mah, 70C que puede ser cargada a 5C y tiene una descarga pico de 140C  

Cuando cargas: Maxima carga 5 C, por lo tanto 1300mah x 5C = 6500mah = 6.5A por ello puedes cargar tu bateria a 6.5 Amperes  
Cuando le exiges energía: Como son 70C = 1300mah x 70C = 91,000 mah = 91A, por ello puedes consumir 91A de manera continua.  
Cuando le sobre exiges energía: Como son 140C = 1300mah x 140C mah = 182,000 mah = 182 A, por ello puedes consumir 182 A durante 3 segundos sin dañar tu batería.


- Que es el numero de celdas?

Se denomina Bateria 1s a una bateria formada por una sola celda o Lipo. De la misma forma, una bateria formada por 4 celdas se denomina una Lipo 4s.

Por ejemplo:  


- Que baterias son mas comunes?

Las baterias mas comunes para los quads de 5" son las 4s, aunque una vez el piloto domina el vuelo se acostumbra a pasar a las 6s.
Las baterias 1-2S se utilizan en Tiny o quads mas pequeños.

Las baterías LiPo usada en RC están compuestas de celdas individuales conectadas en serie.   
Cada celda tiene un voltaje nominal de 3.7 V, por lo tanto el voltaje se define simplemente como la cantidad de celdas de la batería, también conocido como su numero “S”. así :

1S = 1 celda = 3.7V
2S = 2 celdas = 7.4V
3S = 3 celdas = 11.1V
4S = 4 celdas = 14.8V
5S = 5 celdas = 18.5V
6S = 6 celdas = 22.2V

Así, una batería 4S es una batería que proporciona 14,8 Voltios.

El voltaje afecta directamente la velocidad de los motores sin escobillas, así que usando baterías con más S puedes aumentar la velocidad del cuadracóptero si es que los ESC y el resto de la electrónica soporta este voltaje más alto.

Una batería con más celdas que otra pero la misma capacidad es más pesada simplemente porque contiene más celdas.

Para hacer una batería 4S de 1000 mAh podrías combinar 2 baterías 2S de 1000 mAh o también una 3S de 1000 mAh y una 1S de 1000 mAh.

El voltaje nominal de una LiPo es 3.7 V. Sin embargo éste no es el valor del voltaje cuando la batería está completamente cargada ni el que tiene cuando está descargada, sino un valor medio.

Las baterías LiPo están diseñadas para operar entre 3V y 4.2 V. Descargar una batería por debajo de 3 V le causaría una pérdida de rendimiento y posiblemente un daño irreparable. Cargarla a más de 4.2 V puede ser peligroso en incluso ocasionar fuego.

Es aconsejable no descargar las LiPo por debajo de 3.5V por motivos de salud de la batería. Por ejemplo, con una batería 3S, cuyo voltaje máximo es 12.6 V, deberías aterrizar antes de que el voltaje llegue a 10.5 V (es decir, 3,5 V por celda).

- Que es la resistencia interna?  

Cada una de las celdas de una batería tiene una resistencia interna, y ésta puede ser distinta en cada una de las celdas de la misma batería. La resistencia interna limita la máxima corriente que la batería LiPo puede producir. Cuando una batería LiPo envejece, o si ha sido usada muy intensivamente pierde fuerza o pegada.  

La resistencia interna no aparece en la hoja de especificaciones, porque cambia con el tiempo. La resistencia interna aumenta con:

El tiempo que tiene la batería  
Daños físicos (choques)  
Sobre- descargas  
Sobre-calentamientos  
Otros usos abusivos  
Puedes medir la IR con herramientas específicas. Algunos cargadores LiPo ofrecen esta función.  


#### Fuentes de información 

[QuadMx Drones] http://www.quadmx.com/diccionario/  

[PROMETEC] https://www.prometec.net/elegir-bateria-lipo/

[Airbender_FPV] https://www.instagram.com/airbender_fpv/

