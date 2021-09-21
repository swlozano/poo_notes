# Otros tipos de Herencia

<div class="MaterialLecture-text"><p>A partir de ahora las clases que estén siendo heredades las llamaremos familias.</p>
<p>Acabamos de aplicar herencia a la familia <strong>Car</strong>. Ahora apliquémosla a la familia <strong>Payment</strong>.</p>
<p>En clases anteriores te mencioné que otro punto de partida que puedes tomar para aplicar herencia es del hecho de que hay clases que lógicamente deberían estar en una familia, como es el caso de Payment.</p>
<p>Repasemos el diagrama de Payment</p>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-21%20a%20la%28s%29%2012.21.03-6c3f1263-88f7-44db-a123-ba70c028069c.jpg" alt="Captura de pantalla 2019-01-21 a la(s) 12.21.03.png"></figure>
<p>Notarás que a nivel de código parece inservible pero cuando estemos en el caso de uso Pagar un Viaje, probablemente en ese momento no sabremos cuál es el método de pago, y necesitemos ingresar un dato lo suficientemente genérico que conceptualmente nos dé la información que necesitamos, en este caso que es un Payment. Este es un tipo de Polimorfismo y uno de los principios SOLID del software que obedece a la Inyección de Dependencias. Lo veremos más adelante a detalle.</p>
<p>Ahora nos faltará crear las clases y aplicar su herencia.</p></div>
