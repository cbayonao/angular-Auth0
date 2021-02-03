# Que aprenderemos en esta seccion?

A continuacion trabajaremos con una aplicacion que tendra como finalidad, utilizar el sistema de autenticacion de usuarios Auth0.

Tras concluirla aprenderemos mucho sobre:

	- Que es Auth0 y la documentacion basada en Angular 2?
	- Autenticacion con facebook, twitter, google entre otros.
	- Creacion de un formulario de captura para la creacion de los usuarios.
	- Personalizacion de la caja de login.
	- Uso de servicios para bloquear rutas que no son validas si el usuario no esta autenticado.
	- Obtener informacion del perfil del usuario ingresado.
	- Entre otras cosas utiles para nuestras aplicaciones.

`ng g c components/navbar -is --skipTests` Genera componente -is indica que los estilos estan inline, --skiptests inidca que no se cree archivo de tests

`ng g guard services/auth` Genera un guard que previene el acceso a la ruta protegida si se conoce la ruta, pregunta lo siguiente:

	-CanActivate: Cuando no trabajamos con lazyload.
	-CanActivateChild: Por si acaso es ruta principal tiene rutas hijas.
	-CanLoad: Cuando usamos lazyload.
