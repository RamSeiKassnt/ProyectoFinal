# ProyectoFinal
Proyecto Final Coder
En este proyecto Final para el curso de Python de CoderHouse, se realizo una pagina web de administracion de un taller mecanico para automoviles multimarca. La pagina se realizó utilizando Djago con lenguaje Python y plantillas HTML donde se modificaron las imagenes y el icono de la pagina heredada (carpeta static).
La pagina tiene dos secciones, una publica y una privada que solo podrá acceder un usuario previamente registrado: si el usuario es un superusuario podra acceder incluso a la seccion "Gestionar usuario" que nos lleva al panel de administracion de Djago. La parte privada tambien tiene otras secciones que los usuarios standard podran navegar: "Ver comentarios", mostrara los comentarios que los usuarios anonimos pueden dejar para calificar el servicio (solo lectura en este caso), "Clientes", "Autos" y "Service" son tres secciones creadas con tres modelos con sus respectivos formularios que permitiran hacer el CRUD en cada una de ellas.
Finalmente, un usuario loggeado podra cerrar la sesion e ir a la parte publica de la pagina.
Con respecto a esta parte, se podra ver que el menu de navegacion cambia y mostrara solo tres secciones: "Home", "Calificar nuestro servicio" y "Acerca de mi". La primera mostrará la pagina inicial con una descripcion de los servicios prestados por el taller, mientras que la tercera compartira la motivacion del trabajo. La seccion de calificar el servicio, mostrara el formulario que permitira dejar los comentarios pertinentes y que luego solo podran revisar los usuario autenticados.

Existe tambien una seccion oculta (register) en el proyecto donde podremos desde la pagina crear un nuevo usuario. Sin embargo cuando intentemos ingresar a la pagina con este nuevo usuario se presentara un problema ya que no tiene un avatar (esto ultimo solo podra agregarse desde la seccion "Gestionar usuarios" - ingresando al sistema con un supersusuario).

otros problemas encontrados: a veces muestra algun error en el codico al intentar hacer el CRUD de los modelos, aunque refrescando la pagina logra hacerlo sin problemas (no encontre el error como para corregirlo ya que, como digo, lo soluciona haciendo un refresh de la pagina; entiendo es algo del cache)

superusuario:
Usuario: RamSe
contraseña: Coder1234

Video explicativo de navegacion en el siguiente link
https://drive.google.com/file/d/1ImcPRO9UzDkKz1rZnRgpT5Pa43drceHM/view?usp=share_link

