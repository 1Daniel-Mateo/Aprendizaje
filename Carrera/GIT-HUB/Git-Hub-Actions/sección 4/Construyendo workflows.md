
Ahora aplicando dentro de un programa real debemos crear la misma estructura de las sesiones anteriores, en este caso lo aplicamos con un proyecto en laravel donde en el jobs traemos el run, los servicios de mysql y los Steps que nos chequean e instalan las dependencias, extensiones y el composer dentro del repositorio.

![[estructura aplicada.png]]


**Ejecutar pruebas**

Se copia las variables de entorno del archivo env.example para que pueda correr de mejor manera el programa y se copie en un archivo env. También el uso de linea de comandos de laravel con esto podemos ejecutar la aplicación con base en su infraestructura y esto para ejecutar nuestras pruebas unitarias.


![[Pasted image 20241025164320.png]]

**Condicionales**

Las condicionales dentro de los archivos yaml, condicionando un Step por un id y llamándole dentro de otro Step donde generamos la condicional usando la validación 'if' y si el resultado no es 'success' entonces el Step del test:

![[Pasted image 20241028085420.png]]

**Debug**

 Aquí utilizamos la dependencia artifact que nos recomienda actions que nos sirve para copiar archivos y llamando al parametro (if: Para que evalue si alguno de los Steps presenta fallas)

![[Pasted image 20241028090542.png]]



