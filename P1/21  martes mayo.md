### P1

### IRAT

¿Qué pasa cuando se cambia una lista mutable con una función?

Se cambia la lista, ya que

¿Qué sucede si usas el operador del en una lista?

Elimina elementos de la lista

¿Qué retorna lista.sort?

Devuelve none.

#### Listas

¿Qué formas hay de evitar la mutabilidad  al cambiar la lista al asignar?

```python
lista_1 = [1,2,3]
lista_2 = lista_1[:]
lista_2[1] = 'a'
# Lista_2 va a a ser [1,'a',3]
```

- lista_2 = list(lista1)

- lista_2 = lista1.copy()

- lista_2 = lista[:]

- 
