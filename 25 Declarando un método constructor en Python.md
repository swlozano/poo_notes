# Declarando un método constructor en Python

<div class="MaterialLecture-text"><p>En Python encontrarás un concepto denominado <strong>Métodos Mágicos</strong>, estos métodos son llamados automática y estrictamente bajo ciertas reglas. El método constructor en Python forma parte de esta familia de métodos y como aprendimos en la clase anterior lo declaramos usando <code>__init__</code>, aunque si nos ponemos estrictos este método no construye el objeto en sí. El encargado de hacer esto es <code>__new__</code> y el método <code>__init__</code> se encargará de personalizar la instanciación de la clase, esto significa que lo que esté dentro de <code>__init__</code> será lo primero que se ejecute cuando se cree un objeto de esta clase.</p>
<p>Para nuestro proyecto tenemos la necesidad de que algunas variables se inicialicen obligatoriamente cuando ocurra la instanciación. Así que declaremos el método <code>__init__</code> en las clases de nuestro proyecto con las propiedades obligatorias.</p>
<p>Para la clase Account quedaría algo así, notarás que usamos la palabra clave <strong>self</strong>, esta es muy parecida a lo que venimos trabajando a otros lenguajes con <strong>this</strong>. Y como su nombre lo dice hace referencia a los datos que componen la clase, en este caso <code>self.name</code> está llamando al atributo name que se encuentra en la línea 3 de la clase y, le está asignando el dato que se pasa en el método <code>__init__</code> de la línea 8.</p>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-21%20a%20la%28s%29%201.16.43-c55250b1-a09b-4025-b263-c09ae7364008.jpg" alt="Captura de pantalla 2019-01-21 a la(s) 1.16.43.png"></figure>
<p>Ahora veamos la clase Car:</p>
<figure><img src="https://static.platzi.com/media/user_upload/imagen-f683eb2d-6a0a-44c7-a32c-92a0cbce962b.jpg" alt="imagen.png"></figure>
<p>Lo que notarás de diferente es que cambiamos el tipo de dato de <strong>driver</strong>, ahora es de tipo Account y como ves está solicitando los dos datos obligatorios para instanciar un objeto de este tipo. Esto lo verás más en acción en el próximo fragmento de código del archivo <code>main.py</code>. Además, mucho ojo, en la primera línea observamos que es importante importar la clase para poderla usar.</p>
<p>Nuestro archivo <code>main.py</code> ahora se verá así:</p>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-21%20a%20la%28s%29%201.17.11-72be8450-fa7f-4030-9987-ffb098c4d46c.jpg" alt="Captura de pantalla 2019-01-21 a la(s) 1.17.11.png"></figure>
<p>Observa que estamos importando las dos clases que usaremos y las estamos instanciando en los métodos constructores.</p>
<p>Los resultados serán los siguientes:</p>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-21%20a%20la%28s%29%201.14.06-613a190d-a678-490c-a010-81150b4b883f.jpg" alt="Captura de pantalla 2019-01-21 a la(s) 1.14.06.png"></figure>
<p>El código de este ejemplo lo encuentras en este enlace:<br>
<a href="https://github.com/anncode1/Curso-POO-Platzi/tree/3.2.ConstructorPython" target="_blank" rel="noopener">https://github.com/anncode1/Curso-POO-Platzi/tree/3.2.ConstructorPython</a></p>
<h2>Reto 3.</h2>
<p>Ahora que ya viste cómo creamos un método constructor en Python, mira esta clase <a href="https://platzi.com/clases/2034-php-poo/32133-polimorfismo/" target="_blank" rel="noopener">https://platzi.com/clases/2034-php-poo/32133-polimorfismo/</a> y <strong>hazlo también para PHP</strong>. Compártenos tus resultados en la sección de discusiones.</p>
</div>
