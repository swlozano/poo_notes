# Definiendo Clases en JavaScript

<div class="MaterialLecture-text"><p>Si estás interesado en aprender JavaScript desde ahora debes saber que el concepto de clases no existía como tal hasta el nuevo estándar EcmaScript 6. El reto de encontrar sistemas construidos con este estándar es alto por esa razón te explicaré cuál fue por mucho tiempo su equivalente.</p>
<p>Los Prototipos fue la forma de crear clases en JavaScript y las representaremos partiendo de la declaración de una función.</p>
<p>Creemos nuestras clases:</p>
<ul>
<li>Account</li>
<li>Car</li>
<li>Payment</li>
<li>Route</li>
</ul>
<p>Para esto crearemos el siguiente sistema de archivos dentro de la carpeta JS de nuestro proyecto:</p>
<ul>
<li>Account.js</li>
<li>Car.js</li>
<li>Payment.js</li>
<li>Route.js</li>
<li>index.js</li>
</ul>
<p>El archivo index.js será el lugar equivalente al punto de entrada de la aplicación donde estaremos declarando nuestros objetos basado en las clases. Para esta clase lo dejaremos en blanco.</p>
<p>Ahora veamos el código archivo por archivo:</p>
<h2>Account.js</h2>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-13%20a%20la%28s%29%202.56.24-f11c0607-b11e-425f-aafe-05a11ae8c3f8.jpg" alt="Captura de pantalla 2019-01-13 a la(s) 2.56.24.png"></figure>
<h2>Car.js</h2>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-13%20a%20la%28s%29%202.56.34-a046c5f8-3e4e-4339-88a2-f4a610295155.jpg" alt="Captura de pantalla 2019-01-13 a la(s) 2.56.34.png"></figure>
<h2>Payment.js</h2>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-13%20a%20la%28s%29%202.56.41-4f859f05-797a-42da-a12d-899d99abb08c.jpg" alt="Captura de pantalla 2019-01-13 a la(s) 2.56.41.png"></figure>
<h2>Route.js</h2>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-13%20a%20la%28s%29%202.56.56-09463e4b-c572-4803-9ed7-4232bcfc9589.jpg" alt="Captura de pantalla 2019-01-13 a la(s) 2.56.56.png"></figure>
<p>Este es el enlace del código del proyecto: <a href="https://github.com/anncode1/Curso-POO-Platzi/tree/f5725787165b36cae579f94e428068039b554b0b/JS" target="_blank" rel="noopener">https://github.com/anncode1/Curso-POO-Platzi/tree/f5725787165b36cae579f94e428068039b554b0b/JS</a></p>
<p>En este código notarás el uso de la palabra reservada <strong>this</strong>. Normalmente cuando usamos la sintaxis punto siempre lo haremos a partir de un objeto instanciado, en este caso con this, se hace una simulación al objeto en cuestión, a pesar de que en ese momento visualmente sigue siendo una clase.</p>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-13%20a%20la%28s%29%202.56.56-09463e4b-c572-4803-9ed7-4232bcfc9589.jpg" alt="Captura de pantalla 2019-01-13 a la(s) 2.56.56.png"></figure>
<p>Digamos que se adelanta un poco al momento de ejecución y visualiza al objeto con sus atributos, más adelante verás la forma en que podemos asignar datos a un atributo del objeto en otros lenguajes y verás que es exactamente la misma sintaxis.</p>
<p>Si intentaramos poner this. en el momento de ejecución nos traería un listado de todos los componentes de la clase que en este caso son solo estos tres: id, init y end.</p>
<p>This hace referencia al objeto instanciado. Para comprender del todo esta última frase mira la siguiente clase donde hablamos de objetos.</p>
<h2>Reto.</h2>
<p>En la carpeta de nuestro proyecto PHP declara estas mismas clases: Puedes utilizar esta clase de apoyo: <a href="https://platzi.com/clases/1338-php/12929-programacion-orientada-a-objetos1172/" target="_blank" rel="noopener">https://platzi.com/clases/1338-php/12929-programacion-orientada-a-objetos1172/</a><br>
Inténtalo y compártenos tus resultados, compáralos con tus compañeros.</p></div>
