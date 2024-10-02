Configurar datos según los requisitos de un análisis

### Procesos ETL y ELT

#### (ETL) Extraer, transformar y cargar:

Proceso que consiste en recopilar datos de esta variedad de fuentes, transformarlos y luego cargarlo en la base de datos. Es importante transformar las datos que descargaste para después agregarlos dentro en otro formato.

#### (ELT) Extracción, carga y transformación:

ELT permite que los datos sin procesar no tenga necesidad de transformación y vayan directamente al almacenamiento en un formato no estructurado. Luego, la transformación se produce en los datos almacenados a medida que se utilizan. 

##### Pasos del proceso ETL

**Extraer:**
Se localizan y recopilan datos de diversas fuentes para convertirlos a un único formato para su análisis. Los datos pueden extraerse de una base de datos relacional, NoSQL, archivos planos, archivos XML u otros formatos.

**Transformar:**
Para la transformación utiliza reglas para transformar los datos de origen al tipo de datos necesarios para la base de datos de destino. Esto tiene en cuenta la conversión a medidas a la misma dimensión (por ejemplo, del sistema imperial al métrico). Unión de datos de varias fuentes, agregar , ordenar, determinar nuevos valores que se calculan a partir de datos agregados y aplicación de reglas de validación. 

Limpieza de datos son la eliminación de registros en blanco y la estandarización de formatos como fecha, hora y ubicación. La parte de limpieza del paso de transformación garantiza aún más la coherencia de los datos de origen.

**Cargar:**
Los datos transformados serán cargados a la base de datos, usando el formato universal de csv, esto debido a su facilidad y la carga de recursos no es excesiva para los datos. Ahora solo se organizarían con la tabla a la que se insertan los datos.







