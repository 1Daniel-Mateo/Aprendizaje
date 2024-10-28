
**Variables**
Las variables de entorno se definen en el workflow con un nombre y se llaman dentro de un step que nosotros también aprovecharemos para guardar el valor. También las podemos en la zona de seguridad del repositorio en las acciones podemos crear mas variables.

![[variables.png]]

**Secretos**
Son variables de entorno enfocadas para información sensible.
Similar a las variables abiertas de entorno; sin embargo se agrega el objeto secrect y se pueden configurar en el repositorio en la sintaxis usando la misma interpolación:

![[secreto.png]]

**Llaves SSH**
Para crear elementos SSH es necesario llamar a la variable desde git-hub, se realiza un formateo y creamos un nuevo directorio en el home, llamado al directorio ssh. y rediregimos la salida a ese archivo, donde habilitamos los permisos con chmod y habilitación ssh-keyscan para correrlo con permiso del usuario.

![[ssh.png]]

