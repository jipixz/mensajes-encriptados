# Integración de una aplicación para transferir mensajes encriptados

El objetivo de este trabajo es poner en práctica una combinación de **cifrado simétrico con simétrico** para aprovechar las ventajas de cada uno. En el trabajo anterior debieron aprender cómo se combinan éstos métodos.

El trabajo consiste en integrar código en **python**, **java** o **algún otro** que prefieran que permita el envío de mensajes cifrados usando ambos métodos. No les explicaré la secuencia de combinar ambos métodos porque precisamente esto es parte del trabajo, ya deben de saberlo:

1. El código consistirá de dos partes, un emisor un un receptor.
2. Supongamos que el emisor genera las llaves y las almacena, en el link adjunto hay un ejemplo de como se hace en java, no usen aplicaciones para generar las llaves, hay que hacerlo por medio de código
3. El emisor solicita al usuario la clave para generar la llave simétrica
4. El emisor solicita al usuario el mensaje a enviar
5. El receptor descifra el mensaje y lo muestra en pantalla
6. El emisor también puede enviar mensajes cifrados al emisor

Existe código para integrar esta aplicación, hay muchos ejemplos en internet que hacen cada parte de la aplicación. No están todos los pasos a detalle ya que éstos deben de conocerlos bien.

El entregable será un **video explicando este trabajo, como se integró, explicar el código y la aplicación en ejecución**.

En tres días **subirán a la plataforma una descripción de los pasos o pseudocódigo** que debe de incluir la aplicación.