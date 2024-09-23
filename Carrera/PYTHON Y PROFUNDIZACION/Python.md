[[FastAPI]]
[[Retos de logica]]


Para habilitar el uso de Docker para un usuario que no tiene privilegios de administrador en Windows, debes agregar ese usuario al grupo `docker-users`. Esto le permitirá ejecutar comandos de Docker sin necesidad de permisos de administrador. A continuación, se detallan los pasos para realizar esta configuración:

### Pasos para Habilitar Docker para un Usuario No Administrador

1. **Abrir Administración de Equipos**:
   - Haz clic derecho en el botón de inicio de Windows y selecciona **Administración de equipos**.

2. **Acceder a Grupos**:
   - En la ventana de Administración de equipos, expande **Usuarios y grupos locales** y selecciona **Grupos**.

3. **Agregar el Usuario al Grupo `docker-users`**:
   - Busca el grupo **docker-users** en la lista.
   - Haz clic derecho sobre el grupo y selecciona **Agregar al grupo**.
   - En la ventana que se abre, agrega el nombre de usuario que deseas habilitar para usar Docker.

4. **Cerrar Sesión y Volver a Iniciar Sesión**:
   - Después de agregar el usuario al grupo, cierra la sesión de Windows y vuelve a iniciar sesión para que los cambios surtan efecto.

5. **Verificar la Configuración**:
   - Una vez que hayas iniciado sesión de nuevo, abre una terminal (CMD o PowerShell) y ejecuta un comando de Docker para verificar que ahora puedes usar Docker sin problemas de permisos. Por ejemplo:
     ```bash
     docker run hello-world
     ```

### Alternativa Usando Comandos

Si prefieres usar la línea de comandos, puedes agregar un usuario al grupo `docker-users` utilizando el siguiente comando en una ventana de PowerShell o CMD con privilegios de administrador:

```bash
net localgroup docker-users DOMAIN\username /add
```

Asegúrate de reemplazar `DOMAIN\username` con el dominio y nombre de usuario correcto.

### Consideraciones

- **Privilegios de Seguridad**: Ten en cuenta que agregar un usuario al grupo `docker-users` le otorga permisos significativos sobre el sistema, ya que Docker puede interactuar con recursos del sistema operativo. Es recomendable hacerlo solo con usuarios de confianza.
  
- **Reinicio de Docker**: En algunos casos, puede ser necesario reiniciar Docker Desktop para que los cambios surtan efecto.

Siguiendo estos pasos, podrás habilitar el uso de Docker para un usuario sin privilegios de administrador en Windows.

Citations:
[1] https://aprendiendoavirtualizar.com/administrar-contenedores-docker-sin-usar-sudo/
[2] https://soloconlinux.org.es/ejecutar-docker-sin-ser-root/
[3] https://www.ionos.com/es-us/digitalguide/servidores/configuracion/tutorial-docker-instalacion-y-primeros-pasos/
[4] https://learn.microsoft.com/es-es/troubleshoot/developer/visualstudio/ide/troubleshooting-docker-errors
[5] https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04-es
[6] https://learn.microsoft.com/es-es/virtualization/windowscontainers/manage-docker/configure-docker-daemon
[7] https://support.esri.com/es-es/knowledge-base/how-to-get-docker-desktop-to-run-at-startup-for-noteboo-000024946
[8] https://help.hcl-software.com/commerce/9.1.0/es/install/tasks/tiginstall_nonrootdocker.html



Instalar el usuario desde mi administrador y que corra por este usuario dsuarez.

probar que quede habilitado el usuario.





