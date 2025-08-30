# Mercaprójimo
Se trata una práctica que hice en el grado. Los usuarios pueden ponerse en contacto para comprar o vender objetos de segunda mano.

La lógica consiste en que el usuario particular publica el anuncio, y de la misma forma en que puede publicar su anuncio, puede contactar con otros usuarios que han publicado un anuncio mostrando su interés por el producto.

La comunicación se realiza en la propia web a través de chat.

## Lenguajes y tecnologías
Esta hecha con: PHP, HTML5, CSS3, JS, MySQL y Bootstrap

## Vistas del sitio:

Inicio
![Inicio](img/1.png)
![Inicio](img/2.png)
![Inicio](img/3.png)

Menú
![Menu](img/4.png)


Productos añadidos
![Productos añadidos](img/6.png)


Perfil
![Perfil](img/7.png)


Lista de chats
![Lista de chats](img/8.png)


Chat con un usuario
![Chat con un usuario](img/9.png)


Aviso Legal
![Aviso legal](img/10.png)


Registro
![Registro](img/11.png)


Inicio de sesión
![Inicio de sesión](img/12.png)


## Vídeos demostración del sitio:
Vista como particular comprador (o interesado)
[Ver video](vid/1.mp4)


Vista como particular vendedor
[Ver video](vid/2.mp4)


## URL con acceso limitado:
https://mercaprojimo.oisan.freeddns.org


## Muestras del código:

index.php
![index](img/code/1.png)


var.php
El archivo donde se encuentran las variables de acceso común
![var](img/code/2.png)


Mensaje.php
Es el modelo para la creación de objetos Mensaje
![Usuario](img/code/3.png)


Usuario.php
Es el modelo para la creación de objetos Usuario.
Las funciones que aparecen son para crear usuarios en la BBDD y eliminarlos respetando los principios ACID (active = 0)
Y utilizando sentencias preparadas por motivos de seguridad.
![Usuario](img/code/4.png)


gestionProductos.php
Se obtienen los productos de la BBDD y se muestran en html.
![Usuario](img/code/5.png)


crearMensaje.php
Este script se ejecuta cuando el usuario pulsa sobre el botón de enviar mensaje en un chat.
![Usuario](img/code/6.png)


## BB.DD
La base de datos consta de 3 tablas: Usuarios, Productos, Mensajes.
![Usuario](img/code/7.png)
