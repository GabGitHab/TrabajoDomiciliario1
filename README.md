ALGORITMO DE HASH


Introduccion: Este es una breve introduccion a algoritmo de Hash, pero la intencion de este texto es solo para ejercicio sobre
funcionamiento de Git.


Los algoritmos de hash tienen varias funciones 

Mantener la integridad de los datos, al calcular un hash de un archivo y luego volver a calcularlo en otro momento, se puede verificar

Deterministas, el mismo input siempre genera el mismo output.

Colisiones, dos entradas diferentes no pueden generar el mismo hash (aunque esto no puede evitarse al 100% ya que los
algoritmos de hash tienen una cantidad finita de digitos, si se puede lograr minimizar la probabilidad de que distintas entradas
den hash diferentes).

Este tipo de Algoritmo es utilizado en Git para identificar de manera unica cada objeto almacenado en el repositorio, como commits, blobs y trees.

Tambien se utliza mucho en forences digitales, para verificar la integridad de archivos y datos.



Firma: Gabriel Larrosa