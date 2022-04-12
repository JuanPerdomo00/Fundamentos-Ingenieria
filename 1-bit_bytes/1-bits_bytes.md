
# Que son bits y bytes

### Sitema Binario
Es una técnica de numeración posicional con base 2, es decir cada una de las posiciones es una potencia del número dos y solo se utilizan ceros y unos como dígitos válidos.

### Bit
El bit es la unidad mínima de información, es un cero, o un uno. Es decir, tiene un impulso eléctrico o no lo tiene.

### Bytes
Un byte está compuesto por ocho bits, cada uno de estos bits tiene un valor posicional y corresponde a uno de los 8 primeros lugares de una tabla de sistema binario. Asi en conjunto el Bytes es el resultado de los 8 bits que lo componen.   
![](https://static.platzi.com/media/user_upload/imagen1-28893471-cab6-4355-931d-a64879100023-f4fe04e6-fb86-4667-b4e1-65094e1fd655.jpg)

De esta manera un byte puede tomar valores entre cero y 256. Cada uno de estos valores representa algún tipo específico de valor y para conocerlo, usamos la tabla ASCII. Cada archivo de texto, cada imagen, cada canción que está en nuestra computadora tiene un peso en bytes, que depende de la cantidad de información que contiene. 
![](https://static.platzi.com/media/user_upload/2018-12-19_14-59-36-9d0311c0-7788-4b3a-a1c0-eb9536f2895d-7c0299e8-a386-4343-9ce5-7f861ac7d9cb.jpg)

1 Bit: Es un 0 o un 1  
1 Byte: Son 8 Bit  
1 Kilobyte: Son 1024 Bytes  
1 Megabyte: Son 1024 Kilobytes  
1 Gigabyte: Son 1024 Megabytes  
1 Terabyte: Son 1024 Gigabytes

### Como Interpreta  los bytes las computadoras

Los computadores saben que cada 8 bits deben hacer una pausa porque los bytes siempre equivalen a 8 bits.

Existen bytes que son especiales que pueden significar órdenes específicas para el ordenador como pedir que arranque, o que ejecute una operación matemática.

Una imagen realmente es una grilla de píxeles y cada pixel representa a un byte cuyo número es igual a su color. Los emojis se añadieron a la tabla ASCII y cada emoji equivale a 2 bytes.

### Representaciones Globales con Bytes
Cuando se democratizó el acceso a la computación muchos países por obvias razones tenían idiomas diferentes con distintos caracteres y para solventar eso se creó el protocolo utf-8 que permitió que todo el mundo use la misma lista de caracteres.

Pero existían miles de caracteres que no cabían en 8 bits (utf-8) por lo que se diseñó utf-16 (2 bytes) y como sobro tanto espacio, pues a crear emojis.
