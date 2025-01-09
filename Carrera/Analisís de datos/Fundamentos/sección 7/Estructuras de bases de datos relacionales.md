Las bases de datos relacionales sean tan potentes es la capacidad de almacenar datos en tablas diferentes pero relacionadas. De esta manera, evitamos muchas redundancias y posibles discrepancias en los datos.
![[SQL ejemplo.png]]Los esquemas de bases de datos son la definición de como se organizan los datos dentro de la estructura:

* **Tablas:** Organización de datos en formato de filas y columnas similar a una hoja de cálculo. En una tabla, cada fila representa un registro único de la base de datos y cada columna representa un campo dentro del registro.
  
* **Campo:** Un atributo especifico de un registro individual. Los nombres de los campos son representados mediante columnas de una tabla.
  
* **Registro:** Es la colección de atributos relacionados que pertenecen a un elemento individual o filas de la tabla.


**Clave principal o llave principal:** 

Las llaves principales son usadas principalmente para el control de registros evitando duplicidad, también para usarla como punto de referencia cuando buscamos un registro especifico y también podemos usar como **llave externa** desde otra tabla.

**Clave primaria (PK):** Un campo de una tabla que contiene identificadores únicos para cada registro de la tabla. Una clave principal puede ser una combinación varias columnas.

**Clave externa (FK):** Una columna o una combinación de columnas de una tabla que corresponde a la clave principal de otra tabla.

La definición indica que una clave principal (o una clave externa) puede ser una combinación de varias columnas. Volvamos a nuestra tabla de Ingresos brutos.


### Relaciones de bases de datos

* **Uno a muchos:** Relación entre entidades (registros) en la que un registro de una tabla puede estar relacionado con varios registros de la segunda tabla. Por el contrario, un registro de la segunda tabla solo puede estar relacionado con un registro de la primera tabla.
  
* **Cara a cara:** Una relación entre entidades donde un registro de una tabla solo puede relacionarse con un único registro de la segunda tabla y viceversa.
  
* **Muchos a muchos:** Una relación entre entidades donde varios registros de una tabla pueden relacionarse con varios registros de otra tabla.


### Tipos de datos

Tipos de datos comunes en las bases de datos y los valores que almacenan:

**CHAR:** Abreviatura de “tamaño de carácter”. Cadena de caracteres de longitud fija (según la base de datos) que puede contener números, letras o caracteres especiales en cualquier combinación. La longitud máxima suele ser de 255 caracteres.

**VARCHAR:** Cadena de caracteres de longitud variable que puede contener números, letras o caracteres especiales hasta una longitud máxima de tamaño de carácter variable.

**TEXTO:** Una cadena que normalmente se utiliza para manejar contenido de texto de formato largo.

**INT:** Campo numérico que solo puede contener números enteros positivos o negativos.

**DECIMAL:** Un campo numérico que contiene un número exacto, de punto fijo o decimal.

**FLOAT:** Un campo numérico que contiene un número de punto flotante.

**DATATIME:** Una combinación de fecha y hora que se presenta en muchos formatos estandarizados. Ejemplo de formato: AAAA-MM-DD hh:mm:ss



