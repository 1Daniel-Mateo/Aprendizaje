
Troncal zip, nos brinda ip y varios segmentos telefono

Respaldo de escrutinios y montan como un sistma oprativo similar a un debian, respuestas preprogramadas 

Registrar de donde llamaron y auzilares

General y se van cerrando de manera inversa

cierre de auzilar, general, localidad y  departamento.

registro de llamadas y leen un pdf para adisionar solución.

---

Actas

Software de borrado seguro.

hash SHA-1. nombre encriptado en 
hash MD5. clave encriptada

Registro de una comisión con un estado con base 

ajuste de imagenes

python como generar un pdf
agregar imagenes y 

Generar una base datos de tabla de movimientos y actas

---

# Proyecto de actas de borrado seguro


### Meta Final:

Crear una aplicación que genere actas de borrado seguro, que nos permita crear múltiples registros al mismo tiempo y almacenarlos temporalmente, para luego cerrar el registro cuando el estado de todas las imágenes sea correcto. Una vez completado, el siguiente paso es generar un PDF personalizado y descargarlo.

### Objetivos

* **Diseñar la interfaz para la creación y visualización de registros de borrado seguro** 📋
    - Crear un formulario o interfaz que permita ingresar múltiples registros en paralelo.
    - Validar los campos obligatorios para cada registro, incluyendo detalles como identificador del archivo, método de borrado, fecha y estado.
    - Mostrar un estado de cada registro (por ejemplo, "en proceso", "completo" o "fallido") para un monitoreo rápido.
- **Implementar la lógica de almacenamiento temporal de registros** 🗄️
    - Crear un sistema de almacenamiento temporal para los registros hasta que todos tengan un estado correcto.
    - Usar almacenamiento local (localStorage) o backend (base de datos temporal) para guardar los registros.
    - Permitir al usuario agregar, editar y eliminar registros antes de cerrar el acta.
- **Desarrollar la funcionalidad de cierre del registro** ✅
    
    - Verificar que todos los registros estén completos y en estado correcto antes de permitir el cierre del acta.
    - Confirmar el cierre del registro y bloquear la edición de los registros tras la confirmación.
    - Cambiar el estado del acta de "en proceso" a "cerrado".
- **Generación de PDF personalizada** 📄
    
    - Construir una plantilla de PDF personalizada para el acta final, incluyendo los detalles de cada registro.
    - Añadir cabeceras, pie de página, logotipo de la empresa (si aplica), y detalles de auditoría.
    - Usar librerías como `jsPDF` o `PDFKit` para construir y personalizar el PDF.
- **Funcionalidad de descarga del PDF** ⬇️
    - Permitir la descarga del acta en formato PDF una vez que el registro esté cerrado.
    - Guardar el PDF en la carpeta del usuario o en una ubicación especificada por el navegador.
- **Implementar verificación y alertas en tiempo real para errores** 🚨
    - Agregar alertas o mensajes de advertencia si algún registro tiene un error o si falta información.
    - Permitir la corrección en tiempo real y actualizar el estado de cada registro según los cambios.
- **Pruebas y optimización** 🧪
    - Realizar pruebas de la funcionalidad completa para asegurar que los registros se crean, almacenan, y se borran de manera correcta.
    - Probar la generación del PDF con diferentes tipos de datos para garantizar que el diseño es robusto y no falla.

### **Objetivos Adicionales y Opcionales** 🌟

1. **Sistema de autenticación y permisos** 🔐
    - Añadir autenticación para asegurar que solo usuarios autorizados puedan generar o descargar actas.
2. **Historial de actas y búsqueda avanzada** 🔍
    - Crear un sistema de historial que almacene las actas generadas anteriormente, permitiendo su consulta posterior.
  
### Recursos 

**Tecnologías**

* FastApi
* Estilos propios o Frameworks de vista
* Docker
* Git-Git hub y actions
* Base de datos SQL
* Servidor donde se alojara el programas
###  Impedimentos o problemáticas

* Recursos de los equipos
* Tiempo dependiendo del nivel de urgencia
* Proceso de adquisición de conocimientos
---
## Plan de trabajo

1. Crear un formulario de registro que nos almacene los datos para el acta; base de datos del proyecto, que integre imágenes con validaciones, mensajes personalizados y que descargue un pdf. También incluir un pequeño CRUD. 
   
2. Crear la lógica de registro temporal Mostrando un estado de cada registro (por ejemplo, "en proceso", "completo" o "fallido") para un monitoreo rápido. 
   
3. Parte de autenticación, con validaciones y cierre de sesión.







