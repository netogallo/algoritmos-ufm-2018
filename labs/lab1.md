Universidad Francisco Marroquin

Algoritmia y Complejidad
# Laboratorio 1


## Problema 1
**Problema de Busqueda**

Escriban pseudocodigo para un algoritmo de **busquedad lineal**, que escanee la sequencia *n* y encuentre un valor *v*. Describan cual es el *loop invariant* de su algoritmo para demostrar que es correcto.

Su algoritmo debe de contener un:

**Input:** Secuencia de *n* numeros <math>
    <mi>A</mi>
    <mo>=</mo>
     <mo>[</mo>
    <msub>
    	<mi>a</mi>
    	<mn>1</mn>
  	</msub>
  	  	<mo>,</mo>
  	<msub>
    	<mi>a</mi>
    	<mn>2</mn>
  	</msub>
  		<mo>,</mo>
  	<msub>
    	<mi>a</mi>
    	<mn>3</mn>
  	</msub>
  	  	<mo>...</mo>
  	 	<mo>,</mo>
  	 <msub>
    	<mi>a</mi>
    	<mn>n</mn>
  	</msub>
  	<mo>]</mo>
  	
</math>

**Output:** Indice *i* tal que <math> 
	<mi>v</mi>
	<mo>=</mo>
	<mi>A</mi>
	<mo>[</mo>
	<mi>i</mi>
	<mo>]</mo>
</math>
o *nulo* si no se encuentra el valor.


## Problema 2
Dado el siguiente algoritmo de multiplicacion de matrices:

```
Input: matriz A y matriz B
Output: matriz C

For i from 1 to n:
	For j from 1 to p:
		Let sum = 0
		For k from 1 to m:
			Set sum <- sum + A[i][k] * B[k][j]
		Set C[i][j] <- sum
return C
```
Demuestre cual el es *running time* de este algoritmo.

## Problema 3

![Bubblesort](http://4.bp.blogspot.com/-c96ypner9gE/UXDk-9X9VHI/AAAAAAAACVE/mj4tX46DZlA/s1600/ashis.PNG)

Cual es el *worst-case running time* de este algoritmo?

Como se compara a el *running time* de insertion sort?

- - - -

Fecha de entrega: 2 de Agosto 11:50 pm (media noche)