#SQL
SQL es un lenguaje informático que se utiliza habitualmente para extraer y manipular datos contenidos en bases de datos relacionales. SQL utiliza comandos y palabras clave que describen qué datos extraer y cómo mostrar los resultados. Las consultas SQL también pueden realizar cálculos mediante operadores.

## Comandos SQL

 El comando SELECT, junto con INSERT, UPDATE y DELETE, es parte del lenguaje SQL que se utiliza para trabajar con los datos o manipularlos. Esto se denomina DML ( **lenguaje de manipulación de datos** ).

Otra parte del lenguaje SQL se llama DDL, o **lenguaje de definición de datos** , y nos permite crear y mantener el esquema de la base de datos. Con DDL podemos hacer cosas como crear tablas, definir su estructura y especificar el tipo de datos que se espera para cada columna.

==*Nota: SQL es tan universalmente compatible con los sistemas de bases de datos relacionales (RDBS) que a menudo se hace referencia a las bases de datos relacionales como “bases de datos SQL”. El lenguaje SQL en sí es un estándar de código abierto, pero cada RDBS admite su propia selección de palabras clave SQL, por lo que es importante consultar la documentación del RDBS específico que estemos utilizando.*==

## Uso de SQL

**Comando SELECT**

**SELECT** va seguido de una lista de los atributos (columnas) que queremos que se lean y **se devuelvan** o muestren.
**FROM** para especificar que queremos obtener datos de la tabla.
**WHERE** para especificar los datos que van a ser filtrados.
**ORDER BY** para ordenar una columna en orden ascendente "ASC" y descendente "DES".

SELECT columnas FROM tabla WHERE datos filtrados ORDER BY columna para ordenar las columnas

## Operadores de SQL


**RVAG.**  Devuelve el promedio de todos los valores de ese campo o expresión.

```
SELECT AVG() FROM tabla;
```

![[Pasted image 20241028150241.png]]

**COUNT.**

```
SELECT COUNT(*),MAX(Score),MIN(Score) FROM tabla WHERE condicion
```
