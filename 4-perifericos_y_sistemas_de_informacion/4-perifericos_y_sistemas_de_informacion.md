## ¿Cuáles son los periféricos de una computadora?

Las impresoras, micrófonos, unidades de disco externo y en general todos aquellos dispositivos que se pueden quitar y poner de una computadora para aumentar sus funciones, son considerados como dispositivos periféricos.

Estos sistemas no deben tener acceso total a nuestra computadora, necesitan diferentes niveles de permisos. Estos permisos se organizan en niveles de anillos.

-   **Primer anillo - Kernel**: El Kernel lo podemos entender como la capa más profunda de nuestro S.O. por lo tanto tiene acceso completo a archivos, drivers, programas, etc…Igual que cualquier otro proceso, se carga en la RAM como la cualidad de que es lo primero en cargar.En esta capa también viven programas capaces de encriptar y desencriptar información, de tal forma que ninguna otra capa del S.O. tenga acceso a ellos.
-   **Segundo anillo - Drivers**: Como se ha dicho antes los drivers son código que se encargan de interpretar las señales del hardware y establecer una comunicación con el software del PC. Estos primeros drivers pertenecen a piezas de hardware bastante importantes como la pantalla, el teclado, el mouse, etc.
-   **Tercer anillo - Más Drivers**: Otra capa de drivers carga en un tercer “puesto” en la RAM. Dado que están más alejados del Kernel, tienen menos permisos y privilegios que los drivers del segundo anillo. Dado que mediante los drivers de este anillo, se comunican en su mayoría las Apps, es necesario que primero los drivers del tercer anillo pidan permisos a los del segundo anillo para luego así comunicarse con el hardware.
-   **Cuarto anillo - Apps**: Finalmente en la última capa del modelo de anillos del S.O. nos encontramos con las apps, que se cargan en la RAM para ejecutar procesos. Sin embargo, a diferencia de los otros anillos no tienen ningún tipo de acceso directo al hardware del PC. Es relevante tener en cuenta que así debería ser, pues de lo contrario cualquier Software escrito por terceros tendría la capacidad de acceder casi por completo al PC y a sus piezas de Hardware.

![](https://static.platzi.com/media/files/operating-rings_9e1109d1-3440-45c3-864d-6da3eb4bb7cc.png)