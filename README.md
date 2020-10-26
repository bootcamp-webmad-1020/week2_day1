# week2_day1

## Contenidos

> JS | Data structures
>
> JS | Array advanced methods: `.map()`, `.filter()`, `.reduce()`, `.reverse()` and `.sort()`


## Main points: array advanced methods

Los métodos `.map()`, `.filter()` y `.reduce()` son métodos de los objetos de tipo array que no mutan el array original.

- El método `.map()`:
  - Recibe como argumento una función.
  - Retorna un array manipulado de la misma longitud que el original.
  - Transfiere a cada posición del array resultante el retorno de la función argumentada.
    
- El método `.filter()`
  - Recibe como argumento una función.
  - Retorna un array con una longitud máxima igual a la longitud del array original.
  - Transfiere al array resultante cada posición del array original donde la función argumentada retorna un valor _truthy_.
  
- El método `.reduce()` 
  - Recibe como argumento una función con dos parámetros por defecto: acumulador y valor iterado.
  - Puede recibir un segundo argumento tomando este como valor inicial para el acumulador.
  - Toma como valor del acumulador para la segunda y sucesivas iteraciones el valor retornado de la anterior iteración.
  
Los métodos `.sort()` y `.reverse()` mutan el array original.

- El método `.sort()` 
  - Recibe como argumento una función de ordenación, de lo contrario ordena los elemtnos según codificación `Unicode`.

- El método `.reverse()` 
  - Invierte el orden de los elementos presentes en el array.
  
 
## Main points: _truthys_ vs _falsies_

Las arquitecturas condicionales accederán siempre al bloque incial de instrucciones excepto en el caso de expresiones con resultado _falsie_:
- `false`
- `undefined`
- `null`
- `NaN`
- `0`
- `""`
