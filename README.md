# Baterias

Los multirrotores, o drones, son alimentados por baterías de polímeros de litio, normalmente llamadas LiPo, que son capaces de guardar y entregar una buena cantidad de potencia  En este repositorio iré actualizando la información relacionada con las baterías LiPo para tu quad, y también a elegirlas y a manejarlas con seguridad.

### Que es una LiPo o bateria para drone?

LiPo es un tipo de bateria basada en litio con polimero. Es lo más utilizado en drones ya que tienen un alta capacidad de carga relativa a su peso y permiten descargas de corriente muy altas.  

Todas las buenas baterías LiPo cuentan con un cableado principal y un cableado de balance, y llevan imporesas en su cubierta sus especificaciones: su capacidad expresada en miliamperios hora (mAh), su voltaje, bien indicado explícitamente o bien implícitamente si sólo se menciona el numero de celdas (1S, 2S, etc.) y su capacidad de descarga, esto es, la velocidad a la que es capaz de entregar la energía sin dañarse.

<img src="https://www.prometec.net/wp-content/uploads/2018/02/g2.jpg">

### Que es la C en las baterias LiPo?  

Se utiliza la C como una base para saber a que corriente puedes cargar/ descargar una bateria. O cuanta corriente te puede dar en algun punto la bateria cuando demandes energia de ella, dependiendo de la corriente de tu bateria. 

Una bateria de 4S de 1300mah, 70C que puede ser cargada a 5C y tiene una descarga pico de 140C  

Cuando cargas: Maxima carga 5 C, por lo tanto 1300mah x 5C = 6500mah = 6.5A por ello puedes cargar tu bateria a 6.5 Amperes  
Cuando le exiges energía: Como son 70C = 1300mah x 70C = 91,000 mah = 91A, por ello puedes consumir 91A de manera continua.  
Cuando le sobre exiges energía: Como son 140C = 1300mah x 140C mah = 182,000 mah = 182 A, por ello puedes consumir 182 A durante 3 segundos sin dañar tu batería.


### Que es el numero de celdas y que baterias son mas comunes?

Se denomina Bateria 1s a una bateria formada por una sola celda o Lipo. De la misma forma, una bateria formada por 4 celdas se denomina una Lipo 4s.
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

### Que es la resistencia interna?  

Cada una de las celdas de una batería tiene una resistencia interna, y ésta puede ser distinta en cada una de las celdas de la misma batería. La resistencia interna limita la máxima corriente que la batería LiPo puede producir. Cuando una batería LiPo envejece, o si ha sido usada muy intensivamente pierde fuerza o pegada.  

La resistencia interna no aparece en la hoja de especificaciones, porque cambia con el tiempo. La resistencia interna aumenta con:

El tiempo que tiene la batería  
Daños físicos (choques)  
Sobre- descargas  
Sobre-calentamientos  
Otros usos abusivos  
Puedes medir la IR con herramientas específicas. Algunos cargadores LiPo ofrecen esta función.  

### Como elegir una LiPo?  

Para elegir la mejor batería LiPo para tu dron, primero debes conocer tus necesidades, el voltaje deseado, y lo que sería la máxima corriente demandada.

Una vez has elegido tus motores y el tamaño de tus hélices, deberías ser capaz de encontrar datos online. Por ejemplo, voy a usar un motor determinado con hélices 5010×3 que a 100% de acelerador, según el gráfico de las especificaciones del motor, extrae 36,7A.

La máxima corriente extraída al 100% sería 36.7 x 4 = 146.8A al 100 % de acelerador. Si quisieras estar seguro podrías simplemente usar este número para escoger la batería, pero es mejor descontar un 10%, esto es: 146.8*0.9 =132.1A

Descontamos el 10% por lo siguiente:

En condiciones reales, la intensidad requerida es normalmente menor de la que arrojan los ensayos debido a el aire que se mueve. Puedes ver en la gráfica como la corriente es significativamente distinta entre el 90% y el 100% de acelerador. Te deberías preguntar cómo de a menudo pones el acelerador al 100%. Lo normal es volar entre un 40 y un 80% de gas y utilizar hasta el 100% sólo en cortas ráfagas de unos pocos segundos.

Por supuesto que hay otros componentes además de los motores que hacen uso de la batería, como el FC, RX. LED, FVP, etc. pero todo ello junto supone muy poco comparado con el consumo de los motores, así que simplemente se pueden despreciar en el cálculo, o si quisieras ser muy preciso, puedes añadir 1.5 A.

Ahora debemos definir la capacidad y el C Rating que necesitamos. Esta es una pequeña guía que te puede servir para hacerte a la idea. Relaciona la capacidad de la batería con el tamaño de las hélices:

6” – de 1500 mAh a 2200 mAh  
5” – de 1300 mAh a 1800 mAh  
4” – de 850 mAh a 1300 mAh  
3” – de 650 mAh a 1000 mAh  

Digamos que para un mini quad de 5”, si deseamos una construcción relativamente ligera, se usaría una batería de 1300 mAh (1,3 Ah). Por lo tanto, el C Rating en ráfaga requerido sería 132.1 / 1.3 =102 C. El C rating en continuo será la mitad de este número: 102 / 2 = 51C.

Es posible que quieras una batería con un C rating más alto si vas a volar constantemente abusando del acelerador.

Por supuesto que tienes que tener en cuenta qué tipo de vuelo piensas hacer y qué tiene más importancia para ti: el peso o la capacidad.

Los corredores de carreras muy quemados irán a por las baterías más ligeras posibles. Si te gusta el vuelo libre,y el peso no es la única prioridad y puedes preferir tener un mayor tiempo de vuelo.

### Como cargar una LiPo?  

Cargar bien las LiPo es importante para operar con ellas con seguridad y que las baterías tengan la longevidad adecuada, y un buen cargador no es barato. Por supuesto que hay cargadores baratos, mucho más baratos que lo que cuesta una sola batería, y te pueden servir perfectamente para salir del paso o cuando estás empezando, pero puedes mirarlo así: lo que no te gastes en el cargador ahora te lo vas a gastar más tarde reemplazando baterías.

**Tipos de carga**

**Carga balanceada**  
El cargador monitoriza el voltaje de cada celda y las puede cargar individualmente intentando mantener el mismo voltaje en todas las celdas. Este es el método recomendado y más seguro para cargar una batería LiPo.

**Carga directa (carga rápida)**  
La batería se carga a través de la línea principal y el cargador no chequea el voltaje de cada celda. Esto es normalmente más rápido pero puede producir que las cargas de las distintas celdas no esté equilibrada y que la batería no se cargue al 100 %.

**Carga de almacenaje**  
El cargador carga todas las celdas a la carga de almacenaje, que es entre 3.80 y 3.85 V

**Descarga**  
El cargador intenta “drenar” la batería LiPo muy lentamente, incluso más que la carga.
Por qué usar la carga balanceada?

Cada celda en una batería es un poco distinta, Incluso cuando la batería está descargada, puedes ver como los voltajes de las celdas son todos distintos.

Si fuéramos a cargar una batería no balanceada sin monitorizar el voltaje de cada celda, es muy probable que algunas de las celdas acabasen por debajo de los 4,2 V (no completamente cargadas) y lo que sería peor, algunas podrían acabar por encima de 4.2 V. Recuerda que si las baterías LiPo exceden los 4,2 V puede ser peligroso.

### Cuando es el momento de aterrizar?  

Una cuestión común de los principiantes es “Cuándo debería aterrizar?”

La respuesta es cuando el voltaje llegue a **3.5 o 3.6 voltios**. En las LiPo, no deberías usarlas hasta vaciarlas completamente. El voltaje no cae linealmente con la capacidad usada, sino que cae dramáticamente una vez se llega a los 3,5 ó 3,6 V. Si aún no has aterrizado, podrías dañar la batería al descargarla más de lo aconsejable.

<img src="https://www.prometec.net/wp-content/uploads/2018/02/g14.jpg">

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRomDEK0EUHX75dVJYgErrZsEnTyp6oYaivIw&amp;usqp=CAU">


#### Otros comentarios  

Cómo almacenar las baterías LiPo

Si no vas a usar las baterías en un periodo prolongado de tiempo (más de una semana, por ejemplo), deberías:

Cargarla de 3,8 a 3,85 V
Guardarlas en un lugar seguro (una bolsa LiPo o una caja metálica)
Guardarla a temperatura ambiente
Cuando una batería LiPo tiene entre 3,8 y 3,85 V, tiene aproximadamente entre el 40 y el 50% de su carga máxima, y éste es el estado más estable para una LiPo, Este es el estado de carga que traen todas las baterías LiPo al comprarlas, por eso vienen cargadas a medias.

Dejar una batería LiPo con plena carga durante un periodo prolongado además de ser inseguro podría perjudicar su rendimiento. Si puedes volar cada pocos días, esto no es problema para ti.

Bolsas LiPo

Las bolsas LiPo cuestan muy poco dinero y es una inversión importante para tus baterías LiPo. Se utilizan para cargarlas y almacenarlas. Están diseñadas para contener las llamas en caso de que una batería se ponga a arder.

Qué hacer con una batería LiPo sobre descargada

Cuando una batería LiPo se descarga completamente, las celdas se oxidan con el tiempo lo que provoca una reducción del rendimiento permanente. En cualquier caso, si se coge a tiempo, normalmente se puede salvar la batería sin dañar demasiado su comportamiento.

Los cargadores podrían no reconocer una LiPo sobre descargada si el voltaje es demasiado bajo. Lo mejor es desechar la batería y aunque hay un método para salvarla, (ya lo contaremos), debes saber que lo haces bajo tu propio riesgo.

Viajando con baterías LiPo

la mayoría de aerolíneas permiten que los pasajeros viajen con baterías LiPo en su equipaje de mano. Hay algunas cosas que conviene tener en cuenta:

Chequea con tu aerolínea lo concerniente a viajar con baterías LiPo
No metas las baterías en tu equipaje facturado
Viaja con tus baterías con carga de almacenaje
Pon cinta a los conectores y guárdalas en una bolsa LiPo
Nunca viajes con baterías dañadas
Qué hacer si una batería LiPo coge fuego?

Lo primero no entres en pánico.
Desconecta primero todas las conexiones.
La forma más efectiva y económica para apagar el fuego de una batería LiPo sería cubrirla con arena. Si ocurriese que no tienes ni gato ni arena en casa, métela en una caja metálica (la caja de galletas) y ciérrala para evitar que la combustión tenga oxígeno
Simplemente espera a que el fuego se apague y a que la batería se enfríe. No respires el humo.
NUNCA uses agua para apagar una LiPo en llamas.
Desechar las LiPo

Cuando retirar las baterías LiPo?

Las LiPo tienen un ciclo de vida limitado. Cada ves que las cargas y las descargas supone un ciclo. Con la acumulación de ciclos, la batería empezará a perder pegada (incrementar su resistencia interna) y capacidad. Se dice que una LiPo puede ser usada más de 300 ciclos si se cuida adecuadamente, pero no es extraño dañarlas antes. Lo mejor es reemplazarlas si son incapaces de mantener el 80% de su capacidad nominal.

Las baterías LiPo deben ser desechadas adecuadamente en contenedores adecuados. Nunca agujerees una batería LiPo porque arderá en llamas.

#### Fuentes de información 

[QuadMx Drones] http://www.quadmx.com/diccionario/  

[PROMETEC] https://www.prometec.net/elegir-bateria-lipo/

[Airbender_FPV] https://www.instagram.com/airbender_fpv/

