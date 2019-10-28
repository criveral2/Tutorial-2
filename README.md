
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

![image](https://user-images.githubusercontent.com/52549697/67696947-bd10de80-f975-11e9-9089-fa6b2e2b3ae8.png)

 

Escribir un comentario de estilo:
Use su editor para abrir el archivo tss_styles_txt.css del tutorial html02 
carpeta.
Dentro de la sección de comentarios en la parte superior del archivo, ingrese su nombre después
el Autor: comentario y la fecha siguiente a la Fecha: comentario.

![image](https://user-images.githubusercontent.com/52549697/67697020-e03b8e00-f975-11e9-85d6-9c9ea8665402.png)
 
Regrese al archivo tss_home.html en su editor HTML y agregue lo siguiente
elemento de enlace directamente antes de la etiqueta de cierre </head>.
<link href = "tss_styles.css" rel = "stylesheet" />
![image](https://user-images.githubusercontent.com/52549697/67697069-f47f8b00-f975-11e9-8a67-559b481db73d.png)
 
Cierre el archivo tss_home.html, guardando sus cambios.

Para indicar la codificación de caracteres:
Regrese al archivo tss_styles.css en su editor.
Directamente encima de la sección de comentarios iniciales, inserte la línea: @charset "utf-8" ;.
 
 
 ![image](https://user-images.githubusercontent.com/52549697/67697113-0b25e200-f976-11e9-9348-0b8b1bc2ffa9.png)
 
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

![image](https://user-images.githubusercontent.com/52549697/67697149-18db6780-f976-11e9-8d70-523567af8243.png)

 
Agregue las siguientes reglas de estilo dentro de la sección Estilos de encabezado:
h1 { 
color: white; 
background-color: rgb(222, 128, 60);
 } 
h2 { 
color: white;
 background-color: rgb(235, 177, 131); 
}

![image](https://user-images.githubusercontent.com/52549697/67697174-2395fc80-f976-11e9-9527-fddc7e3ea3aa.png)
 
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

![image](https://user-images.githubusercontent.com/52549697/67697195-2c86ce00-f976-11e9-9f84-b2a8827ed944.png)

 
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

![image](https://user-images.githubusercontent.com/52549697/67697246-3b6d8080-f976-11e9-9346-a17fc96cc0e2.png)

 
Guarde los cambios en la hoja de estilo y luego abra el archivo tss_run.html en
su navegador.
Use los enlaces de navegación en la página para ver el contenido y el diseño de
las páginas de ciclismo y natación, y luego confirme que h1 y h2
Los títulos de estas páginas tienen formatos similares.
 
 ![image](https://user-images.githubusercontent.com/52549697/67697270-47f1d900-f976-11e9-8aa1-8d59fe7c012f.png)

![image](https://user-images.githubusercontent.com/52549697/67697301-5213d780-f976-11e9-9b44-f70ddd00e4a9.png)

Para especificar una familia de fuentes para el cuerpo de la página:
Regrese al archivo tss_styles.css en su editor.
Agregue el siguiente estilo a la regla de estilo para el elemento del cuerpo:

![image](https://user-images.githubusercontent.com/52549697/67697335-5fc95d00-f976-11e9-97c3-a71d5d9ef14b.png)
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador.
Vea las otras tres páginas en el sitio web para verificar que la fuente sans-serif sea
también se aplica al texto del cuerpo en esas páginas.
 
 ![image](https://user-images.githubusercontent.com/52549697/67697365-6b1c8880-f976-11e9-84d7-4ae49b9a1952.png)

 ![image](https://user-images.githubusercontent.com/52549697/67697401-753e8700-f976-11e9-8efa-583ee64ff644.png)
 
 ![image](https://user-images.githubusercontent.com/52549697/67697433-85eefd00-f976-11e9-97ee-95639672fdad.png)

Para instalar y usar una fuente web:
Regrese al archivo tss_styles.css en su editor.
Directamente después de la regla @charset en la parte superior del archivo, inserte lo siguiente regla @ font-face:
@font-face { 
font-family: Quicksand; 
src: url('Quicksand-Regular.woff') format('woff'),
 url('Quicksand-Regular.ttf') format('truetype'); 
}

![image](https://user-images.githubusercontent.com/52549697/67697457-9010fb80-f976-11e9-8c2e-88548103d459.png)
 
En la parte superior de la sección para Estilos de encabezado, inserte la regla de estilo:
h1, h2 {
 font-family: Quicksand, Verdana, Geneva, sans-serif; 
}

![image](https://user-images.githubusercontent.com/52549697/67697484-9d2dea80-f976-11e9-894b-a04ac0762c82.png)
 
Guarde sus cambios en el archivo y vuelva a cargar el archivo tss_home.html en su
navegador. 



Para establecer los tamaños de fuente de los elementos de la página:
Regrese al archivo tss_styles.css en su editor.
En la sección Estilos de encabezado, inserte el siguiente estilo como parte del estilo
regla para el selector h1, h2:
letter-spacing: 0.1em;

![image](https://user-images.githubusercontent.com/52549697/67697513-aae37000-f976-11e9-96c5-b8e2620ecaae.png)

 
Desplácese hacia abajo hasta la sección Estilos de navegación cerca de la parte inferior del archivo y inserte la siguiente regla de estilo para el texto de elementos ul anidados dentro de
elemento de navegación:
nav > ul {
 line-height: 2em; 
}
 
 ![image](https://user-images.githubusercontent.com/52549697/67697536-b3d44180-f976-11e9-8b78-fe4ecae735d9.png)


Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. Verifique que el espacio entre letras en los encabezados h1 y h2 tenga
ha aumentado y la lista de enlaces ahora está a doble espacio.
 
 ![image](https://user-images.githubusercontent.com/52549697/67697554-bdf64000-f976-11e9-985e-37efd4cacb0b.png)

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
 ![image](https://user-images.githubusercontent.com/52549697/67697575-c64e7b00-f976-11e9-8bdc-df5b2bb475e9.png)
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. 
Para aplicar un estilo de contorno:
Si tomaste un descanso después de la sesión anterior, asegúrate de que tss_styles.css
El archivo está abierto en su editor.
Desplácese hacia abajo a la sección Estilos de lista e inserte las siguientes reglas de estilo para
formatee listas ordenadas anidadas dentro del artículo del programa de estudios:

 ![image](https://user-images.githubusercontent.com/52549697/67697622-d8c8b480-f976-11e9-8247-b1fca4496a83.png)
 
Guarde sus cambios en el archivo y luego abra el archivo tss_run.html en su

Para eliminar los marcadores de las listas de navegación:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos de navegación y, dentro de la regla de estilo para la navegación> ul selector, agrega el estilo list-style-type: none;

 ![image](https://user-images.githubusercontent.com/52549697/67697652-e2eab300-f976-11e9-97ab-3f687e9f737f.png)
 
Guarde sus cambios en el archivo y luego abra el archivo tss_home.html en su
navegador. Verifique que no haya marcadores junto a los elementos de la lista de navegación en la columna izquierda.
 
 ![image](https://user-images.githubusercontent.com/52549697/67697673-ebdb8480-f976-11e9-884d-b82df7a949ec.png)
 
Vaya a las otras tres páginas en el sitio web y verifique que las listas de navegación en
Estas páginas tampoco tienen marcadores de lista.
 
 ![image](https://user-images.githubusercontent.com/52549697/67697716-fdbd2780-f976-11e9-9aa7-7cbe5cc0094b.png)


Para usar una imagen para un marcador de lista:
Regrese al archivo tss_styles.css en su editor.
En la parte superior de la sección Estilos de lista, inserte la siguiente regla de estilo:
article#about_tss ul { 
list-style-image: url(runicon.png);
 }

 ![image](https://user-images.githubusercontent.com/52549697/67697745-07df2600-f977-11e9-9e68-c71bd8375fc2.png)

Guarde sus cambios en el archivo y luego abra el archivo tss_home.html en su
navegador.
Para cambiar el relleno izquierdo utilizado en la lista de navegación:
Regrese al archivo tss_styles.css en su editor.
Localice la regla de estilo nav> ul en la sección Estilos de navegación e inserte el
Estilo padding-left: 5px;.
 
 ![image](https://user-images.githubusercontent.com/52549697/67697765-1299bb00-f977-11e9-8311-01c495fb955a.png)


Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. 
Para aumentar el margen superior:
Regrese al archivo tss_styles.css en su editor.
Directamente debajo de la regla de estilo para el selector nav> ul en los estilos de navegación sección, inserte la siguiente regla:
nav > ul > li.newgroup {
 margin-top: 20px; 
}

![image](https://user-images.githubusercontent.com/52549697/67697785-1c232300-f977-11e9-916a-446b7ef4f99a.png)
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en
su navegador Verifique que las entradas en la lista de navegación ahora estén divididas
en tres grupos: el primer grupo que contiene los enlaces del Tri y
Tener éxito en el sitio web de deportes; el segundo grupo que contiene enlaces a sitios web
en correr, andar en bicicleta y nadar; y el tercer grupo que contiene enlaces
a los sitios web de triatlón.
 
![image](https://user-images.githubusercontent.com/52549697/67697812-27764e80-f977-11e9-926d-495120e0e5bb.png)


Para cambiar el espacio de margen alrededor de las comillas de bloque:
Regrese al archivo tss_styles.css en su editor.
Localice la regla de estilo para el selector de bloque de comillas a un lado en el lado y
Sección Estilos Blockquote e inserte el margen: 20px 5px; estilo en el
regla de estilo.

![image](https://user-images.githubusercontent.com/52549697/67697830-30672000-f977-11e9-872d-4933e0eda496.png)
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegador. 


Para aplicar pseudo-clases a una lista desordenada:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos de lista en la parte inferior de la hoja de estilos, elimine el
artículo # about_tss regla de estilo ul que establece el marcador de imagen de estilo de lista y
reemplácelo con las siguientes tres reglas de estilo:

![image](https://user-images.githubusercontent.com/52549697/67697853-39f08800-f977-11e9-9f15-607e73d7eff3.png)
 

Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en
su navegador
Para aplicar pseudo-clases a enlaces de hipertexto:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos de navegación e inserte las siguientes reglas de estilo para
enlaces de hipertexto que han sido visitados o no visitados.
 
 ![image](https://user-images.githubusercontent.com/52549697/67697884-4543b380-f977-11e9-85cd-76b5032184e0.png)
 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su
navegue y desplace el puntero del mouse sobre los enlaces en la lista de navegación.

Para insertar comillas en comillas de bloque:
Regrese al archivo tss_styles.css en su editor.
Vaya a la sección Estilos aparte y de Blockquote y, dentro de la regla de estilo para
el selector de comillas de bloque aparte, inserte la siguiente propiedad de comillas para usar
comillas rizadas para las comillas:
quotes: "\201C" "\201D";Agregue las siguientes reglas de estilo para insertar comillas antes y después de cada
comilla de bloque en el elemento aparte:

![image](https://user-images.githubusercontent.com/52549697/67697902-4ecd1b80-f977-11e9-83be-4491eb238fcd.png)

 
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




