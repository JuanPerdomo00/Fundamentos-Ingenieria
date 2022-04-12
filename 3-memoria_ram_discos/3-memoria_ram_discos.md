
# Que es la memoria RAM y como funcionan los discos duros

Un **disco duro** (del inglés hard drive) es una pieza de hardware que almacena datos en un disco. El usuario puede acceder a estos datos para leer y escribir archivos.

## Cómo funciona un disco duro

En generaciones anteriores, un disco duro contenía un brazo mecánico, que se utilizaba para leer y escribir los datos en un disco de metal mientras este se encuentra girando, algo similar a los antiguos discos de vinilo. Cuando el brazo lee o escribe información, necesita moverse para acceder a las diferentes partes del disco.

Actualmente, existe una serie de nuevos discos, llamados de estado sólido (Solid State Drive) que ya no utilizan ningún tipo de brazo o disco giratorio y cuyo funcionamiento se asimila más al de la memoria RAM, sin que la información se pierda al apagar el equipo. Esto permite que la velocidad de lectura y escritura sea extremadamente rápida y el tiempo de vida útil del disco se extienda por no tener piezas móviles que puedan dañarse.

## Discos duros y memoria RAM

Los discos duros tradicionales son relativamente lentos porque deben posicionarse donde está el archivo almacenado y esto puede implicar que el brazo mecánico que mueve el cabezal se tome mucho tiempo en encontrar todos los _pedazos_ del archivo.

La memoria RAM es más rápida, ya que puede acceder a los datos almacenados de manera instantánea. La diferencia está en que los discos duros no son volátiles: guardan la información de manera persistente aunque se les quite el suministro de energía. La información de la memoria RAM, en cambio, se elimina en el momento en el que el computador se apaga.

Además, almacenan los archivos de manera secuencial: para almacenar un archivo, este se parte en varios pedacitos y se guarda la posición de cada uno de ellos, además de su ubicación, en el disco para poder leerlos secuencialmente.

## Sistemas de archivos de un disco

Para poder almacenar los archivos de forma adecuada, un disco duro necesita un sistema de archivos. Los sistemas de archivos son convenciones internas de los sistemas operativos para poder acceder a los archivos almacenados.

-   En Linux existe ext3 o ext4.
-   En Windows existía FAT16 o FAT32 (File Allocation Table), que fue reemplazado por NTFS (New Technology File System).
-   En Mac OSX el sistema de archivos se llamaba HFS (Hierarchical File System) pero ahora se llama AFS (Apple File System) en macOS Sierra.

Cuando abrimos un archivo, la CPU (Unidad Central de Procesamiento) se lo pide al disco duro y luego lo lleva a la memoria RAM para leerlo.

## Cómo funciona la memoria RAM

En la RAM están almacenados, de manera temporal, todos los programas y archivos que están en ejecución al momento de usar el computador. Si abrimos un archivo con el Bloc de Notas, por ejemplo, ambos deben estar cargados en la RAM. El CPU puede acceder a la memoria RAM a través de un índice compartido, es decir, un índice que indica en qué posiciones de memoria se encuentran qué partes de un archivo o proceso.

Los datos viajan a través de un conjunto de cables paralelos llamado bus de datos, que comunica la CPU con el disco duro y la RAM para permitir la transferencia de datos.

# GPUs, tarjetas de video y sonido
Sabemos cómo los archivos se cargan en memoria pero ¿Cómo veo en pantalla que el archivo se ha abierto?

Esto se logra gracias a la Graphic Processing Unit o GPU.

La CPU puede ejecutar cualquier proceso, incluido el dibujado en pantalla de ciertos datos. Pero no es ella quien se encarga, sino la GPU: **tarjetas especialmente fabricadas para realizar estas tareas**.

La comunicación entre la CPU y la GPU se realiza actualmente a través de un socket llamado PCI-Express.

Estas placas de vídeo tienen sus propias unidades o núcleos de procesamiento y su propia memoria RAM.

Lo que sucede es que la GPU divide la pantalla en una matriz y cada núcleo se encarga de dibujar una parte de esa matriz, para lograr una mejor performance.

Esto es mucho más rápido de lo que podría lograr la CPU sola ya que debería dibujar pixel por pixel ella sola.

![](https://static.platzi.com/media/files/archivos_624fac99-b611-4a4a-a578-914206c29626.png)

