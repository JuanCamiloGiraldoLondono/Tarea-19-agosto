1.Un sistema modular es aquel que permite subdividir un sistema en partes más
pequeñas haciendo que el problema a resolver sea mucho más sencillo, todos estos
módulos se encuentran conectados entre sí. El bajo acople hace referencia a la
independencia que se tiene entre las diferentes partes del código, lo cual es
importante ya que al suceder un cambio dentro del sistema la solución se basa en
cambiar cosas específicas sin realizar muchos cambios en el código.

2. La alta cohesión es importante ya que permite tener funciones que realizan acciones
específicas, al tener esto permite que si se necesita realizar un cambio vaya
directamente a la función que debo cambiar sin necesidad de afectar otras acciones
que no estén relacionadas pero que se encuentren en la misma función.

3. Un monolito es una arquitectura que utiliza un único código para sus servicios o
ejecutar diferentes funciones. Por lo general estas arquitecturas son más sencillas
de utilizar aunque trae ciertas complicaciones, aunque tiene ciertas características
positivas como que son arquitecturas que permiten un fácil despliegue, son de baja
latencia y son fáciles de someter a pruebas.

4. Diseñar un sistema como monolito no es recomendable ya que posee varias
desventajas, por lo cual se hace más adecuado el uso de microservicios. Algunas de
las desventajas que podemos encontrar son: Son complejos de mantener ya que a
medida que aumente el tamaño de la aplicación cada vez va a ser más costoso
mantenerlo si no se tiene una buena arquitectura modular y de bajo acople, es difícil
escalarlos ya que para que esto sea posible es necesario desplegar toda la
aplicación lo cual hace que se requiera más infraestructura, por último corremos el
riesgo de que si falla un punto del monolito puede fallar toda la aplicación.
