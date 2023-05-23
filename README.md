Explicación
El proyecto consiste en hacer un sistema para crear usuarios, almacenarlos en una base de datos
e ingresar a la misma desde un sing in, todo esto con variables de entorno separandolas por carpetas
y utilizando algunos paquetes de npm hacer que el sistema sea mas seguro.

uuid:Generaidentificadores unicos de ahi sus siglas, en este caso el uuid se genera de manera aleatoria debido al uuid.v4().

porque es una buena opción usar uuid y no un id autonumérico: 
Por lo que investigue estos uuid son casi literalmente unicos y son muy utiles por motivos de seguridad
y para evitar que se dupliquen los datos.

¿Que es el parámetro de Salt Rounds de la librería bcryptjs?
Funciona para incriptar las contraseñas o por lo menos hacerlas mas seguras:
"Determina la cantidad de iteraciones realizadas para generar el valor de sal (salt) utilizado en el proceso de hashing de contraseñas.
 El valor de sal es una cadena aleatoria que se agrega a la contraseña antes de aplicar el algoritmo de 
 hashing, lo que aumenta la seguridad y dificulta los ataques de fuerza bruta y de tablas arcoíris"
