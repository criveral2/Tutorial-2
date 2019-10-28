
 	PRÁCTICA DE LABORATORIO 

CARRERA: Computación	
ASIGNATURA: HIPERMEDIAL
NRO. PRÁCTICA:	3	
TÍTULO PRÁCTICA: Tutorial 2
OBJETIVO ALCANZADO:
Diseñar sitios web utilizando los respectivos estándares actuales e implementando diferentes estilos gráficos para crear paginas iterativas para el usuario.
El desarrollo del taller ayudó al buen manejo y al aprendizaje del estudiante sobre los sitios web.

ACTIVIDADES DESARROLLADAS
Tri and Succeed Sports:
Ingrese su nombre y la fecha en la sección de comentarios del archivo y guarde el documento como tss_home.html.
Para cambiar el diseño de la página de inicio de TSS:
Regrese al archivo tss_home.html en su editor HTML y agregue lo siguiente
elemento de enlace a la sección de cabecera directamente después del elemento de título:
<link href = "tss_layout.css" rel = "stylesheet" />

Guarde sus cambios en el archivo y luego vuelva a abrir el archivo tss_home.html en su
navegador. La Figura 2-4 muestra la apariencia de la página usando los estilos de diseño
definido en el archivo tss_layout.css.
 

Escribir un comentario de estilo:
Use su editor para abrir el archivo tss_styles_txt.css del tutorial html02 
carpeta.
Dentro de la sección de comentarios en la parte superior del archivo, ingrese su nombre después
el Autor: comentario y la fecha siguiente a la Fecha: comentario.
 
Regrese al archivo tss_home.html en su editor HTML y agregue lo siguiente
elemento de enlace directamente antes de la etiqueta de cierre </head>.
<link href = "tss_styles.css" rel = "stylesheet" />
 
Cierre el archivo tss_home.html, guardando sus cambios.

Para indicar la codificación de caracteres:
Regrese al archivo tss_styles.css en su editor.
Directamente encima de la sección de comentarios iniciales, inserte la línea: @charset "utf-8" ;.
 
Guarde sus cambios en el archivo.

Para definir colores de fondo y texto:
Agregue el siguiente código dentro de la sección HTML y Estilos del cuerpo:
html {
 background-color: hsl(27, 72%, 72%);
 } 
body { 
color: rgb(91, 91, 91); 
background-color: ivory; 
}

 
Agregue las siguientes reglas de estilo dentro de la sección Estilos de encabezado:
h1 { 
color: white; 
background-color: rgb(222, 128, 60);
 } 
h2 { 
color: white;
 background-color: rgb(235, 177, 131); 
}
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador.


Para crear una regla de estilo con un selector contextual:
Dentro de la sección Estilos Aparte y Blockquote, inserte el siguiente estilo
regla:
aside blockquote { 
color: rgb(232, 165, 116); 
}
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador.
Para aplicar un selector de id:
Regrese al archivo tss_styles.css en su editor.
Cambie los selectores para los elementos h1 y h2 en el Título
Sección de estilos para el artículo # about_tss h1 y el artículo # about_tss h2
respectivamente.

 
La Figura 2-16 resalta los selectores revisados en la hoja de estilo.
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. 

Para aplicar un selector de clase:
Use su editor para abrir tss_run_txt.html, tss_bike_txt.html y
archivos tss_swim_txt.html de la carpeta html02 tutorial. Introduzca su nombre
y la fecha en la sección de comentarios de cada archivo y guárdelos como
tss_run.html, tss_bike.html y tss_swim.html respectivamente.
Tómese un tiempo para estudiar el contenido y la estructura de los archivos. Tenga en cuenta que el elemento del artículo tiene el atributo de clase con el programa de valores. Guarda tus cambios a los archivos.
Regrese al archivo tss_style.css en su editor.
Dentro de la sección Estilos de encabezado, agregue la siguiente regla de estilo para mostrar el texto de los títulos h1 y h2 en gris medio sobre un fondo morado claro:
article.syllabus h1, article.syllabus h2 { 
background-color: rgb(255, 185, 255); 
color: rgb(101, 101, 101); 
}

 
Guarde los cambios en la hoja de estilo y luego abra el archivo tss_run.html en
su navegador.
Use los enlaces de navegación en la página para ver el contenido y el diseño de
las páginas de ciclismo y natación, y luego confirme que h1 y h2
Los títulos de estas páginas tienen formatos similares.
 
 


Para especificar una familia de fuentes para el cuerpo de la página:
Regrese al archivo tss_styles.css en su editor.
Agregue el siguiente estilo a la regla de estilo para el elemento del cuerpo:

 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador.
Vea las otras tres páginas en el sitio web para verificar que la fuente sans-serif sea
también se aplica al texto del cuerpo en esas páginas.
 
 
 

Para instalar y usar una fuente web:
Regrese al archivo tss_styles.css en su editor.
Directamente después de la regla @charset en la parte superior del archivo, inserte lo siguiente regla @ font-face:
@font-face { 
font-family: Quicksand; 
src: url('Quicksand-Regular.woff') format('woff'),
 url('Quicksand-Regular.ttf') format('truetype'); 
}

 
En la parte superior de la sección para Estilos de encabezado, inserte la regla de estilo:
h1, h2 {
 font-family: Quicksand, Verdana, Geneva, sans-serif; 
}

 
Guarde sus cambios en el archivo y vuelva a cargar el archivo tss_home.html en su
navegador. 



Para establecer los tamaños de fuente de los elementos de la página:
Regrese al archivo tss_styles.css en su editor.
En la sección Estilos de encabezado, inserte el siguiente estilo como parte del estilo
regla para el selector h1, h2:
letter-spacing: 0.1em;

 
Desplácese hacia abajo hasta la sección Estilos de navegación cerca de la parte inferior del archivo y inserte la siguiente regla de estilo para el texto de elementos ul anidados dentro de
elemento de navegación:
nav > ul {
 line-height: 2em; 
}
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. Verifique que el espacio entre letras en los encabezados h1 y h2 tenga
ha aumentado y la lista de enlaces ahora está a doble espacio.
 

Para aplicar la propiedad de fuente:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos de pie de página y agregue la siguiente regla de estilo:
body > footer address { 
background-color: rgb(222,128,60); 
color: white;
 color: rgba(255, 255, 255, 0.7);
 font: normal small-caps bold 0.9em/3em Quicksand, Verdana, Geneva, sans-serif;
 text-align: center; 
}
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. 
Para aplicar un estilo de contorno:
Si tomaste un descanso después de la sesión anterior, asegúrate de que tss_styles.css
El archivo está abierto en su editor.
Desplácese hacia abajo a la sección Estilos de lista e inserte las siguientes reglas de estilo para
formatee listas ordenadas anidadas dentro del artículo del programa de estudios:

 
Guarde sus cambios en el archivo y luego abra el archivo tss_run.html en su

Para eliminar los marcadores de las listas de navegación:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos de navegación y, dentro de la regla de estilo para la navegación> ul selector, agrega el estilo list-style-type: none;

 
Guarde sus cambios en el archivo y luego abra el archivo tss_home.html en su
navegador. Verifique que no haya marcadores junto a los elementos de la lista de navegación en la columna izquierda.
 
Vaya a las otras tres páginas en el sitio web y verifique que las listas de navegación en
Estas páginas tampoco tienen marcadores de lista.
 

Para usar una imagen para un marcador de lista:
Regrese al archivo tss_styles.css en su editor.
En la parte superior de la sección Estilos de lista, inserte la siguiente regla de estilo:
article#about_tss ul { 
list-style-image: url(runicon.png);
 }

 
Guarde sus cambios en el archivo y luego abra el archivo tss_home.html en su
navegador.
Para cambiar el relleno izquierdo utilizado en la lista de navegación:
Regrese al archivo tss_styles.css en su editor.
Localice la regla de estilo nav> ul en la sección Estilos de navegación e inserte el
Estilo padding-left: 5px;.
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. 
Para aumentar el margen superior:
Regrese al archivo tss_styles.css en su editor.
Directamente debajo de la regla de estilo para el selector nav> ul en los estilos de navegación sección, inserte la siguiente regla:
nav > ul > li.newgroup {
 margin-top: 20px; 
}

 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en
su navegador Verifique que las entradas en la lista de navegación ahora estén divididas
en tres grupos: el primer grupo que contiene los enlaces del Tri y
Tener éxito en el sitio web de deportes; el segundo grupo que contiene enlaces a sitios web
en correr, andar en bicicleta y nadar; y el tercer grupo que contiene enlaces
a los sitios web de triatlón.
 

Para cambiar el espacio de margen alrededor de las comillas de bloque:
Regrese al archivo tss_styles.css en su editor.
Localice la regla de estilo para el selector de bloque de comillas a un lado en el lado y
Sección Estilos Blockquote e inserte el margen: 20px 5px; estilo en el
regla de estilo.

 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. 


Para aplicar pseudo-clases a una lista desordenada:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos de lista en la parte inferior de la hoja de estilos, elimine el
artículo # about_tss regla de estilo ul que establece el marcador de imagen de estilo de lista y
reemplácelo con las siguientes tres reglas de estilo:
 

Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en
su navegador
Para aplicar pseudo-clases a enlaces de hipertexto:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos de navegación e inserte las siguientes reglas de estilo para
enlaces de hipertexto que han sido visitados o no visitados.
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegue y desplace el puntero del mouse sobre los enlaces en la lista de navegación.

Para insertar comillas en comillas de bloque:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos aparte y de Blockquote y, dentro de la regla de estilo para
el selector de comillas de bloque aparte, inserte la siguiente propiedad de comillas para usar
comillas rizadas para las comillas:
quotes: "\201C" "\201D";Agregue las siguientes reglas de estilo para insertar comillas antes y después de cada
comilla de bloque en el elemento aparte:

 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. 



información de GitHub
Usuario: criveral2
Correo: criveral2@est.ups.edu.ec
Github: git@github.com:criveral2/Tutorial-2.git


RESULTADO(S) OBTENIDO(S):
Se obtuvieron conocimientos sobre los diferentes estilos que utiliza una web para la creación de páginas, como también el buen uso de las herramientas que la web dispone.
CONCLUSIONES:
Se obtuvo el entendimiento de organizar sitios web utilizando el lenguaje html y css.
RECOMENDACIONES:
Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, Firefox y Safari, además, probar la verificación de un validador de paginas web. 

Nombre de estudiante: ___Christian Rivera__________________________




