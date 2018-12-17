## Challenges:

Os dejamos una colección de ejercicios prácticos para que vayáis cogiendo soltura y poniendo vuestros conocimientos en acción:

### Índice:

#### Ejercicios de git y github:

- Crea tu repositorio.
- Utiliza los comandos de git: _status, branch, checkout, push, pull, merge, commit, add, clone_.
- Haz un _fork_ del Módulo 0 y haz un _pull request_ para añadir tu nombre y una frase en el archivo Alumnos, que está en el _root_ del proyecto.

#### Ejercicios web:

- ¿Qué es el DOM?
- ¿Qué es un framework?
- ¿Diferencias entre HTTP y HTTPS? ¿Y websockets?
- Define el proceso que ocurre desde que entras a una web hasta que ves la página cargada.

#### Ejercicios js:

Te recomiendo que los ejercicios de js los hagas en: [repl.it](https://repl.it). Seleccionad el lenguaje de javascript y probad este código para tener una estructura con la que empezar los ejercicios.

```js
// declaramos una variable en falso que controle la salida del programa
let exit = false;

// metemos la lógica dentro de un while para que se repita el procedimiento en caso de no querer salir.
while (!exit) {
  // asignamos el resultado del prompt en una variable name y no vamos a controlar que se cancele esta pregunta.
  let name = prompt("Welcome to hack a bos, what´s your name?");

  // imprimimos el resultado por consola
  console.log("My name is ", name);

  // creamos una ventana de confirmación
  if (window.confirm("Do you want another question?")) {
    // si confirmamos preguntamos más
    let age = prompt("What´s your age?");

    // ahora si queremos controlar, esta vez usamos condicionales.
    if (age) {
      // si has introducido tu edad
      console.log(`My age is ${age}`);
      alert(`I am ${name} and I am ${age} years old`);

      // preguntamos si quiere salir
      askToLeave();
    } else {
      // si no has introducido tu edad
      console.log(`And I don´t want to say my age.`);
      alert(`I am ${name} and I am ${age ? age : "##censored##"} years old`);

      // preguntamos si quiere salir
      askToLeave();
    }
  } else {
    // si no, ponemos la variable que controla la salida a true y el programa se cierra
    exit = true;
  }
}

// si vemos que vamos a repetir el mismo código dos veces podemos extraerlo en una función y llamarla donde la necesitemos.
function askToLeave() {
  if (window.confirm("Do you want to exit?")) {
    exit = true;
  } else {
    exit = false;
  }
}
```

Ejercicio 0 - Calculadora [(hacer)](c0.md)

Ejercicio 1 - Taxis [(hacer)](c1.md)

[Volver](../../README.md).
