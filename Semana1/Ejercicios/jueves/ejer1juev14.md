[regresar](jueves14julio.md)
# Imprimir numeros especiales

## Descripcion
En este ejercicio debes usar un control de flujo iterativo para poder imprimir todos los números pares en el rango de números del 0 al 100. Recuerda que no debes imprimir cada número, debes usar una estructura de control de flujo para realizar el ejercicio

## Ayuda

1. [Para](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)
2. [Tiempo](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
3. [hacer mientras](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/do...while)
4. [Número par](https://byjus.com/maths/even-numbers/)
5. [Operador de recordatorio](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Remainder)


## Solucion

""" .JavaScript

var i = 0;
do {
  if(i % 2 === 0 ){
    console.log(i);
  }
  i = i + 1;
} while (i < 100);

"""