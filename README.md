# ejercicio_patrones2
Patron: Command

-Descripción (lo que intenté hacer):
La forma de controlar al personaje que en este caso es un cubo, es mediante la utilización de comandos en vez de estar todo anclado al script del player. 
Se usa el patrón elegido para separar las acciones de input de las acciones mismas de movimiento. 

-Problemática con la que nos encontraríamos si no aplicaramos el patrón: 
Sería un código más dificil de mantener ya que si se quisieran agregar nuevas acciones o si se quisieran modificar los inputs se tendrían que modificar varias partes del código lo que complicaría la tarea innecesariamente. 

-El patrón soluciona la problemática ya que permite que cada accion sea tratada como un objeto dentro del código, lo que permite mejorar la flexibilidad del código un poco por lo que dije arriba. 

-Ventajas: 
Por su flexibiliad y el desacoplamiento hace que el código sea fácil de mantener. Además, se pueden agregar nuevos comandos sin necesidad de modificar los existentes. 
Permite implementar operaciones reversibles ya que los comandos pueden ser almacenados y revertidos. 

-Desventajas:
No es tan fácil guardar el estado de una aplicación porque parte de ella puede ser privada. 
Alto consumo de memoria RAM debido al guardado de copias de seguridad lo cual consume muchos recursos. 



