# Describir y programar

### Introducción a la publicación Web, JavaScript y D3.js

La publicación de una visualización de datos en web nos exige [describir](https://es.wikipedia.org/wiki/Categoría:Lenguajes_de_descripción) y [programar](https://es.wikipedia.org/wiki/Anexo:Lenguajes_de_programación), utilizando lenguajes específicos para cada caso. Para describir tenemos los lenguajes <strong>HTML</strong> y <strong>CSS</strong>; y para programar tenemos, entre otros lenguajes, a <strong>JavaScript</strong>.

A los lenguajes de descripción mencionados arriba, sumaremos un dialecto: <strong>SVG</strong>. Y para simplificar el trabajo de programación, usaremos una biblioteca de JavaScript: <strong>D3.js</strong>.

#### 1. DESCRIBIR

**1.1. [HTML es <u>H</u>yper<u>T</u>ext <u>M</u>arkup <u>L</u>anguage</strong>](https://github.com/profesorfaco/describir-programar/wiki/HTML)**. Su bloque constructivo más básico es el [elemento](https://developer.mozilla.org/es/docs/Web/HTML/Elemento). Un [elemento](https://developer.mozilla.org/es/docs/Web/HTML/Elemento) es un contenido marcado con una etiqueta de apertura (`<etiqueta>`) y una etiqueta de cierre (`</etiqueta>`); aunque hay [elementos](https://developer.mozilla.org/es/docs/Web/HTML/Elemento) que no son más que una etiqueta.

En la primera o en la única etiqueta de cada [elemento](https://developer.mozilla.org/es/docs/Web/HTML/Elemento) es posible agregar uno o varios [atributos](https://developer.mozilla.org/es/docs/Web/HTML/Atributos), los que nos permitirán caracterizar o identificar al [elemento](https://developer.mozilla.org/es/docs/Web/HTML/Elemento) en cuestión. 
                
**1.2. [SVG es Scalable Vector Graphics](https://github.com/profesorfaco/describir-programar/wiki/SVG)**. Este dialecto ofrece una serie de elementos gráficos vectoriales, en los que se deben usar atributos para establecer sus características básicas, incluyendo su posición en un plano. Por ejemplo, puedo definir que quiero un círculo (circle), cuyo centro esté en una coordenada horitonzal (cx) y otra vertical (cy), con cierto radio (r): `<circle cx="10" cy="10" r="10"/>`

**1.3. [CSS es Cascading Style Sheets](https://github.com/profesorfaco/describir-programar/wiki/CSS)**. Su bloque constructivo más básico es la regla. Cada regla se inicia con su(s) [selector(es)](https://developer.mozilla.org/es/docs/Web/CSS/Referencia_CSS#Selectores), para luego contener, entre paréntesis de llave, determinadas [propiedades](https://www.w3schools.com/cssref/default.asp): `selector{propiedad:valor;}`
                
A través de CSS puedo describir el modo en que deben verse los elementos de HTML y SVG en la ventana del navegador. Si mediante elementos HTML y SVG defino qué se ve, mediante reglas CSS defino el cómo debe verse aquello cuando sea visto, con la posibilidad de establecer modos específicos para dispositivos específicos.

#### 2. PROGRAMAR

**2.1. [JavaScript](https://github.com/profesorfaco/describir-programar/wiki/JavaScript)** es un lenguaje de programación que permite realizar actividades complejas en una página web en la interacción con el [Modelo de Objetos del Documento (Document Object Model; DOM)](https://es.wikipedia.org/wiki/Document_Object_Model) de la misma.

Cuando le indicas al navegador "Ver el código fuente de la página", lo que obtienes es la descripción de tal página, algo idéntico a lo que se pudo escribir en un [Editor de código fuente](https://es.wikipedia.org/wiki/Editor_de_código_fuente). Ese escrito es analizado por el navegador y un resultado de tal análisis es el DOM, y esto último es lo que se manipula con JavaScript. Dicho de un modo simple, el DOM es donde la máquina hace cosas y Javascript es el lenguaje que le indica a la máquina qué cosas hacer.

**2.2. [D3.js es <u>D</u>ata <u>D</u>riven <u>D</u>ocument</a>](https://github.com/profesorfaco/describir-programar/wiki/D3.js)** es una de [muchas bibliotecas de JavaScript](https://www.javascripting.com/). Su diferencia, y razón para explorarla, es que nos facilita, además de la manipulación del DOM, el trabajo con datos, CSS y SVG.
 
- - - - - - - - - - - - - - - - - 

### Clase 1: Miércoles 8 de mayo, 2019

[Retomando la clase sobre datos](https://profesorfaco.github.io/describir-programar/)

[HTML y CSS en 5 pasos](https://profesorfaco.github.io/describir-programar/step-by-step/html-css/step-1.html)

[SVG y D3.js en 5 pasos](https://profesorfaco.github.io/describir-programar/step-by-step/svg-d3/step-1.html)

- - - - - - - - - - - - - - - - - 

### Clase 2: Sábado 11 de mayo, 2018

Más sobre D3.js

- - - - - - - - - - - - - - - - - 
