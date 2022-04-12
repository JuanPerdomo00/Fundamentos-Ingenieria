# Qué es el Modelo Cliente/Servidor

## ¿Cúal es la diferencia entre Frontend y Backend?

El frontend es la parte que se “ve” de un sitio. Incluye el texto, los botones, imágenes, animaciones etc. El backend son las acciones que se realizan cuando le damos clic al botón, son las conexiones a las bases de datos, y todo el código que hace que el sitio funcione.

## ¿Qué es el modelo cliente-servidor?

Se le llama modelo clinete-servidor a la relación que existe entre el frontend y el backend. El proceso de un modelo Cliente/Servidor es así:

-   Cliente (Navegador que lee HTML, CSS y JS)
    
-   Se envía una solicitud al Backend (Python, Go, Node, Java, etc.) a través de una URI
    
-   El Backend recibe la solicitud y toma decisiones en base a ella
    
-   El Backend consulta la Base de Datos (MySQL, Oracle, MongoDB, etc.) en caso de ser necesario
    
-   El Backend devuelve una respuesta que el navegador pueda leer, muchas veces datos en formato JSON
    
-   El Cliente recibe los datos JSON y los parsea para mostrarlos en HTML
    

A un grupo de tecnologías se les conoce como Stack

# Cómo funciona realmente un sitio web
Cuando escribimos una dirección web y damos clic, se ejecutan una serie de pasos, que no vemos pero que son responsables de que lleguemos o no al sitio elegido:

-   El navegador le hace una petición al sistema operativo para ver si tiene una versión en caché.
    
-   GET le pide al servidor los datos y se los envía a la IP del servidor.
    
-   El servidor responde con un número, como 200 (OK), 404 (No encontrado), 500 (error del servidor).
    
-   Se buscan los archivos que ya tenemos en caché.
    
-   Se empieza a desplegar el sitio web empezando por el texto.
    
-   Por último se solicitan las imágenes, videos y otros assets del sitio.
    

-Las cookies son datos guardados en variables y van ambos lados, tanto en el servidor como en el navegador. Las cookies pesan, entonces es importante limitarlas para no afectar la velocidad de las peticiones.

![](https://static.platzi.com/media/files/http_f00292a5-0e1e-4582-a6c8-1da21dafcac1.png)