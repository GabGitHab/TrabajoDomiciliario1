ALGORITMO DE HASH


Introduccion: Este es una breve introduccion a algoritmo de Hash, pero la intencion de este texto es solo para ejercicio sobre
funcionamiento de Git.


Los algoritmos de hash tienen 5 caracteristicas
Deben ser : 

Unidireccionales, no podemos obtener el codigo de entrada a partir del hash.

Deterministas, el mismo input siempre genera el mismo output.

Colisiones, dos entradas diferentes no pueden generar el mismo hash (aunque esto no puede evitarse al 100% ya que los
algoritmos de hash tienen una cantidad finita de digitos, si se puede lograr minimizar la probabilidad de que distintas entradas
den hash diferentes).

Rapidos, deben ser rapidos de calcular.

Debe cumplir con el efecto avalancha, el mas minimo cambio en el input debe generar un hash completamente diferente.



Firma: Gabriel Larrosa