# Pagina web hecha con WordPress en Local

A continuación, os enseñaremos a como instalar y utilizar el wordpress en local, ademas os enseñaremos a descargar la basa de datos que necesitaras para descragar tu proyecto de wordpress.

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

### Pre-requisitos 📋

Para la instalación del wordpress en local necesitaremos un sistema operativo Windows, Linux o MAC.
Deberemos dirigirnos a la web de xampp, para descargarnos la versión de xampp de nuestros sistemas operativo (en este caso windows).

### Instalación 🔧

# Instalación de Xampp 

1- Haz doble clic en el fichero que te has descargado para empezar la instalación de XAMPP.

Si usas Windows te aconsejo que mejor hagas clic encima del fichero con el botón derecho del ratón para que te salga el menú y elijas la opción Ejecutar como administrador.

2- Te aparecerá una ventana de bienvenida como ésta en la que sólo tienes que hacer clic en el botón Next.

![image](https://cdn.miposicionamientoweb.es/wp-content/uploads/2017/06/instalacion-xampp.png) 

3- En la siguiente pantalla puedes elegir los componentes de XAMPP que quieras instalar.

Puedes dejarlo con todo seleccionado por defecto o seleccionar sólo lo que necesites. En este caso como mínimo necesitas seleccionar Apache, MySQL, PHP y phpMyAdmin.

Después haz clic en el botón Next.ç

4- Aquí puedes elegir la carpeta donde se instalará XAMPP y todos los componentes que hayas seleccionado antes.

En Windows la carpeta de instalación por defecto es C:\xampp.

Haz clic en el botón Next. En la siguiente pestaña, también le daremos a next.

5- Seguidmanete te avisa de que la instalación ya está lista para ejecutarse, así que sólo tienes que hacer clic en Next. Y acto seguido verás esta otra ventana con el progreso de la instalación.
Cuando haya terminado podrás hacer clic en el botón Next.

6- Por último verás una ventana avisando de que la instalación se ha completado con éxito.

Y hay una opción seleccionada por si quieres abrir ya el panel de control de XAMPP.

Haz clic en el botón Finish.

# Como Utilizar el Panel de Control de Xampp

La primera vez nada más abrir el panel de control de XAMPP te saldrá una opción para elegir el idioma entre el inglés o el alemán. Elige el inglés (si quieres) y haz clic en Save.

Ahora verás el panel de control con todos los elementos instalados.

Puede parecer algo lioso, pero con saber lo que voy a explicarte ahora verás que es más que suficiente:

 1- Haciendo clic sólo en estos 2 botones Start ya tendrías lo necesario para instalar tu WordPress en local. Con el primero arrancas el servidor Apache, y con el segundo arrancas el gestor de base de datos.

Una vez arrancados verás que se pondrán de color verde y podrás pararlos cuando quieras haciendo clic en los botones de Stop.

![image](https://cdn.miposicionamientoweb.es/wp-content/uploads/2017/06/servidor-arrancado-apache-mysql.png) 

2- Con el botón Explorer puedes ir directamente a la carpeta donde hayas instalado XAMPP, que en Windows por defecto ya has visto que es C:\xampp.

3- Y en este apartado inferior se irán mostrando mensajes sobre el estado del servidor local, si se ha arrancado bien Apache o MySQL, si ha habido algún error, etc.

Así que ya sabes, ahora sólo tienes que arrancar Apache y MySQL haciendo clic en los botones de Start…

# Crear base de dato para Wordpressç

Antes de instalar WordPress en local necesitas crear una base de datos nueva.

Para eso vamos a usar phpMyAdmin, que es la herramienta que administra las bases de datos de MySQL en nuestro servidor local.

1- Nada más entrar al gestor de bases de datos de phpMyAdmin verás una ventana como ésta.

En la parte izquierda verás las bases de datos que hay creadas por defecto en tu servidor local.

![image](https://cdn.miposicionamientoweb.es/wp-content/uploads/2017/06/gestor-bases-de-datos-phpmyadmin.png) 

2- En este mismo apartado de la izquierda, haz clic en Nueva. Verás que en la parte derecha ahora te dejará elegir el nombre de la nueva base de datos (yo he puesto nuevabd) y en Cotejamiento elige la opción utf8mb4_general_ci (te la elige pro defecto).

Haz clic en el botón Crear.

3- Ahora en el apartado de la izquierda ya tendrás tu nueva base de datos creada.

El usuario para poder gestionarla (esto te hará falta luego cuando instales WordPress) es root, que es el usuario principal que crea XAMPP, y por defecto el usuario root no tiene password.

# Instalar WordPress en local con XAMPP,

1- Lo primero que debes hacer es descargarte el fichero .zip con la última versión de WordPress desde la página oficial de WordPress. Mueve este fichero a la carpeta C:\xampp\htdocs\www que es la carpeta que emos creado nosotros de XAMPP.

2- Tienes que descomprimir el fichero para que extraiga el contenido directamente en C:\xampp\htdocs\www.

Así se creará una carpeta nueva llamada «wordpress» que contiene todo lo necesario para instalar tu WordPress desde cero.

3- Ahora ya puedes entrar en http://localhost/wordpress/ desde tu navegador (que sería la carpeta «wordpress» que acabas de crear).

Automáticamente te llevará a la pantalla de bienvenida para empezar la instalación y configuración de WordPress desde cero.

Haz clic en el botón ¡Vamos a ello!

4- En la pantalla siguiente tienes que meter los datos de la base de datos que creaste en el punto 3 tal y como están en la imagen.

Recuerda que el usuario root no tiene contraseña, así que deja este campo vacío.

Después haz clic en el botón Enviar. Y seguidamente haz clic en Ejecutar la instalación.

![image](https://cdn.miposicionamientoweb.es/wp-content/uploads/2017/06/instalar-wordpress-local-configuracion-base-de-datos.png)

5- Aquí tienes que rellenar los datos para la instalación de WordPress, como el título de tu nuevo sitio, el nombre del usuario que quieres crear para administrarlo, su password, etc.

Puedes seleccionar la opción Disuadir a los motores de búsqueda de indexar este sitio si quieres, aunque en verdad ni Google ni nadie podrá ver tu sitio estando en local (si no quieres, claro).

Después haz clic en Instalar WordPress.

6- Si todo ha ido bien verás un mensaje como éste en el que te avisa de que WordPress se ha instalado correctamente.

Ahora puedes hacer clic en el botón Acceder para ir a la ventana de login de tu WordPress.

7- Ahora simplemente deberás darle al botón de acceder, escribiendo tus credenciales escritos anteriormente. Y entrando desde http://localhost/wordpress/ podrás ver cómo queda tu sitio.

## Construido con 🛠️

Este proyecto ha sido realizado gracias a la ayuda de estos programas:
- Xampp
- Visual Studio Code
- Github

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Autores ✒️

* **Pere Torras** - *Trabajo Inicial* - [PereTorras](https://github.com/Torraselpere)
* **Danny Larrea** - *Profesor* - [Fuente de Información] 

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Danny Larrea gran contibuïdor del trabajo. 📢
* Cuando quieras me invitas a una cena ;)  
* Agradecido con el de arrbia por hacer esto posible.
