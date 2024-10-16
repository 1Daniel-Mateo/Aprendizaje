#Errores_itop

Protocolo de seguridad 
Modificar el puerto 3697
volver a instalar el toolkit 
Integrecion de datos, diccionario, actualizar el codigo del itop


QUE HICISTE AYER
QUE DIFICULTADES TUVISTE
QUE VAS HACER HOY


1. Instalar extensiones 
![[extensiones a instalar.png]]

Se instalan las extensiones personas_gasd y grupos_gasd
Se realiza copilación y valida que la extensión organizaciones_gasd es totalmente funcional y generan los campos indicados en la descripción.

-agrega los campos en la interfaz grafica y la base de datos.
pantallazo.

se hizo prueba de registro exitoso y se almacenaron en la base de datos.

pantallazo


Plantilla para documentar comentarios

- Se instalan las extensión office365_gasd.
    
- Se realiza compilación y se valida que la extensión es totalmente funcional y generan los campos propuesto en la descripción.
    
- Ingreso de un office de prueba.  
    
- Se valida de la prueba:  
      
- También nos permite modificar y eliminar esta prueba.
    
    Modificar:  
    Eliminar:  
- Se realiza la migración de datos a este componente.  
  
- Se valido que fueron almacenados en la base de datos.  


Valido que la distribución de los campos de cambios normales dentro del modulo de cambios en la versión 3.2 se encuentran desajustados comparada con la versión 2.6, esta versión funcional, podemos ingresar y actualizar los datos. Se tendrá que ajustar en la fase de ajustes del aplicativo.

Validación de distribución y funcionalidad de localidades

Perfiles que presentan problema
1. admin tools manager
2. audit manager

Necesidad de evaluar la utilidad de muchos campos ya que muchos de estos no tienen mucho uso


AGREGAR MODULO DE ANEXOS A RESUMEN DE INFRAESTRUCTURA

Para la migración de iTop a nueva versión en el menú de gestión de elementos tecnológicos se agrega el modulo de anexos. Estos son los pasos para realizar este ajuste:

1.  En la herramienta en el menú configuración selecciona el apartado de configuración:
   
   ![[Pasted image 20241016083140.png]]
   
2. Usa ctrl + f y busca attachments. Cuando lo hayas encontrado, inserta el nombre de la clase padre que vas habilitar en el arreglo y luego le das al boton de aplicar.
   
   ![[Pasted image 20241016083834.png]]
Nota: No borrar o solo modificar lo que se necesite dentro de este archivo, por que este es el archivo de configuración de la herramienta y cualquier afectación dañara al aplicativo.

3.  Se valida que el modulo de anexos fue agregado en todas las clases con relación a la clase 'PhysicalDevice'.
   
   ![[Pasted image 20241016084536.png]]
