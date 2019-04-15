# Pr-ctica02---Mi-Sitio-Web-CSS-
 	FORMATO DE INFORME DE PRÁCTICA DE LABORATORIO / TALLERES / CENTROS DE SIMULACIÓN – PARA ESTUDIANTES
CARRERA:  INGENIERÍA DE SISTEMAS
	ASIGNATURA:  HYPERMEDIAL 
NRO. PRÁCTICA:	2	TÍTULO PRÁCTICA:  Resolución de problemas sobre CSS3
OBJETIVO ALCANZADO:
Entender y organizar de una mejor manera los sitios de web en Internet 
Diseñar adecuadamente elementos gráficos en sitios web en Internet.
Crear sitios web aplicando estándares actuales.
ACTIVIDADES DESARROLLADAS
1. Crear un repositorio en GitHub con el nombre “Practica02 – Mi Sitio Web(CSS)”
Para realizar este paso previamente creamos una cuenta en GitHub, ahora conectado a la cuenta en línea procedemos a crear el repositorio donde guardaremos la práctica.
 
Luego tendremos la siguiente pantalla: 
  
Con esto ya hemos creado nuestro repositorio. En este lugar nos dará la url del repositorio que es necesaria para configurar la forma de subir los archivos.
2. Realizar un commit y push por cada requerimiento de los puntos antes descritos. 
Para el desarrollo de esta práctica haremos uso del proyecto anterior, al cual le daremos estilos con CSS 3.
Para esto debemos abrir el cmd y colocar los siguientes comandos, en el caso de Windows:
-	git init
-	git add .
-	git commit -m "Nombre-Proyecto"
-	git remote add origin “url del respositorio”
-	git push -u origin master
Estos para la primera vez que se vaya a trabajar con el proyecto, después solo es necesario correr:
-	git add .
-	git commit -m "Nombre-Proyecto"
-	git push -u origin master
Y para que esto funcione previamente debes haber instalado y configurado “Git for Windows”.
Ahora luego de correr los comandos tendremos:
 
Con el init iniciamos el repositorio vacío.
Con el add los añadimos.
Con el commit creamos los datos dentro del repositorio.
Con el remote le damos la dirección de donde subir los archivos.
Y con el push guardamos los datos en el repositorio.
Si todo corre bien deberíamos obtener lo siguiente:
 
Como pueden darse cuenta la pagina web en GitHub se actualiza con los nuevos datos subidos, con esto hemos cargado en la pagina el primer punto de la práctica.
Funciones de CSS utilizadas:
-	Selectores Etiquetas:
-	Selectores Descendentes:
-	Selectores de Clase:
-	Selectores ID:
Para el primer punto de la practica tenemos:
“Con base a la Práctica 01 - Resolución de problemas sobre HTML5, se pide utilizar estilos CSS con la finalidad de obtener un diseño como el que se muestra a continuación
 
Para lo cual, se recomienda utilizar, en al menos una página HTML, un diseño a dos columnas con cabecera y pie de página, como el que se muestra en la Figura 2. Así, como también se recomienda utilizar, en al menos una página HTML, un diseño a tres columnas con cabecera y pie de página como se muestra en la Figura 3.”
Ahora en nuestra carpeta creada tenemos los archivos de las páginas web a utilizar: 
 
Crearemos los archivos .css necesarios para nuestra práctica.
 
En lo referente a esta practica vamos a revisar CSS 3, así que con lo referente a HTML solo revisaremos como se debe acceder a los métodos creados en los archivos .css. Yo definí 9 archivos css para organizar el estilo de las páginas. 
sarticulos: se encarga del estilo de los artículos de las páginas.
scolores: se encarga de los colores definidos para los estilos de las páginas.
smultimedia: se encarga de los estilos de las imágenes y videos en las páginas.
ssections: se encarga de los estilos las secciones.
stables: se encarga de los estilos de las tablas.
stext: se encarga de los estilos del texto.
sthreecol: se encarga del estilo de cajas de tres columnas.
stwocol: se encarga del estilo de cajas de dos columnas.
Haremos el primer commit y push:
Ahora en la carpeta css están los archivos utilizados para el diseño de la página:
Revisaremos estos archivos ahora:
Revisaremos el archivo para colocar en estilo de 3 columnas, que es el uso del modelo de cajas:
Aquí tenemos según el selector id dado en html, los selectores #menuPrincipal y #contenido:
Width: controla la anchura de la caja de los elementos.
Border: controla el diseño de los bordes.
Border-radius: controla las esquinas de las cajas.
Float: controla el movimiento de las cajas en forma flotante.
Margin-lefth: controla el ancho del margen a la izquierda.
Padding: controla el relleno de los elementos tanto horizontales como verticales.
Para usarlos en html debemos hacer los siguiente:
 
Esto se define según el tipo de selectores:
Selector ID: id=” nombreid” y en css se lo llama con el símbolo # seguido sin separación del nombreid.
Selector de Clase: class=” nombreclase” y en css se lo llama así: etiqueta.nombreclase.
Selectores Descendentes: se coloca primero la etiqueta principal y luego la etiqueta que está dentro de la principal que quiere modificar, así: etiqueta principal etiqueta a modificar.
Selectores por Etiquetas: se coloca el nombre de la etiqueta y todas las que se llamen así se verán afectadas.
Ejemplo:
En HTML5:
 
En CSS3:
Resultado:
 
De esta forma se realizarán todos los archivos .css según las necesidades requeridas.
Diseño 3 columnas:
 
Para esto agregamos 2 nuevos selectores ID uno para la tercera columna y el otro para el pie de página.
Resultado: Inicio Página / Final Página
 
 
Diseño archivo .css de colores:
   
 
En este archivo manejamos los colores utilizados en todo el diseño de la página web.
Llamamos a los selectores en cada página, según su tipo y colocamos lo necesario para que funciones.
color: da color al texto, según la etiqueta.
border-color: da color al borde la página, según la etiqueta.
background-color: da color al fondo de la página, según la etiqueta.
Los colores pueden ser usado mediante: palabras clave, colores del sistema, RGB hexadecimal, RGB numérico y RGB porcentual. Nosotros usamos las palabras clave y RGB hexadecimal.
Diseño del archivo .css del texto:
   
En este archivo manejamos el texto en todo el diseño de la página web.
Llamamos a los selectores en cada página, según su tipo y colocamos lo necesario para que funciones.
font-size: controla el tamaño de la fuente.
font-family: controla el tipo de fuente.
text-decoration: controla la decoración del texto general.
text-decoration-line: controla la decoración del texto por línea.
letter-spacing: controla el espacio entre letras.
text-aling: controla la alineacíon del texto.
Diseño del archivo .css de la tabla:
 
Hacemos uso de border, width, para dar el estilo requerido a la tabla y la etiqueta vertical-align que centra el contenido de las celdas.
Diseño del archivo .css de la tabla:
  
Se hace uso de width y height para dar el tamaño este tipo de elementos.
Diseño del archivo .css para las secciones.
 
Hacemos uso de width, height, float, margin para el margen, margin-top Tambien para el margen, pero en la parte de arriba.
Para el archivo .css para artículos.
 
Aquí solo le damos forma al borde para los artículos.

También, se pide que se utilice selectores por etiquetas, selectores descendentes, selectores por clase y selectores por id.
Selector ID: id=” nombreid” y en css se lo llama con el símbolo # seguido sin separación del nombreid.
Ejemplo:
En HTML5:
 
En CSS3:
 
Selector de Clase: class=” nombreclase” y en css se lo llama así: etiqueta.nombreclase.
Ejemplo:
En HTML5:
 
En CSS3:
Selectores Descendentes: se coloca primero la etiqueta principal y luego la etiqueta que está dentro de la principal que quiere modificar, así: etiqueta principal etiqueta a modificar.
Ejemplo:
HTML5
Al ser de este tipo no se pone nada en HTML5, este hace efecto a todas las etiquetas a entre la etiqueta nav.
CSS:
 
Selectores por Etiquetas: se coloca el nombre de la etiqueta y todas las que se llamen así se verán afectadas.
Ejemplo:
HTML5
Igual que en el anterior, no se coloca nada, pero la diferencia es que modifica todas las etiquetas que se encuentren en el archivo.
CSS3
 
Para hacer uso de esto en HTML5 se debe de hacer un link, a manera de importar el archivo de la siguiente forma:
 
Entre la etiqueta head se utiliza la etiqueta link para que de esta forma se haga uso de los archivos requeridos para la página en cuestión.
En la etiqueta va la dirección del archivo .css a enlazar, la relación del documento a enlazar y el tipo de documento a enlazar.
GitHub
Luego, se pide que se personalicen al menos tres etiquetas para títulos (h1 – h6), tanto en color, tamaño, fuente, decoraciones, etc.
GitHub 
Asimismo, se pide que se personalice todos los hipervínculos usando pseudo-clases.
El uso de pseudo-clases hace referencia generalmente para cambiar el color de los hipervínculos, cuando estas sobre el hipervínculo, cuando abres el hipervínculo.
Regla CSS:
Etiqueta:tipodepseudo-clase
a:link: pone de color el texto cuando aun no se accede al hipervínculo.
a:visited: pone de color el texto cuando se ha abierto el hipervínculo.
a:hover: pone de color el texto cuando poner el puntero encima del hipervínculo.
a:focus: pone de color el texto cuando recorrer con TAB o cuando hacer clic con el puntero.
GitHub
También, se pide que se cree un menú vertical (navegación) para todas las páginas. El menú debe tener bordes ovalados, con color de fondo y una separación entre cada menú de al menos 5px.
   
En esta parte configuramos el borde, el tamaño de separación y el color de fondo respectivamente.
De igual manera, se pide crear una nueva página HTML, en donde, se muestre un formulario de contacto que tenga los siguientes campos (nombre, correo electrónico, mensaje y botón para enviar).
 
Hacemos uso de algunas etiquetas anteriores, pero las nuevas son:
label: para etiquetas.
input: para entradas.
id: código, name: nombre y placeholder: texto de ejemplo.
textarea: para entrada de mayor tamaño.
id: código, name: nombre y placeholder: texto de ejemplo.
button: para botón.
Resultado:
GitHub.
Asimismo, se pide que se utilice una gama de máximo cinco colores (ver más, https://htmlcolorcodes.com/es/recursos/mejor-paleta-de-colores-generadores/).
Aquí hicimos uso de la herramienta: Coolors
 
CSS3
 
Resultado:
 
Finalmente, se pide que en toda la práctica existan al menos 50 reglas CSS.
Al final tengo un total de 53 reglas CSS3, distribuidas en los archivos .css.
GitHub
  
3. Verificación de los archivos .css y las páginas HTML con W3CValidator.
HTML5
Página: acerca.html
 
Página: animales.html
 
Página: causas.html
 
Página: consecuencias.html
 
Página: envio.html
 
Página: estadisticas.html
 
Página: index.html 
 
CSS3
Archivo: sarticulos.css
 
Archivo: scolores.css
 
Archivo: smultimedia.css
 
Archivo: ssections.css
 
Archivo: stables.css
 
Archivo: stext.css
 
Archivo: stwocol.css
 
Archivo: sthreecol.css
 
4. Luego, se debe crear el archivo README del repositorio de GitHub. 
5. Información de GitHub (usuario y URL del repositorio de la práctica).
Usuario: jmurillov1
URL del repositorio: https://github.com/jmurillov1/Pr-ctica02---Mi-Sitio-Web-CSS-
7. En el archivo README del repositorio debe constar la misma información del informe de resultados de la práctica que se indica en el siguiente punto. 
 
RESULTADO(S) OBTENIDO(S):
•	Tener el conocimiento suficiente para que el estudiante pueda entender y organizar de una mejor manera los sitios de web y de negocios en Internet.
•	Tener el conocimiento sobre nuevas etiquetas y su uso.
•	Aprender a usar HTML5 y CCS3.
Resultados:
Sitio Web Completo: Google Chrome
Sitio Web Completo: Firefox
Sitio Web Completo: Internet Explorer
 CONCLUSIONES:
•	Los estudiantes podrán organizar sitios web basados en el lenguaje de etiquetado HTML. Y CSS
•	Que se debe organizar muy bien las etiquetas y los archivos CSS y la información para que la estructura sea correcta y lograr los resultados esperados.
•	Que la estructura con HTML5 es más rápida de trabajar, porque resume algunas cosas y si agrega CSS3 es mucho más fácil y rápido de trabajar.
RECOMENDACIONES:
•	Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, Firefox y Safari.
•	Validar las páginas creadas con un software, como es el caso de: W3C Validator.
•	Usar correctamente las etiquetas HTML y las formas de CSS.
Nombre del estudiante: Jordan Fernando Murillo Valarezo
Firma del estudiante: 
