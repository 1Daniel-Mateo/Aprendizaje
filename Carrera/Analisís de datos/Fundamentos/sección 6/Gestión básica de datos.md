#Gestin_DB
## Bases de datos de archivos planos

Una base de datos de archivos planos es almacenado como caracteres de texto dentro de un formato de tabla en una computadora. Almacena información en filas, cada una con la misma estructura que la anterior. A cada una de esas filas, a las que se puede acceder y editar fácilmente, las llamamos **registro** o **instancia** . Las columnas se extienden verticalmente de arriba a abajo y contienen diferentes tipos de información, también conocidos como **campos** o **atributos , para cada** **registro** o fila. Las filas se extienden horizontalmente de izquierda a derecha y también se conocen como **registros** . Un archivo de hoja de cálculo, que se muestra a continuación, es un ejemplo de una base de datos de archivos planos.

![[Pasted image 20241022164049.png]]
Las bases de datos de archivos planos también pueden estar en formato de texto sin formato como los archivos.

Un ejemplo común de este tipo de base de datos de archivos planos es un archivo **CSV** o de valores separados por comas. En este caso, no hay celdas, como en una hoja de cálculo; en su lugar, la información de cada fila está separada por caracteres de texto sin formato, llamados **delimitadores** , como las comas.

![[Pasted image 20241022164359.png]]

**Limitaciones de los archivos planos**
Los archivos planos tienen las siguientes desventajas:

- Es difícil realizar cambios en la estructura del registro.
- Ineficiente para el mantenimiento de registros a gran escala
- Mayor redundancia debido a registros duplicados
- Es fácil crear inconsistencias en los datos

## Bases de datos relacionales

Una base de datos relacional mantiene tipos de datos relacionados en **tablas** , y cada tabla puede tener **relaciones** con otras tablas que vinculan toda la información.

![[Pasted image 20241023141920.png]]
Cada tabla tendrá un nombre, columnas y filas. Al igual que en un archivo plano, cada encabezado de columna en una tabla de base de datos relacional identifica los datos contenidos en esa columna. Asimismo, cada fila representa un registro dentro de la base de datos y los valores (atributos) asociados con ese registro. La intersección de una columna y una fila es un **campo** , y todos los campos de una columna contienen el mismo tipo de datos en el mismo formato, como numérico, de texto o de fecha.

**Esquemas**
Toda la información sobre tablas, atributos, relaciones y otros elementos de una base de datos relacional se documenta en un **esquema** , que es una descripción formal que define la estructura de la base de datos. El esquema se puede modificar fácilmente; por ejemplo, es posible añadir una nueva columna a una tabla, añadir nuevas tablas o eliminar las antiguas mediante un simple comando. Con esta estructura, podemos registrar y almacenar la información.

**Herramientas**
Si queremos utilizar una base de datos relacional, existen muchas herramientas disponibles para configurarla y utilizarla. Este tipo de herramienta se denomina Sistema de Base de Datos Relacional (RDBS, por sus siglas en inglés): software diseñado para crear cualquier cantidad de bases de datos relacionales y trabajar con ellas para almacenar y recuperar datos. Los RDBS más conocidos son MySQL, PostgreSQL, Oracle Rdb y Microsoft SQL Server.

**Ventajas**

- Los datos se almacenan en tablas interrelacionadas, lo que permite almacenar datos complejos de manera eficiente.

- Mayor seguridad y precisión de los datos

- Ideal para almacenamiento de datos de gran tamaño

**Desafíos**

- El software RDBS puede ser costoso de configurar y mantener

- Los RDBS requieren un conjunto de habilidades específicas para su uso

- El rendimiento puede ser lento si hay varias tablas grandes y complejas

