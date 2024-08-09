# *14  de mayo*

### Menu

##### ¿Cómo hacer un menu?

- Primero que nada definimos la función

- En nuestro caso el función no tiene parametros

- Nuestra función no tiene  retorno, por eso no devuelve nada.

- En el menu **debe** asegurarse que debe introducirse en el *bucle*

###### ¿Cómo negar una operación de verdad o falso al momento de igualarlo?

- Para expresar esto  se utiliza el **not** antes del signo de operación, sea cualquiera.

- ```python
  while not a != b:
  
  while not a == False #Indica que debe mientras sea verdadero es true
  ```

###### ¿ Qué hay en  la hoja 9 de la ppt de menu?

> - num es una variable de tipo **int**
> 
> - Existe una bandera al principio del programa que permite que se inicie o o no
> 
> - Se muestra una defnición de una función **menu()**}
>   
>   - ¿Qué es esta función?
>     
>     - Imprime una serie de caracteres  demonstrando las opciones que podemos tomar.
> 
> - ¿Qué succede si presionamos cuatro o si no ponemos otro número?
>   
>   - En ese programa lo que sucede si cambiamos ese valor, que no sea cuatro seguimos en un bucle infinito hasta el final.

### Variable cadena

##### ¿Qué sucede si usamos len en una cadena?

- Nos da el valor de la cantidad los digitos, siendo este n

- Los indicies van desde 0 hasta n-1,  de esta  

##### Bucles

##### ¿Cómo se recorre una cadena con for?

- **For** permite recorrer una secuencia de valores , de esta manera permite recorrer esos valores

###### ¿Qué hace range?

Range genera una secuencia desde un número sin incluir 

```python
range(0,6 ) # significa desde 0 hasta 5
range (6) # Indica desde 0 hasta 5
range (0, 8, 2) # Este 2 es el paso, este range genera la secuencia 2,4,6.
"No llega hasta 8"

range (x,y,z)
# x = inicio, y = final, z = paso 
```

###### ¿Cómo se soluciona un problema de for relacionado a "print" a través de un for con un len?

- Si  recorrerimos una cadena través de for, in len(cadena)

- Y luego utilizamos esas posiciónes de valor de la variable i como índice.
  
  Usando esto podemos a través de print  y nos va ir dando las letras.¿Cómo se recorre una cadena a través de un **while**?

```python
i = 0
while i < len(cadena):
    print(cadena[i])
i = i 
```

###### ¿Cómo recorremos los valores  uan cadena por contenido (Por carácter)?

- letra se va ir asignando a los caracteres que tiene cadena 

- En la primera iteración  letra  = cadena[0], va aumentando hasta terminar.

```python
for letra in cadena:
    print(letra)
```

¿Se puede recorrer con un while una cadena con **In**?

- No es recomendable porque no tiene el mismo signficado

- While "p" in "pato" va ser true constantemente y va a producir bucle infinito.

###### ¿Cómo se concantena una  cadena,  por qué esta mal lo siguiente?

- Esta mal porque no se hacer eso con las cadenas, ya que se tratan de algo **Inmutable**, por lo que no acepta cambios  de esta manera

```python
cadena = "Federico"
cadena[1] = "2" # MAL
```

```python
cadena = cadena[0] + "2" + cadena[2:] #Esto esta bien.
```

### ¿Cómo construir una cadena que esta al inversa?

```python
def reversa(cadena):
    nueva_cadena = ""
    for letra in cadena:
        nueva_cadena = letra + nueva_cadena ### Cambio a diferencia de mi programa  realiza la concatenación en el orden al reves
        return  nueva_cadena
```

#### PARCIAL

¿Qué puede ir en un parcial?

- Se debe crear funciones o solucionar los problemas de manera generalizada, no únicamente para un caso especifico. Para cualquier valor
