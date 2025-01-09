#uso_de_SQL

## Unir tablas 

**INNER JOIN:** Etiqueta que nos sirve para unir dos tablas usando **ON** para indicar el valores que coinciden en ambas tablas.

## Combinación de funciones SQL para extraer datos

**SELECT** campos **FROM** tabla **AS** nombre de referencia de la tabla **INNER JOIN** unir con otra tabla **ON** unimos ambas tablas


## Características de gestión de SQL y alternativas

#### Lenguaje de manipulación de datos

La manipulación DML, permite la inserción, eliminación y gestión de datos dentro de la base de datos. Los comandos DML incluyen:

- **INSERT** – Se utiliza para agregar un registro de datos (fila) a una tabla existente.
    
- **DELETE** – Elimina datos de una tabla.
    
- **UPDATE** – Modifica una fila de datos existente.
    
- **SET** – Se utiliza con UPDATE para especificar qué actualizar.
    
- **LOCK** – Bloquea una tabla.

#### Datos distribuidos y NoSQL

Las base de datos relacionales satisfacen las necesidades de los analistas de datos para la mayoría de las aplicaciones. El software del sistema de gestión de bases de datos (RDBMS), los servidores físicos en los que se carga el software y los discos donde se almacenan los elementos de datos. A medida que las bases de datos crecen, se necesitan servidores más potentes para procesar y almacenar las bases de datos más grandes que contienen más datos. Con esta infraestructura RDBMS tradicional y la cantidad de datos que utilizan estas nuevas aplicaciones, es fácil llegar a un límite en el que un servidor muy potente y una gran cantidad de almacenamiento no son suficientes para procesarlos.

El procesamiento distribuido basado en la nube es una solución alternativa que toma un gran volumen de datos y lo divide en fragmentos más pequeños. Estas cantidades más pequeñas de datos se distribuyen entre muchas ubicaciones y luego son procesadas por muchas computadoras.

También incluimos las base de datos NoSQL almacena y accede a los datos de forma diferente a las bases de datos relacionales. A veces, a las bases de datos NoSQL se las denomina “no relacionales” porque no organizan los datos en tablas que constan de columnas y filas que se ajustan a un esquema estructurado. En lugar de tablas, los datos NoSQL se almacenan en un formato no estructurado o semiestructurado que simplifica el diseño de bases de datos.

**Almacenes de clave-valor**

