## Cómo nos conectamos a Internet.

Tradicionalmente, pensamos que todas nuestras computadoras conectan a servidor en la nube y de ahí tenemos accesos a todos los servicios que nos ofrece internet. El procedimiento es más complejo, requiere de múltiples protocolos de transferencia y de hardware especializado que se encarga de transmitir los paquetes de datos involucrados en nuestra navegación. Veamos algunos de estos.

# Puertos y protocolos de red
Los **routers** son las puertas de enlace a diferentes redes. El router asigna IPs dentro de la red local y esa IP es única en esa red, hacia afuera todos los equipos se conectan con la IP que te da el proveedor de internet que tienes contratado.

Para asignar IPs un software se encarga de revisar la MAC address de cada dispositivo y asignarle una IP que esté disponible.

En los esquemas de red se crea un **red virtual** dentro de los sistemas operativos con un concepto interno que se le conoce como los **puertos**.

## ¿Qué son los puertos y los protocolos de Red?

**Un puerto es una puerta específica para un programa específico**.  
Cada solicitud que tú haces desde tu pc a través de una red trabaja con una ip y un puerto amigo, los puertos sirven para identificar los miles de servicios que maneja un SO, ejemplo: cuando tu entras a twitter desde tu navegador tú estás haciendo una petición a (102.102.20.02, ejemplo de ip de twitter), y el puerto 80, pero si quisieras subir un archivo por protocolo ftp sería 102.102.20.02 por puerto 21 que se ve reflejado como 102.102.20.02:21 y así sucesivamente cambia el puerto dependiendo del servicio. Los protocolos son como un lenguaje de comunicación entre máquinas y los puertos son autopistas donde los mensajes del protocolo pueden transitar.


# Qué es una dirección IP y el protocolo de Internet
¿Que es un IP?  
IP es la sigla de** Internet Protocol** y una dirección IP es un número único con el cual una computadora o un dispositivo se identifica cuando está conectada a una red con el protocolo IP.

Para definir una IP en nuestra computadora todo se dará a partir de la Mascara de Red ella será quien defina el estándar de números fijos y variables que tendrá nuestra ip.  
Todos los casos donde la Máscara tenga 255 simbolizará un fragmento de números fijos para la IP.

## Como se asigna un dirección IP

Recuerda que el Router es quien asigna una IP a nuestra computadora, a través de DHCP, esté debe tener una ip maestra que también lo identifique en la red, gracias a esta IP es que se permite que todos los dispositivos puedan intercambiar información y persistir en la red.  
Cada dirección IP está compuesta por 4 números separados por puntos y son una forma de comprender números más grandes y complejos. Las direcciones IP tienen una estructura que las convierten en privadas o públicas y que además hacen parte de la máscara de red y el getaway.

Las direcciones IP permiten que cada computador o dispositivo pueda conectarse al exterior, es decir a Internet, esto a través de tecnologías como NAT o Network Address Translation.

![](https://static.platzi.com/media/user_upload/ips_f6a4455a-6660-47e1-933e-a81ba037ef03-5987e6fd-a3e2-4f98-b319-1b69b099e3ba.jpg)

## Tipos de IP

La manera más fácil de ver si una ip es clase A, B o C es utilizando la máscara de red estándar y estas son:  
255.0.0.0 - clase A  
255.255.0.0 - clase B  
255.255.255.0 - clase C  
Pero, también existe el método de máscara de subred variable, la cual es muy útil para segmentar una red IP con máscara de red estándar

Todo sección representada por un 0 en la máscara de red va a ser destinada a host o clientes y las que están representadas por 255 son la destinada a la red


# Cables submarinos, antenas y satélites en Internet

La mayoría de personas imaginan que el acceso a Internet consiste en conexiones satelitales, lo cual es un error, pues los satélites están destinados solo para áreas remotas. Internet funciona a partir de cables que atraviesan diferentes lugares del mundo.

Ya sea en nuestra casa con nuestro modem, o en la calle con nuestro celular, lo que hacemos es conectarnos a alguna de las infraestructuras que nuestro proveedor de contenido mantiene para este sistema. De ahí, la conexión con diferentes puntos en el mundo a través de cables submarinos, que pueden ser de fibra óptica o cobre.

Estos cables pueden comenzar en una ciudad como Nueva York y terminar en Japón y aunque no parezca, la red de Internet un poco frágil pues los cables pueden romperse por diferentes causas, como las anclas de los barcos.

![](https://static.platzi.com/media/user_upload/world-submarine-cable-map-652c0888-f4bf-4a53-8a1e-323febc6bfbb.jpg)

## ¿Qué es la fibra optica?

La fibra óptica es un filamento de material dieléctrico, que permite la trasmisión de información a muy alta velocidad.

Estos cables son muy frágiles, y cuando alguno de ellos sufre una avería, es cuando se presentan problemas en el internet mundial.

![](https://static.platzi.com/media/user_upload/A86-285c8d27-0789-4ce5-88a8-259bc5ad20b8.jpg)


# Qué es un dominio, DNS o Domain Name System

## ¿Qué es un dominio?

Los dominios son los nombres únicos de los sitios web. Se utilizan porque son más fáciles de recordar que la **IP**. Por ejemplo es más fácil recordar [http://misitio.com](http://misitio.com) a 190.02.4.123


## ¿Qué es un DNS?

**DNS** significa Domine Name System. La manera de relacionar una IP con el dominio que le queremos asignar es mediante los DNS. Es decir, sirve como una base de datos. Nosotros podemos cambiar hacia donde apunta nuestro dominio, por ejemplo cuando queremos cambiar de proveedor de hosting. 

# Cómo los ISP hacen Quality of Service o QoS

## ¿Qué es el Quality of Service?

Cuando queremos conectarnos a puntos muy lejanos, por ejemplo, a un servidor ubicado en el otro lado del mundo para nuestro proveedor de internet es muy costoso. La manera que tiene los servidores para manejar estas situaciones es priorizando las conexiones usando un QoS (Quality of Service), que se traduce en que se regulan la velocidad, según el servicio al que quieres acceder.

Cuando la conexión se encuentra más cerca el proveedor de internet hace una red MAN (Metropolitan Area Network) y el costo de eso es casi nulo.

Hay una forma de burlar el QoS y simular una la conexión más cercana y esto es a través del CDN (Content Delivery Network).

## ¿Qué es CDN?  
Un CDN es un servicio que contiene una copia de contenido estático, como imágenes o videos, que estan alojados originalmente en otro servidor. Es como tener una copia más cercana de dicho material. Esto se traduce en mejores velocidades de navegación, a un menor costo.

![](https://static.platzi.com/media/user_upload/freddy%20image-56f8e6b8-679b-410a-a675-e5e702e0e3f8-62b2f539-1f96-48bf-824a-2fbeaf9cd27a.jpg)

# Cómo funciona la velocidad en internet
## ¿Qué velocidad de internet tengo?

La velocidad que nos ofrecen los proveedores de Internet, no es constante y muchos menos, es igual. Para entender nuestra velocidad de internet, es necesario conocer que esta depende de dos cosas. El ping y el ancho de banda.

## ¿Qué es el ancho de banda?

El ancho de banda es la capacidad máxima de información que se puede mandar. La mayoría de los **ISPs** (Internet Service Providers) nos venden ancho de banda en Mb. Es decir se mide en la cantidad de bits (no bytes) que transmite por segundo. Esta velocidad es variable y depende también del ping.

## ¿Qué es el ping?

La velocidad del internet se mide obteniendo el tiempo que le toma a la información viajar a través de un punto a otro en milisegundos. Por ejemplo entre tu computadora y el servidor. El ping tiene un límite y eso no va a cambiar nunca. Nuestra señal siempre va a viajar a una velocidad menor o igual a la velocidad de la luz, pero nunca podrá viajar más rápido. Puede ser un ping muy grande, cuando tenemos mucha distancia que recorrer.

Entonces, el ancho de banda es como el tamaño de un tubo de agua y el ping es la velocidad a la que puede viajar el agua.

![](https://static.platzi.com/media/files/bandwidth_df3967e6-f876-43da-b7af-f32d912ab1d1.png)