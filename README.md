# Calculadora
calculadora en javascript
 este proyecto es una implementación básica de una calculadora simple en HTML y JavaScript. 

 Aquí está la funcionalidad del código paso a paso:

En el HTML, se muestra una interfaz básica de la calculadora que consta de un campo de entrada (input) para mostrar los números y resultados, y una serie de botones (input)
que representan los dígitos, operadores y acciones de la calculadora.

Cada botón tiene un valor asociado y un atributo onclick que llama a una función JavaScript correspondiente cuando se hace clic en él. Por ejemplo, el botón con el valor "1"
tiene onclick="agregar('1')", lo que significa que cuando se hace clic en ese botón, se ejecutará la función agregar('1').

En el archivo script.js, se definen tres funciones JavaScript:

a. La función agregar(valor) se utiliza para agregar el valor del botón a la pantalla de la calculadora. Obtiene el elemento de la pantalla mediante document.getElementById('pantalla')
y concatena el valor del botón (valor) al valor actual de la pantalla.

b. La función borrar() se utiliza para borrar el contenido de la pantalla de la calculadora. Establece el valor del elemento de la pantalla en una cadena vacía, lo que vacía el campo de entrada.

c. La función calcular() se utiliza para realizar el cálculo basado en la expresión matemática ingresada en la pantalla. Obtiene el valor de la pantalla mediante 
document.getElementById('pantalla').value, utiliza la función eval() para evaluar la expresión y obtiene el resultado. Luego, establece el valor de la pantalla en el resultado calculado.

Cada vez que se hace clic en un botón, se llama a la función correspondiente y se realiza la acción correspondiente en la pantalla de la calculadora.

En resumen, el código permite que los usuarios interactúen con la calculadora haciendo clic en los botones y muestra el resultado de los cálculos en la pantalla.
