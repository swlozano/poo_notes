# El Diagrama UML de Uber

<div class="MaterialLecture"><div class="MaterialLecture-text"><p>Este es el diagrama que finalmente obtuvimos, aquí solo faltaría añadirle los atributos que posee cada clase.</p>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-21%20a%20la%28s%29%203.20.10-075bf981-504e-46b5-acb5-3d9bc67e8ea5.jpg" alt="Captura de pantalla 2019-01-21 a la(s) 3.20.10.png"></figure>
<p>Recopilemos todo lo que hemos aprendido para explicar los últimos detalles.</p>
<p>En primer lugar notarás que tenemos 3 tipos de flechas:</p>
<h2>Asociación</h2>
<figure><img src="https://static.platzi.com/media/user_upload/associacion-d2e1b691-b6e9-4854-85e2-d3ffdf0a9049.jpg" alt="associacion.png"></figure>
<p>Como su nombre lo dice, notarás que cada vez que esté referenciada este tipo de flecha significará que ese elemento contiene al otro en su definición. Si recuerdas la clase Car, este contenía una instancia de Driver. La flecha apuntará hacia la dependencia.</p>
<figure><img src="https://static.platzi.com/media/user_upload/car-driver-204d198e-60fa-4c57-a0d0-0668c0e011d7.jpg" alt="car-driver.png"></figure>
<h2>Herencia</h2>
<figure><img src="https://static.platzi.com/media/user_upload/herencia-2eb98d5e-bcad-4162-b236-aa87eba20e76.jpg" alt="herencia.png"></figure>
<p>Siempre que veamos este tipo de flecha se estará expresando la herencia.<br>
En nuestro diagrama tuvimos al menos tres familias conviviendo. La dirección de la flecha irá desde el hijo hasta el padre.</p>
<p><strong>Familia Car</strong></p>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-24%20a%20la%28s%29%201.24.30-ff45a4c0-dfa8-464b-8590-5d48cfa03eb5.jpg" alt="Captura de pantalla 2019-01-24 a la(s) 1.24.30.png"></figure>
<p><strong>Familia Account</strong><br>
<img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-24%20a%20la%28s%29%201.24.13-bc9edb69-8909-487b-9619-350dcb933638.jpg" alt="Captura de pantalla 2019-01-24 a la(s) 1.24.13.png"></p>
<p><strong>Familia Payment</strong><br>
<img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-24%20a%20la%28s%29%201.24.42-ef7679b6-3b93-45c1-a4d9-1d6a24f4aa2a.jpg" alt="Captura de pantalla 2019-01-24 a la(s) 1.24.42.png"></p>
<h2>Composición</h2>
<figure><img src="https://static.platzi.com/media/user_upload/composicion-1da1dd19-6925-42d9-9727-7fd8cb031b0c.jpg" alt="composicion.png"></figure>
<p>Pasemos a una de nuestras piezas claves, pues notarás en el centro del diagrama la clase <strong>Trip</strong> que está vinculada a User, Car, Route y Payment. La composición va a significar una asociación entre estas clases con la diferencia de que para que esta clase pueda vivir forzosamente necesita a las demás. Es decir que estas clases son obligatorias para que la clase Trip pueda existir, esta dependencia obligatoria podríamos expresarla en el método constructor de la clase Trip, pues para que un objeto pueda ser creado dependerá de que los demás existan.</p>
<figure><img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202019-01-24%20a%20la%28s%29%201.46.08-72aaa220-d916-4cae-9ac2-5a8ebe375b80.jpg" alt="Captura de pantalla 2019-01-24 a la(s) 1.46.08.png"></figure>
<p>Esta clase Trip poseerá la lógica más fuerte del negocio aquí será donde se concentrarán la mayor cantidad de clases.</p>
<p>Esto es todo nuestro diagrama de clases, que quedó totalmente expresado en nuestro proyecto.</p></div></div>
