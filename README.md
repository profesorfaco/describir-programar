# Describir y programar

Diplomado en Visualización de Datos UC, 2019

Miércoles 8 de mayo + Sábado 11 de mayo

Profesor Felipe Cortez / http://profesor.faco.cl / profesor@faco.cl

### Una introducción a la publicación Web, JavaScript y D3.js

La publicación de una visualización de datos en web nos exige <a href="https://es.wikipedia.org/wiki/Categoría:Lenguajes_de_descripción" title="Categoría:Lenguajes de descripción - Wikipedia">describir</a> y <a href="https://es.wikipedia.org/wiki/Anexo:Lenguajes_de_programación" title="Anexo:Lenguajes de programación - Wikipedia">programar</a>, utilizando lenguajes específicos para cada caso. Para describir tenemos los lenguajes <strong>HTML</strong> y <strong>CSS</strong>; y para programar tenemos, entre otros lenguajes, a <strong>JavaScript</strong>.

A los lenguajes de descripción mencionados arriba, sumaremos un dialecto: <strong>SVG</strong>. Y para simplificar el trabajo de programación, usaremos una biblioteca de JavaScript: <strong>D3.js</strong>.

#### 1. Describir

**1.1. <a href="https://github.com/profesorfaco/describir-programar/wiki/HTML" title="Wiki del Repositorio" target="_blank">HTML es <u>H</u>yper<u>T</u>ext <u>M</u>arkup <u>L</u>anguage</strong></a>**. Su bloque constructivo más básico es el <a href="https://developer.mozilla.org/es/docs/Web/HTML/Elemento" target="_blank" title="Referencia de Elementos HTML">elemento</a>. Un <a href="https://developer.mozilla.org/es/docs/Web/HTML/Elemento" target="_blank" title="Referencia de Elementos HTML">elemento</a> es un contenido marcado con una etiqueta de apertura (<code>&lt;etiqueta&gt;</code>) y una etiqueta de cierre (<code>&lt;/etiqueta&gt;</code>); aunque hay <a href="https://developer.mozilla.org/es/docs/Web/HTML/Elemento" target="_blank" title="Referencia de Elementos HTML">elementos</a> que no son más que una etiqueta.

En la primera o en la única etiqueta de cada <a href="https://developer.mozilla.org/es/docs/Web/HTML/Elemento" target="_blank" title="Referencia de Elementos HTML">elemento</a> es posible agregar uno o varios <a href="https://developer.mozilla.org/es/docs/Web/HTML/Atributos" title="Referencia de Atributos HTML" target="_blank">atributos</a>, los que nos permitirán caracterizar o identificar al <a href="https://developer.mozilla.org/es/docs/Web/HTML/Elemento" target="_blank" title="Referencia de Elementos HTML">elemento</a> en cuestión. 
                
**1.2. <a href="https://github.com/profesorfaco/describir-programar/wiki/SVG" title="Wiki del Repositorio" target="_blank">SVG es Scalable Vector Graphics</a>**. Este dialecto ofrece una serie de elementos gráficos vectoriales, en los que se deben usar atributos para establecer sus características básicas, incluyendo su posición en un plano. Por ejemplo, puedo definir que quiero un círculo (circle), cuyo centro esté en una coordenada horitonzal (cx) y otra vertical (cy), con cierto radio (r): `&lt;circle cx="10" cy="10" r="10"/&gt;`

**1.3. <a href="https://github.com/profesorfaco/describir-programar/wiki/CSS" title="Wiki del Repositorio" target="_blank">CSS es Cascading Style Sheets</a>**. Su bloque constructivo más básico es la regla. Cada regla se inicia con su(s) <a href="https://developer.mozilla.org/es/docs/Web/CSS/Referencia_CSS#Selectores" target="_blank" title="Referencia CSS">selector(es)</a>, para luego contener, entre paréntesis de llave, determinadas <a href="https://www.w3schools.com/cssref/default.asp" target="_blank" title="CSS Properties">propiedades</a>: `selector{propiedad:valor;}`
                
A través de CSS puedo describir el modo en que deben verse los elementos de HTML y SVG en la ventana del navegador. Si mediante elementos HTML y SVG defino qué se ve, mediante reglas CSS defino el cómo debe verse aquello cuando sea visto, con la posibilidad de establecer modos específicos para dispositivos específicos.

#### 2. Programar

**2.1. <a href="https://github.com/profesorfaco/describir-programar/wiki/JavaScript" title="Wiki del Repositorio" target="_blank">JavaScript</a>** es un lenguaje de programación, se usa para escribir funciones embebidas o incluidas en páginas HTML y que interactúan con el Document Object Model (DOM o Modelo de Objetos del Documento) de la página

Cuando le indicas al navegador "Ver el código fuente de la página", lo que obtienes es la descripción de tal página, algo idéntico a lo que se pudo escribir en un <a href="https://es.wikipedia.org/wiki/Editor_de_código_fuente" title="Wikipedia" target="_blank">Editor de código fuente</a>. Ese escrito es analizado por el navegador y un resultado de tal análisis es el <a href="https://es.wikipedia.org/wiki/Document_Object_Model" title="Wikipedia" target="_blank">Document Object Model (DOM)</a>; esto último es lo que se manipula con JavaScript. Dicho de un modo simple, el DOM es donde la máquina hace cosas y Javascript es el lenguaje que le indica a la máquina qué cosas hacer.

**2.2. <a href="https://github.com/profesorfaco/describir-programar/wiki/D3.js" title="Wiki del Repositorio" target="_blank">D3.js es <u>D</u>ata <u>D</u>riven <u>D</u>ocument</a>**. Es una <a href="https://www.javascripting.com/" target="_blank" title="JavaScripting.com | The Database of JavaScript Libraries">de muchas bibliotecas de JavaScript</a>. Su diferencia, y razón para explorarla, es que nos facilita, además de la manipulación del DOM, el trabajo con datos, CSS y SVG.
 
- - - - - - - - - - - - - - - - - 

### Clase 1: 

[Retomando la clase sobre datos](https://profesorfaco.github.io/describir-programar/)

[HTML y CSS en 5 pasos](https://profesorfaco.github.io/describir-programar/step-by-step/html-css/step-1.html)

[SVG y D3.js en 5 pasos](https://profesorfaco.github.io/describir-programar/step-by-step/svg-d3/step-1.html)

- - - - - - - - - - - - - - - - - 

### Clase 2:

Más sobre D3.js
