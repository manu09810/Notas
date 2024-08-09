# IRAT - Lista como secuencia

###### ¿Qué es una lista?

- Se agrupan elementos de cualquier tipo.

- Una lista es una secuencia de elementos

- Pueden estar a la vez que otros de elementos de cualquier otro tipo.

- Se indican con "[" y "¨]  y con comas entre ellos

###### ¿Qué tipos de listas existen?

###### Para entender  el concepto del lista, puesto que una lista puede tener otra lista adentro, esto se llama lista anidada.

- Cuando una lista no tiene nada adentro se llama lista vacía.



### Listas en la acción.

###### Elementos de las listas

¿Qué diferencias  y similitudes tienen las cadenas?

- Una de sus principales diferencias se basa en que las strings son inmutables, mientras que esto en el caso de las listas no es cierto, son mutables muy fácilmente de hecho.

- En ambas se acceden a sus elementos a través de [], en ambas se comienza a contar desde cero

- Pero en las listas se puede asignar otro elemento a la posición usando el símbolo de asignación y los corchetes

- 
  

¿A qué se refiere el texto con mapear?

- Utilizar los indices permite mapear la lista, esto permite interactuar con elementos individualmente.

- El funcionamiento será el mismo que con las cadenas (int, números negativos equivalen a contar desde el final.)

- El operador in también funciona en las listas.

- Obtendremos los mismos errores que con las  cadenas 

##### ¿Cómo se puede utilizar *For* para recorrer una lista?

-  Existen dos maneras principalmente de recorrer una lista
  
  - Utlizando *for* in range lista, de esta manera podemos ir recorriendo los elementos pero obtendremos sus valores.Utilizando for in range(len(lista)), esto permitara obtener el valor de i como el de la posición, lo que es mucho más cómodo para asignar los valores.

```python
lista = [1, 2, 3]
for i in range(len(lista)):
    lista
```

      ¿Qué casos especiales existen?

Al correr una cadena vacía, no sucede nada, puesto que  al no existir elementos, no pasaría nada, i no asume ningún valor.

Otro caso especial es donde existen listas **anidadas** porque estas contaran como un solo elemento para el *for*.



#### Interacciones entre listas

¿Qué operadores se pueden usar con las listas?

Si se utiliza el signo de "+" se logra el efecto de la concateneación, aqui el orden es importante y permite crear una lista más grande en base a otras dos listas  sumadas.

El otro operador es el de "*" permite repetir un patrón de una lista, sus  elementos asignados la cantidad de veces que se quiera.

Explica el funcionamiento del  rebanado de listas:




