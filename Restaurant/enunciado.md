# Restaurant

### Descripción
Tienes un restaurante, el cual tiene unacapacidad máxima de personas a atender. Las personas se van atendiendo por orden de llegada.
A cada una de las personas que llega, le irás entregando platos para que coma hasta que esta te indique que está satisfecha. Y calcular el precio del plato. Cuando esté satisfecha, debes indicar el final del valor de su cuenta.

Cuando hayas terminado de atender a todos, debes indicar el total que ganaste como restaurante

P.D. el precio del plato se calcula con las 3 primeras letras del nombre del plato. Si la letra es una vocal, deberás sumarle 3 al valor del plato, si es una consonante, deberás sumarle 6.

### Input
1. Recibirás la capacidad del restaurante `int`.
2. Luego irás recibiendo los nombres de los clientes.
3. Mientras el cliente no esté satisfecho, recibirás nombres de platos, sabrás que el cliente esta satisfecho porque te llegará el string `Estoy satisfecho!`.

El paso 2 y 3 lo recibirás la cantidad de veces de la capacidad del restaurante.

### Output
1. Primero debes indicar que el restaurante abrio:
```
Restaurante abierto
```

2. Por cada cliente que recibas, deberás darle la bienvenida:
```
Bienvenido {cliente} al restaurante
```
3. Por cada plato que se coma la persona, debes imprimir:
```
Me comí un plato de {nombre_plato}
```
4. Cuando sepas que el cliente esté satisfecho:
```
Estoy satisfecho
``` 
e imprimir el total de su cuenta:
```
Tiene que pagar una cuenta de {total_cuenta} pesos
```
5. Cuando hayas atendido a todos los clientes, debes imprimir:
```
Restaurante cerrado
El restaurante gano {ganancias_restaurante} pesos
```


## Propuesto
1. ¿Cómo debiera cambiar el ejercicio si tuvieras que atender a personas hasta que llegues a los 500 pesos?

2. ¿Cómo cambiaría lo anterior si tuvieras que recolectar hasta un número de plata que se te entrega como input (justo después de la capacidad)?