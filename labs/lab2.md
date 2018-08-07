Universidad Francisco Marroquin

Algoritmia y Complejidad
# Laboratorio 2


## Problema 1
**Problema de Sorting**

Supongamos que trabajan en una famosa empresa de tecnologia cuyo principal producto es un motor de busqueda. 
Para saber en que orden mostrar las paginas al hacer una busqueda, su trabajo es ordenar la lista de paginas web por su *pagerank* de mayor a menor. Hacer esto en un tiempo menor a <math></math>

```python
website_page_ranks = [3,39,61,91,57,22,75,89,9,90,63,78,28,73,20]
```

Adicionalmente agruegen un contador para ver cuantas veces se itero el programa y compararlo al input.


## Problema 2
**Verificacion de heap**

Escriban un programa que verifique si el siguiente arreglo es un heap.

```python
possible_heap = [16,14,10,8,7,9,3,2,4,1]
```
Demuestre el *running time* de este programa.

## Problema 3
**Heapify**


![heapify](https://2.bp.blogspot.com/-OcYCdFkYNcU/WWwOyzyIWnI/AAAAAAAAAIk/tepgD2ORBgoNPz7ewhbiDgo9m6pnLpDFACLcBGAs/s1600/Sin%2Bt%25C3%25ADtulo.png)




El codigo para MAX-HEAPIFY es muy eficiente en terminos de factores constantes, posiblemente exceptuando la linea 10, que podria causar que algunos compiladores produzcan codigo ineficiente.
Escriban un algoritmo de MAX-HEAPIFY que utilize un constructo de control iterativo (loop) en lugar de recursion.

- - - -

Fecha de entrega: 9 de Agosto 11:59 pm (media noche)