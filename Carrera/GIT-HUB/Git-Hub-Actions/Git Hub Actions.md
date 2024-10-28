#git_hub_actions
### Conceptos Básicos:

CI/CD: Método ideado para automatización los procesos de desarrollo y hacer más eficiente su integración.

Integración continua: Integrar cambios de manera continua y automatización.

Despliegue continuo: Estrategia de desarrollo de software en la que los cambios de código de una aplicación se publican automáticamente en el entorno de producción.

Pruebas Unitarias: Bloque mas pequeño y aislado de código de aplicación, normalmente una función o método que es verificado en su respectivo bloque de código y ejecutando según los esperado.


**Herramientas de integración de código CI/CD:**

Jenkins:
Sistema desplegado en un servidor que usamos para hacer integración continua y programar tareas automáticas cuando ocurre una acción en concreto, lo que ahorra tiempos y recursos.

GitHub Actions: 
Permite a los miembros de la empresa mejorar la productividad mediante la automatización de todas las fases del flujo de trabajo de desarrollo de software.

Los desarrolladores pueden fusionar con frecuencia los cambios de código a un repositorio central donde luego se ejecutan las compilaciones y pruebas. Las herramientas automatizadas sirven para verificar que el nuevo código es correcto antes de la integración con la rama principal de tu repositorio.
### Conceptos

**Workflows:** Un archivo YAML  que definen una seri de acciones que se ejecutan automáticamente en respuesta a eventos.

**Event:** Disparador que inicia un workflow.

**Job:** Unidad de trabajo dentro de in workflow. El workflow puede tener varios jobs, y cada uno de estos se pueden ejecutar en paralelo o secuencialmente.

**Step:** Acción individual dentro de un job.

**Action:** Bloque de código reutilizable que realiza una tarea específica en un step.

**Runner:** Entorno donde se ejecutan los jobs.

### YAML

Lenguaje de serialización de datos y configurar archivos para realizar ejecuciones de los jobs.

**Reglas**

Para la creación de este archivo de configuración

1. No uso de bloques delimitados, no necesitan de ningún símbolo especial para definir un bloque.
2. Esta organizado sobre la indentación que se van a organizar de la misma manera.


Secciones del curso Git Hub Actions

Sección 1: [[Configuración básica]]
Sección 2:[[Instalación de paquetes]]
Sección 3: [[Variables y secretos]]
Sección 4:[[Construyendo workflows]]
Sección 5:[[Workflow Ruuners]]
Sección 6:[[Despliegues]]
Sección 7:[[Monitoreo y Notificaciones]]
