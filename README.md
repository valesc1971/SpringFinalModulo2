Proyecto Campcake - SprintFinal Modulo2
Este proyecto consiste es una pagina web para un negocio independiente que permite presentar la empresa y recibir pedidos de clientes. En este caso particular, se trata de una panaderia-pasteleria de nombre CampCake. En el futuro, se espera unir este proyecto con una base de datos de tal forma de poder almacenar los datos y pedidos de los clientes.

Tabla de Contenidos
Tecnologias Usadas
Instalacion
Consideraciones
Visualizacion del sitio web

Tecnologias
Este proyecto fue creado usando:

HTML
CSS
Boostrap (https://getbootstrap.com/)
JavaScript (https://datatables.net/)
JQuery (https://jquery.com/)
DataTable plugin

Instalacion
Para descargar este proyecto, se debe clonar desde este repositorio remoto a un repositorio local.

$git clone https://github.com/valesc1971/ABPro7.git


Consideraciones
Se utilizo HTML como herramienta principal para la creacion del codigo utilizando archivos CSS para formato en conjunto con JavaScript, JQuery, Boostrap y DataTable. Estas herramientas son llamadas desde los archivos HTML usando CDN.

El codigo en JavaScript y JQuery se ubican en Scripts/main.js. Este archivo es llamado desde los archivos HTML para su ejecucion.

El sitio web creado es responsivo y tiene 4 paginas HTML enlazadas entre si a traves de la barra de navegacion. Estas paginas HTML son:

Inicio - presentacion de la empresa (index.html)
Productos - presentacion de los productos (productos.html)
Pedidos - Formulario para ingresar datos del cliente y pedidos (contacto.html)
Estadisticas - Estadisticas de clientes y pedidos realizados (estadisticas)
Adicionalmente, cada una de estas paginas tiene su correspondiente archivo CSS style.ccs (index) style-productos.css (productos) style-contacto.css (contacto) style-estadisticas.css (estadisticas)

El archivo LOGO1.png corresponde al logo de la empresa

La pagina "Pedidos" es un formulario que entrega alertas por datos y por tipo de datos. Una vez que se completa correctamente el formulario, aparece una alerta de confirmacion.

Para desplegar la tabla de estadisticas se utilizo el plugin DataTable. https://datatables.net/. Considerando que este plugin entrega los strings en ingles, se ajustaron para que aparecieran en espanol.En una primera instancia, al actualizar la tabla, esta mostraba la tabla sin formato antes de desplegar el formato requerido; para evitar esto, se incluyo la funcion .show().

Para un buen funcionamiento del carrusel de Boostrap, se recomienda utilizar imagenes del mismo alto. Si no es asi, se debe ajusta el alto de la imagen y dejarlo fijo ajustado al de menor alto lo que hace perder la responsividad en esta parte.

La Familia de Fuentes utilizada es 'Roboto', sans-serif de GoogleFonts (https://fonts.google.com/)


Visualizacion del sitio web
image image image image

Este grupo de trabajo está conformado por: Valeria Sanchez, Fernando Quezada, Carlos Galleguillos y Alejandro Lanas.

Ningún derecho reservado, disponible para su copia, modificación y/o distribución en pos del aprendizaje.

© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
