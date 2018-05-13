# COUPON BLOG

### Datos del proyecto counpon blog

* Counpon blog esta implementado por Ghost y esta desarrollado enteramente en Javascript, usando [Node.js](https://nodejs.org/en/) como plataforma del lado del servidor.

* Ghost cuenta con una administración de contenido que usa [Ember.js](https://emberjs.com/), que es un framework del lado del cliente capaz de implementar SPA (Single Page Application) de una manera sencilla.

* Ghost cuenta también con [Handlebars](http://handlebarsjs.com/) es el lenguaje de plantillas semántico, sin lógica, y poderoso que alimenta a los temas de Ghost. Es muy fácil de aprender!.

* Mas información acerca de Ghost [Aqui](https://ghost.org/es/).

### Acerca de node
* Mac y Linux
	* Si usas nvm debe ingresar la versión completa de Node al ejecutar 	comando `nvm install 8.11.1` y `nvm use 8.11.1` listo.
	* Para hacer que el Nodo 8.11.1 sea el predeterminado en el 	terminal (Linux y macOS solamente) `$ nvm alias default 8.11.1`
	* Ahora que tiene Node instalado, puede continuar con la 	instalación de **landing-coupon**

* Windows
	> NVM no soporta Windows pero existe **nvm-windows**

	* Aqui puedes encontar una pequeña guia de acerca de [nvm-windows](http://www.nodenica.com/como-instalar-nvm/)

### Guía de instalación

* abrir terminar.
* clonar el repositorio `git clone git@github.com:Silverhill/coupon-blog.git`.
* ingresar a  `cd coupon-blog`.
* version node => `v8.11.1`,
* comando de instalación. =>  `npm install`.
* comando para iniciar el proyecto. =>  `npm start`.
* navegar a [http://localhost:2368/](http://localhost:2368/)

### Estructura de caperta para el tema coupon-blog
	├── /assets
    	├── /css
        	├── screen.css
    	├── /fonts
    	├── /images
    	├── /js
	├── /partials
    	├── loop.hbs
	├── default.hbs
	├── index.hbs [required]
	└── post.hbs [required]
	└── package.json [required]

* En la carpeta **assets** se guardan los ficheros css, js, imágenes, fuentes, videos, etc.
* En la carpeta **partials** se guardan partes que compondrán un layout o templates.
* El archivo **default.hbs** contiene la estructura que usaran la mayoría de layout.
* El archivo **index.hbs** sera el archivo principal de nuestro template.
* El archivo **post.hbs** es el layout donde se mostraran nuestros post.
* El archivo **package.json** contendrá información como nombre del tema y la versión.
