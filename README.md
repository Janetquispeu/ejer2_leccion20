# ejer2_leccion20
Modificar el siguiente script usando closures para que se ejecute sin problemas.
El código muestra el mensaje JS coders love its callbacks, mientras que el resultado debería ser JS developers love its closures. 
Nota: Solo modificar una línea para que se obtenga el resultado deseado.
Al subir a GitHub, indicar el motivo por el que está mostrando el primer mensaje en el README.md.
var num2 = 0;

![image](ejercicio2.png)

Elimino:  var feature = 'closure';
También le quito el var en la parte "var feature = 'callbacks'; "
Para que  por hoisting, en la función la variable feature lo tome como una variable definida y no cumpla la condición del if y que me cumpla la otra opción y salga el mensaje en la consola 'JS developers love its closure' .