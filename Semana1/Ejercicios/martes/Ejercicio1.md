[regresar](Martes.md)
# Lenguajes de programacion interperetados y compilados.

Cada programa es un conjunto de instrucciones, ya sea para agregar dos números o enviar una solicitud a través de Internet. Los compiladores e intérpretes toman código legible por humanos y lo convierten en código de máquina legible por computadora.<br>

## IDIOMAS COMPILADOS

Los lenguajes compilados se convierten directamente en código de máquina que el procesador puede ejecutar. Como resultado, tienden a ser más rápidos y eficientes de ejecutar que los lenguajes interpretados. También le dan al desarrollador más control sobre los aspectos del hardware, como la administración de la memoria y el uso de la CPU.

Los lenguajes compilados necesitan un paso de "compilación": primero deben compilarse manualmente. Debe "reconstruir" el programa cada vez que necesite hacer un cambio. En nuestro ejemplo de hummus, la traducción completa está escrita antes de que llegue a ti. Si el autor original decide que quiere usar un tipo diferente de aceite de oliva, será necesario volver a traducir la receta completa y enviársela.

### Ejemplos
Ejemplos de lenguajes compilados puros son C, C++, Erlang, Haskell, Rust y Go.

### Ventajas
Los programas que se compilan en código de máquina nativo tienden a ser más rápidos que el código interpretado. Esto se debe a que el proceso de traducción del código en tiempo de ejecución aumenta la sobrecarga y puede hacer que el programa sea más lento en general.

### Desventajas
-Tiempo adicional necesario para completar todo el paso de compilación antes de la prueba <br>
-Dependencia de la plataforma del código binario generado

## IDIOMAS INTERPRETADOS

Los intérpretes ejecutan un programa línea por línea y ejecutan cada comando. Aquí, si el autor decide que quiere usar un tipo diferente de aceite de oliva, podría quitar el viejo y agregar el nuevo. Su amigo traductor puede transmitirle ese cambio a medida que sucede.

Los lenguajes interpretados alguna vez fueron significativamente más lentos que los lenguajes compilados. Pero, con el desarrollo de la compilación justo a tiempo , esa brecha se está reduciendo.

### Ejemplos
Ejemplos de lenguajes interpretados comunes son PHP, Ruby, Python y JavaScript.

### Ventajas
Los lenguajes interpretados tienden a ser más flexibles y, a menudo, ofrecen características como escritura dinámica y tamaño de programa más pequeño. Además, debido a que los intérpretes ejecutan el código del programa fuente ellos mismos, el código en sí es independiente de la plataforma.

### Desventajas
La desventaja más notable es la velocidad de ejecución típica en comparación con los lenguajes compilados.