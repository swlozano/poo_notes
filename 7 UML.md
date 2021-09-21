# UML

<div class="MaterialLecture-text"><p>Como ya viste UML significa Unified Modeling Language el cual es un lenguaje estándar de modelado de sistemas orientados a objetos.</p>
<figure><img src="https://static.platzi.com/media/user_upload/220px-UML_logo.svg-ffd3a6a7-ac1d-43df-8648-265767507c9a.jpg" alt="220px-UML_logo.svg.png"></figure>
<p>Esto significa que tendremos una manera gráfica de representar una situación, justo como hemos venido viendo. A continuación te voy a presentar los elementos que puedes utilizar para hacer estas representaciones.</p>
<p>Las <strong>clases</strong> se representan así:</p>
<figure><img src="https://static.platzi.com/media/user_upload/clase-1897e6cf-84b3-4432-926b-aff4fc4db122.jpg" alt="clase.png"></figure>
<p>En la parte superior se colocan los atributos o propiedades, y debajo las opera	ciones de la clase. Notarás que el primer caracter con el que empiezan es un símbolo. Este denotará la visibilidad del atributo o método, esto es un término que tiene que ver con Encapsulamiento y veremos más adelante a detalle.</p>
<p>Estos son los niveles de <strong>visibilidad</strong> que puedes tener:</p>
<p><strong>-</strong> private<br>
<strong>+</strong> public<br>
<strong>#</strong> protected<br>
<strong>~</strong> default</p>
<p>Una forma de representar las relaciones que tendrá un elemento con otro es a través de las flechas en UML, y aquí tenemos varios tipos, estos son los más comunes:</p>
<h2>Asociación</h2>
<figure><img src="https://static.platzi.com/media/user_upload/associacion-d2e1b691-b6e9-4854-85e2-d3ffdf0a9049.jpg" alt="associacion.png"></figure>
<p>Como su nombre lo dice, notarás que cada vez que esté referenciada este tipo de flecha significará que ese elemento contiene al otro en su definición. La flecha apuntará hacia la dependencia.</p>
<figure><img src="https://static.platzi.com/media/user_upload/uml-relacion-asociacion-99b916c6-1f80-4b61-889a-ebf6e74f4f23.jpg" alt="uml-relacion-asociacion.jpg"></figure>
<p>Con esto vemos que la ClaseA está asociada y depende de la ClaseB.</p>
<h2>Herencia</h2>
<figure><img src="https://static.platzi.com/media/user_upload/herencia-2eb98d5e-bcad-4162-b236-aa87eba20e76.jpg" alt="herencia.png"></figure>
<p>Siempre que veamos este tipo de flecha se estará expresando la herencia.<br>
La dirección de la flecha irá desde el hijo hasta el padre.</p>
<figure><img src="https://static.platzi.com/media/user_upload/herencia-clases-53cb3117-def7-433f-adc5-4ad183d6b5e7.jpg" alt="herencia-clases.png"></figure>
<p>Con esto vemos que la ClaseB hereda de la ClaseA</p>
<h2>Agregación</h2>
<figure><img src="https://static.platzi.com/media/user_upload/agregacion-6489d946-cc06-4e3c-a976-f6435531b4f2.jpg" alt="agregacion.png"></figure>
<p>Este se parece a la asociación en que un elemento dependerá del otro, pero en este caso será: Un elemento dependerá de muchos otros. Aquí tomamos como referencia la multiplicidad del elemento. Lo que comúnmente conocerías en Bases de Datos como Relaciones uno a muchos.</p>
<figure><img src="https://static.platzi.com/media/user_upload/uml-relacion-agregacion-adb20be8-d6c2-41d1-b002-2cfa37639240.jpg" alt="uml-relacion-agregacion.jpg"></figure>
<p>Con esto decimos que la ClaseA contiene varios elementos de la ClaseB. Estos últimos son comúnmente representados con listas o colecciones de datos.</p>
<h2>Composición</h2>
<figure><img src="https://static.platzi.com/media/user_upload/composicion-1da1dd19-6925-42d9-9727-7fd8cb031b0c.jpg" alt="composicion.png"></figure>
<p>Este es similar al anterior solo que su relación es totalmente compenetrada de tal modo que conceptualmente una de estas clases no podría vivir si no existiera la otra.</p>
<figure><img src="https://static.platzi.com/media/user_upload/uml-relacion-composicion-2d4cb1fa-5422-44e3-849b-3a3e2d276733.jpg" alt="uml-relacion-composicion.jpg"></figure>
<p>Con esto terminamos nuestro primer módulo. Vamos al siguiente para entender cómo podemos hacer un análisis y utilizar estos elementos para construir nuestro diagrama de clases de Uber.</p>
</div>
