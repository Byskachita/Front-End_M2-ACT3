<h1>Ejercicio-Práctico 3</h1>
Desarrollo de la Página Web de un Hospital

<h2>Contexto</h2>

Un hospital privado está buscando mejorar su presencia en línea mediante la creación de un sitio web que proporcione información clara y fácil de navegar para los pacientes. El sitio web debe reflejar la identidad del hospital, con información sobre los servicios médicos, el equipo médico, y una manera sencilla para que los pacientes puedan contactarse.

Trabajo práctico para desarrollar una página web de hospital que debe contener las siguientes páginas:

1. Vista Principal (Home o Index)
2. Vista del Equipo Médico
3. Vista de Contacto


Este proyecto tiene como objetivo realizar mejoras a la página del hospital desarrollada en el ejercicio anterior, aplicando SASS pero en esta ocasión se agrega bootstrap, se utilizará la misma base, pero se reorganizarán las carpetas para integrar los estilos necesarios que utiliza bootstrap para cada sección y/o módulo.


<h3>Instrucciones de uso</h3>

Clonar el repositorio desde GitHub, o en su defecto descargar los contenidos como zip.
Luego, abrir `index.html` en su navegador por defecto, pero se recomienda Chrome para una mejor experiencia.







## Estructura del proyecto
# Centro médico
    ├── assets
    	 ├── /img               # Imágenes utilizadas en el proyecto
    ├── dist                # Carpetas de bootstrap 
	├──── /css         # archivos css bootstrap 
		├──── /pages         # css vinculada desde sass
	├──── /js         # archivos js de bootstrap
    ├── scss                # SASS estructura de bootstrap
    	├──── /forms         # archivos scss de los formularios de booststrap
    	├──── /helpers      # archivos scss
	├──── /mixins       # Módulos, texto, listas, botones, etc.
    	├──── /pages       # páginas scss de mi proyecto
		 ├── __contact.scss
		 ├── __home.scss
		 ├── __services.scss
    	├──── /tests
		 ├── /mixins # archivos	    
		 ├── /sass-true #archivos js
		 ├── /utilities #Api
		 ├── jasmine.js
    	├──── /utilities             # archivo api
    	├──── /vendor
    ├── contact.html           # Página de contacto
    ├── home.html              # Página de inicio
    ├── services.html         # Página de nosotros y servicios
    └── README.md        # Ud. se encuentra aquí

Este texto se subió como archivo a la plataforma, agrego link que redirige a esta misma páginas donde se pueden visualizar las carpetas creadas https://github.com/Byskachita/Front-End_M2-ACT3
