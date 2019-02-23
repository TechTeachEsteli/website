---
identifier: "cursos"
title:	 "Crear tu primer sitio web: HTML, CSS y Bootstrap"
description: |
  ¿Piensas que desarrollar un sitio web es dificil, require conocimiento de antemano o se necesita programas caros para hacerlo? ¡Ninguno de los anteriores es el caso! Todos podemos aprender a crear un sitio web y sólo se necesita software que es gratis. Además, sólo tienes que saber cómo utilizar una computadora y puedes empezar. 
  
  En este curso aprendedes a utilizar HTML y CSS, los dos lenguajes de programación en los que están basados todos los sitios web. Después seguimos con Bootstrap, un framework muy popular que ayuda en desarrollar páginas web responsive.
intro: |
  En este curso vas tu página web personal, con el contenido que quieras. 
  
  Vamos a empezar con HTML para dar estructura y textos al sitio web. Después añadimos colores y más estilos con CSS. Para crear páginas web responsive utilizaremos Bootstrap. Al final de este curso podrás crear una página web moderna y subirla al internet (gratis).
  
  Si utilizas una laptop de TechTeach por favor ¡no descargue nada! Esas laptops ya tienen todos los programas necesarios para completar los cursos.
image: "images/tabs/Techteachfrontend-01.png"
order: 0
---
<details>
    <summary class="course-part">Introducción y HTML</summary>

Vamos a utilizar un curso gratis que está en ___openclassrooms___ y combinamos el contenido de ese curso con tareas que encuentras aquí. Si quieres puedes preguntar una TechTeacher que te revise la tarea antes de seguir adelante, pero si la tarea no dice explícitamente que lo hagas, no es necesario (pero possible). 

___Programación sólo se puede aprender por práctica.___ Si quieres, puedes tomar notas durante el curso, pero lo más, más, más importante es que practiques. Cuando explican algo nuevo de HTML o CSS y dan un ejemplo, inténtalo tú mism@ también. Primero puedes seguir exactamente el ejemplo, y después cambiar ciertas cosas para practicar más.  

<details>
     <summary class="clase">Parte 1</summary>
     
## Cómo se construyen sitios web y los primeros pasos con HTML
1. Lee la [introducción](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3339706-como-se-construyen-los-sitios-web). No es necesario tomar notas ni aprender todo palabra por palabra; sólo es para que tengas una impresión de cómo funciona todo. 
* Si tienes tu propia laptop es recomendable descargar Chrome y Sublime Text (como recomiendan en la introducción). Las laptops de TechTeach ya tienen esos programas, entonces por favor no descargue nada si estas en una de ellas.
* Crea una carpeta que se llama "TechTeach HTML CSS" + tu nombre. Es ahí donde vas a guardar los documentos que vas a hacer durante este curso. 
* [Sigue con esta clase del curso](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3339876-vuestra-primera-pagina-web-en-html). Practica durante la clase y haga la tarea 1 después. 
  
### Tarea 1 
1. Crea una carpeta que se llama "Parte 1". Guarde aquí los archivos de las clases 1,2 y 3.  
* Haz &lt;&lt;inspeccionar elemento>> en la página de [Claro](https://www.claro.com.ni/).
* Crea una carpeta que se llama __clase1__ con un archivo __HTMLclase1.html__ y haga una página que tiene: 
    1. título
    * un comentario en el código
* Abre la página en Chrome u otro návegador y muestrá tu página a una TechTeacher.

</details>

  <details>
     <summary class="clase">Parte 2</summary>
     
## Párrafos, listas y texto resaltado
1. [Sigue con esta clase del curso](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3340049-organizar-el-texto)

### Tarea 2
1. Crea una carpeta que se llama __clase2__ con un archivo __HTMLclase2.html__ y haga una página que tiene: 
   1. varios niveles de título con párrafos
   * texto resaltado con strong, em y mark
   * una lista ordenada
   * una lista no ordenada 
</details>

<details>
     <summary class="clase">Parte 3</summary>
     
## Enlaces y imágenes
1. [Sigue con esta clase sobre enlace](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3340161-crear-enlaces)
2. [Esta clase sobre imagines](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3340308-imagenes)

### Tarea 3
1. Crea una carpeta que se llama __clase3__ con un archivo __HTMLclase3.html__ y haz una página que tiene: 
   1. un enlace a la página de TechTeach Estelí
   * un enlace que salta a otra parte de la misma página. Ojo: la página tiene que tener bastante texto para poder ver el movimiento. Si no tienes suficiente inspiración para el texto en tu página, o no quieres perder tiempo en eso, puedes utilizar _Lorem Ipsum_;  un texto que sirve sólo para rellenar un espacio. Lee una explicación y encuentra el Lorem Ipsum [aquí](https://loremipsum.io/es/).
   * por lo menos 2 imágenes (buscalas en internet)
   * una imágen que tiene figcaption 
</details>
</details>


<details>
    <summary class="course-part">CSS</summary>

<details>
     <summary class="clase">Parte 4</summary>
     
## Introducción a CSS, color de texto y fondo
1. Cree una carpeta que se llama "Parte 2". Guarda aquí los archivos de las clases 4,5 y 6.
* Sigue [esta clase](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3340579-configurar-css). Haga una carpeta "practica clase 4" para poner los archivos que haces durante la clase para practicar.
* Sigue [esta clase también](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3341935-color-y-fondo)

### Tarea 4a

1. Crea una carpeta que se llama __clase4a__
* Copia el archivo __HTMLclase2.html__ y cambia el nombre a __HTMLclase4a.html__. 
* Haz un archivo __style.css__.
* En el head del html pon &lt;link rel="stylesheet" href="style.css" /> para asociar el css con el html.
* Añadir a varios párrafos un id (invente cualquier nombre para el id).
* Utilizando css, cambia los colores de texto ("color" en css) y colores de fondo ("background-color" en css). Utiliza ambas tecnicas de seleccionar por class y por id. 

### Tarea 4b
1. Crea una carpeta que se llama __clase4b__
* Copia el archivo __HTMLclase3.html__ y cambia el nombre a __HTMLclase4b.html__.
* Haga un archivo __style.css__.
* En el head del html pon &lt;link rel="stylesheet" href="style.css" /> para asociar el css con el html.
* Utilizando css da una imágen de fondo y haga un párrafo transparante

</details>

<details>
     <summary class="clase">Parte 5</summary>
     
## Dar formato al texto

1. Sigue [esta clase](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3340915-dar-formato-al-texto)

### Tarea 5

1. Crea una carpeta que se llama __clase5__
* Copia el archivo __HTMLclase2.html__ y cambia el nombre a __HTMLclase5.html__. 
* Haz un archivo __style.css__.
* En el head del html pon &lt;link rel="stylesheet" href="style.css" /> para asociar el css con el html.
* Añadir a varios párrafos un id (inventa cualquier nombre para el id).
* Dar formato al texto con las propiedades CSS que aprendiste en la clase; font-size, font-family, font-style, font-weight, text-decoration, text-align y float. Utiliza ambas tecnicas de seleccionar por class y por id.

</details>

<details>
     <summary class="clase">Parte 6</summary>
     

## Bordes y sombreado

1. Sigue [esta clase](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3343845-bordes-y-sombreado)

### Tarea 6

1. Crea una carpeta que se llama __clase6__
* Copia los archivos de la tarea anteroir y cambia el nombre del archivo html a __HTMLclase6.html__.
* Aplica lo que aprendiste en esta clase, utilizando las propiedades CSS border, border-radius, box-shadow, text-shadow. 
 
</details>

<details>
  <summary class="clase">Parte 7</summary>
  
## Crear apariencias dinamicas

1. Sigue [esta clase](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3344112-crear-apariencias-dinamicas)

### Tarea 7

1. Crea una carpeta que se llama __clase7__
* Copia el archivo __HTMLclase3.html__ y cambia el nombre a __HTMLclase7.html__. Haz un archivo __style.css__ y asocia el html con ese archivo css.
* Aplica a los enlaces lo que aprendiste en esta clase, utilizando las propiedades CSS :hover, :active, :visited y :focus. 
 
</details>

<details>
     <summary class="clase">Parte 8</summary>
     
## Estructurar tu página

1. Sigue [esta clase](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3344418-estructurar-tu-pagina)

### Tarea 8

1. Crea una carpeta que se llama __clase8__
* Crea una página utlizando todos los elementos que aparecieron en la clase. Para el contenido puedes utilizar [Ipsum lorem](https://loremipsum.io/es/).

</details>

<details>
     <summary class="clase">Parte 9</summary>
     
    
## El modelo de cajas

1. Sigue [esta clase](https://openclassrooms.com/en/courses/3339201-aprende-a-crear-tu-propio-sitio-web-con-html5-y-css3/3344652-el-modelo-de-cajas)

### Tarea 9

1. Crea una carpeta que se llama __clase9__
* Copia los archivos de la tarea anteroir y cambia el nombre del archivo html a __HTMLclase9.html__.
* Aplica todo lo que aprendiste en esta clase
 
</details>

</details>
 
<details>
     <summary class="course-part">Bootstrap</summary>
     Los detalles siguen.
</details>

<details>
     <summary class="course-part">Subir tu página al internet con GitHub</summary>
     Los detalles siguen.
</details>
