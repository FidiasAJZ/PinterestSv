# Pinterest-Clone

OBJETIVO:

 Crear un clon de la siguiente página: https://ar.pinterest.com/

PROCESO:
1.	CREACIÓN DE HTML:
*	Crear un componente NavBar que este contenido por una etiqueta Header. Listo.
*	Incorporar en el mismo cada uno de los botones necesarios. Listo.
*	Incorporar un SearchBar dentro del NavBar, este SearchBar debe de contener las siguientes secciones: Búsquedas recientes, Ideas para ti, Populares en Pinterest.  Dichas secciones tienen que estar a priori vacias. Listo.
*	Crear el botón con un icono de interrogación el cual debe tener dentro una etiqueta Footer con todos los links y textos de derechos reservados de la pagina. * Proceso
*	Por ultimo tenemos que crear un componente que se va a repetir en toda la pagina, este componente será un contenedor llamado Card el cual debe tener dentro una etiqueta img para la imagen y 3 botones que se mostraran solo cuando el ratón este encima de la card. Listo
*	Los 3 botones serán: Guardar, Compartir, Mas Opciones. * Proceso

2.	CREACIÓN DE CSS (OPCIONAL BOOTSTRAP):
*	Las cajas deben de tener todas el mismo ancho (width) y la altura (heigth) debe de ser calculada respecto a la escala de la imagen. * Listo
*	La Grilla debe de ser Responsive, esto quiere decir que como el ancho de las cajas siempre es fijo entonces la cantidad de columnas que se muestran por pantalla deben de ser proporcionales al ancho del dispositivo que los esta visualizando. * Listo
*	Agregar los efectos de hover correspondientes a cada componente. * Listo

3.	CREACIÓN DE JAVASCRIPT (OPCIONAL JQUERY):
*	Crear un deslizar infinito, esto quiere decir que cuando la barra de desplazamiento vertical llegue hasta el final de la pagina, se deben de cargar mas Cards. * Listo
*	Al clickear en el SearchBar deben de incrustarse componentes de tipo Card Especiales dentro de las secciones “Populares en Pinterest” E “Ideas para ti”, y en “Búsquedas recientes” deben de incrustarse elementos de tipo Button con el texto de la las ultimas 5 busquedas. * Listo
*	Al realizar una búsqueda personalizada se debe de aplicar el filtro a las imágenes que se están visualizando por pantalla. * En proceso
*	Al seleccionar una categoría debe aplicarse esa categoría como filtro de las imágenes en pantalla. * En proceso

TECNOLOGIAS A UTILIZAR:
*	HTML
*	CSS
*	MEDIA QUERY
*	BOOTSTRAP
*	JAVASCRIPT
*	JQUERY (OPCIONAL)
*	HTTP
*	GIT
*	GITHUB
*	FIGMA (OPCIONAL)
RECURSOS:
*	


SCSS - modificar bootstrap. //Preprocesador de CSS *Antes de que la pagina procese el CSS se ejecuta el SCSS y crea estilos de CSS pero usando sintaxys de programación. Utilizando variables y condicionales. -> se transforma en el CSS. Bootstrap esta crado con esta tecnologia.

Vite es una herramienta para construir nuestra aplicación y nos permite manejar el ciclo de construcción de nuestra aplicación. "Ejecuta este empaquetador de codigo" todo lo que estructura el proyecto en general y no directamente se usa en el codigo. npm start dev. *slint *webpack codeli.