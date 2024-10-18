
Excel admite una amplia gama de fórmulas y funciones; la única diferencia entre ellas es que las funciones utilizan palabras clave y están predefinidas por Excel, mientras que los usuarios pueden crear fórmulas personalizadas por sí mismos utilizando operadores. Hay reglas estrictas que seguir al crear fórmulas, por lo que es una buena idea planificar cómo desea que funcionen los cálculos antes de comenzar a ingresarlos en su hoja de cálculo.

Primero, lo básico: todas las fórmulas de Excel comienzan con un signo igual **(=)** . El signo igual indica que los datos de la celda no son texto ni números, sino un cálculo. Esto garantiza que la fórmula no se mostrará en la celda en lugar del resultado del cálculo. Por ejemplo, si se ingresa **=1+2** en una celda (con el signo igual como primer carácter), se mostrará el valor **3** , no el texto _=1+2_ .

**Referencias relativas y absolutas**

Los cálculos se pueden realizar sobre una constante, como el número 5, o sobre los datos contenidos en una ubicación específica (normalmente una celda o un rango de celdas). Por ejemplo, la fórmula **=L1/L7** divide el valor de la celda **L1** por el valor de la celda **L7** .

Dentro de una fórmula o función, cuando hay referencias a celdas o rangos, pueden ser relativas o absolutas. Una referencia es relativa cuando su valor depende de la ubicación de la referencia en sí, mientras que una referencia absoluta hace referencia a la misma celda o rango sin importar dónde aparezca la referencia. Por ejemplo, cuando realizó el laboratorio Manipular datos, copió y pegó fórmulas de una fila en las filas inferiores. Al hacerlo, debido a que las fórmulas tenían referencias relativas, utilizaron los valores de las filas inferiores para realizar los cálculos para esas filas. Este es el comportamiento predeterminado para fórmulas y funciones.

Si desea que una fórmula haga referencia a la misma celda o rango de celdas sin importar dónde se pegue la fórmula, puede hacer que la referencia sea absoluta agregando un signo de dólar ($) antes del indicador de columna o fila para esa referencia. Usemos el ejemplo mencionado anteriormente, **=L1/L7** . Si desea utilizar esta fórmula en varios lugares de su hoja de cálculo y que siempre use los valores en L1 y L7, en lugar de los valores que corresponden a la nueva ubicación de la fórmula, la escribiría como =$L$1/$L$7.

Tanto la indicación de columna como la indicación de fila pueden tener este atributo, independientemente una de la otra, por lo que también puede agregar el signo de dólar solo a la referencia de columna o solo a la referencia de fila.

**Funciones**

Las funciones integradas son fórmulas que comienzan con una palabra clave que identifica una función específica que se realizará. La mayoría de las palabras clave de función describen el cálculo que realizará la función. La sintaxis correcta varía según la función, pero suele tener un patrón similar. Por ejemplo, la sintaxis de la función PROMEDIO acepta un rango o una lista de celdas para calcular el promedio de los valores dentro del rango, como **=PROMEDIO(L2:L37)** o **=PROMEDIO(L2, L5, L6)** .

**Nota:** Debe asegurarse de cerrar todos los paréntesis y corchetes, o recibirá un mensaje de error cuando presione Enter para completar la entrada. Para funciones largas, esto puede resultar difícil.

![[Pasted image 20241018145931.png]]


**Tablas dinámicas**

Las tablas dinámicas son una función de Excel que resulta de gran utilidad para los analistas de datos. Las tablas dinámicas proporcionan una forma de resumir, analizar, explorar y presentar datos de forma automática. Los gráficos dinámicos permiten agregar visualizaciones a los datos de una tabla dinámica. Con estas herramientas integradas, puede identificar tendencias, hacer comparaciones entre elementos de datos y crear gráficos en diferentes estilos para visualizar sus datos. En el próximo laboratorio creará una tabla dinámica, pero, como referencia, estos son los pasos para crear una tabla dinámica en Excel:

1. Comience con una hoja de trabajo organizada en columnas y filas, con encabezados de columna.

2. Seleccione la tabla o el rango de celdas que desea incluir en la tabla dinámica. Asegúrese de incluir los encabezados de columna en el rango.

3. Seleccione Insertar en la barra de menú. En la sección Tablas, puede ver los distintos formatos que pueden adoptar sus datos seleccionando la opción Tablas dinámicas recomendadas. Si no ve una tabla recomendada que cumpla con sus requisitos, seleccione Tabla dinámica => Desde tabla o rango.

4. Se abrirá el cuadro de diálogo Crear tabla dinámica. El rango seleccionado debería aparecer en el cuadro Tabla/Rango y debería seleccionarse Nueva hoja de cálculo. Al crear sus primeras tablas dinámicas, es mejor colocarlas en una nueva pestaña de la hoja de cálculo.

5. Se crea una hoja de cálculo de tabla dinámica en blanco y aparece la lista Campos de tabla dinámica que contiene los encabezados de columna. Haga clic en los campos que desea agregar.

6. El asistente de tablas dinámicas colocará los campos en uno de los cuadros de la parte inferior: Filtros, Columnas, Filas y Valores. Puede arrastrar y soltar los campos en diferentes categorías para cambiar la forma en que la tabla dinámica resume los datos.

7. Aparecerá la tabla dinámica con las selecciones que haya realizado. Las tablas dinámicas admiten la mayoría de las funciones que puede realizar en una hoja de cálculo normal, como ordenar, filtrar y dar formato a las celdas.


Actualizar datos en la hoja de cálculo original no actualiza la tabla dinámica automáticamente; debe actualizar su tabla dinámica para que refleje los datos nuevos.

