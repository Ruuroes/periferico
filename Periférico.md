# **Switch.**

## (Conmutador o dispositivo de red).

El switch es es el dispositivo digital lógico de interconexión de equipos que opera en la capa de enlace de datos del modelo OSI. 

Su función es interconectar dos o más host de manera similar a los puentes de red, pasando datos de un segmento a otro.


![Foto del Switch] (https://www.desordena.es/multimedia/imagenes_med/1912_2147.JPG)
## Funcionamiento del conmutador.


Los conmutadores poseen la capacidad de almacenar las direcciones de red de la capa 2 de los dispositivos alcanzables a través de cada uno de sus puertos. Por ejemplo, un equipo conectado directamente a un puerto de un conmutador provoca que el conmutador almacene su dirección MAC. Esto permite que, a diferencia de los concentradores, la información dirigida a un dispositivo vaya desde el puerto origen al puerto de destino.


En el caso de conectar dos conmutadores o un conmutador y un concentrador, cada conmutador aprenderá las direcciones MAC de los dispositivos accesibles por sus puertos, por lo tanto en el puerto de interconexión se almacenan las MAC de los dispositivos del otro conmutador.

## **Clasificación del switch.**


### Según el método de direccionamiento de las tramas utilizadas.

Hay tres tipos:


* **Store and forward:** Los conmutadores Store-and-Forward guardan cada trama en un búfer antes del intercambio de información hacia el puerto de salida.Este método asegura operaciones sin error y aumenta la confianza de la red. Pero el tiempo utilizado para guardar y chequear cada trama añade un tiempo de demora importante al procesamiento de las mismas.
  

* **Cut-through:** Los conmutadores cut-through fueron diseñados para reducir la latencia.El problema de este tipo de switch es que no detecta tramas corruptas.
  
* **Adaptive cut-through:** Son los conmutadores que procesan tramas en el modo adaptativo y son compatibles tanto con store-and-forward como con cut-through. 

### Según la segmentación de las subredes.

 Conmutadores de capa dos: 

 Son los conmutadores tradicionales, que funcionan como puentes multi-puertos. Su principal finalidad es dividir una LAN en múltiples dominios de colisión, o en los casos de las redes en anillo, segmentar la LAN en diversos anillos.

 Conmutadores de capa 3:
 Son los conmutadores que, además de las funciones tradicionales de la capa 2, incorporan algunas funciones de enrutamiento, como por ejemplo la validación de la integridad del cableado de la capa 3 por checksum y soporte a los protocolos de routing tradicionales (RIP, OSPF, etc)

Los conmutadores de capa 3 soportan también la definición de redes virtuales (VLAN), y según modelos posibilitan la comunicación entre las diversas VLAN sin la necesidad de utilizar un router externo.

Conmutadores de capa 4:
Están en el mercado hace poco tiempo y hay una controversia en relación con la adecuada clasificación de estos equipos. 

Básicamente, incorporan a las funcionalidades de un switch de capa 3 la habilidad de implementar la políticas y filtros a partir de informaciones de capa 4 o superiores.
