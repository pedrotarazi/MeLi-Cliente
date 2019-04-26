# MeLi-Cliente

Crear una aplicación CLIENTE que consuma la API del ejercicio 2.

La aplicación debe ofrecer un formulario de carga (con datos validados) que permita
definir una LONGITUD, una LATITUD, los parámetros obligatorios y opcionales de
Agencies API, y un selector con los criterios de orden aceptados.

Al enviar dicho formulario, deben desplegarse los resultados de las agencias cercanas
en un formato amigable (no JSON) con los datos más relevantes e informativos, para un
consumidor, de cada una de las agencias.

Incorporar en el listado dos iconos para cada agencia: (LIKE) (UNLIKE). Si el usuario
acciona el icono LIKE, la agencia se guarda en la base de datos. Si ya está guardada el
sistema devolverá un mensaje que le informará al usuario que ya es una agencia
recomendada. Si el usuario acciona el icono UNLIKE, la agencia, si está guarda, se borrará
de la base de datos, informando al usuario que ha dejado de ser una agencia
recomendada, si no estaba guardada, se informará al usuario que nunca fue una agencia
recomendada.

En cualquier momento, y desde cualquier pantalla, se podrá acceder al listado de
agencias recomendadas.

¡PUNTOS EXTRA! Por un buen manejo de excepciones y escritura prolija de código y un
buen uso del patrón MVC.
