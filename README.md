# Arrays-CDMX009

## ¿Qué es un array?

Es una estructura de datos que nos permite almacenar diferentes valores: strings, numbers, booleans, arrays, objetos.

Para crear un objeto podemos hacerlo de la manera más convencional:

let fruits = ['Manzana', 'Naranja', 'Pera'];

O creando una instancia de Array:

let colors = new Array('Negro','Rojo','Azul')

## Pilas y colas

Un array puede comportarse como una pila o como una cola, para ello utilizamos ciertos métodos que nos permiten agregar o quitar elementos del arreglo dependiendo que como lo utilicemos.

### Pila(Stack)
Para una pila (stack) se utiliza el principio LIFO (Last In First Out) es decir que el último elemento que agregamos es el primero que quitamos:

fruits.push('Mango');
['Manzana', 'Naranja', 'Pera', 'Mango'];

fruits.pop();
['Manzana', 'Naranja', 'Pera'];

### Cola(Queue)
Para una cola (queue) se utiliza el principio FIFO (First in First Out) es decir que el primer elemento que agregamos es el primero que quitamos:

colors.unshift('Rosa');
['Rosa','Negro','Rojo','Azul']

colores.shift();
['Rosa','Negro','Rojo','Azul'];
// 'Rosa'

Existen muchos más métodos, para ellos te recomendamos visitar el siguiente links en donde podrás encontrar muy buenos ejemplos e información: https://www.w3schools.com/js/js_array_methods.asp


Array: https://gist.github.com/HectorBlisS/cba6765e20297d64efb8ac1f850b0f7b
Codepen: https://codepen.io/pen/?editors=0111



