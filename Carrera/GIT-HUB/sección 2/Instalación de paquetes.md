#instalacion_actions

Se puede generar de manera automatizada la instalación de paquetes que necesitemos para el desarrollo, lo importante es definir la instalación de estos paquetes usando plugins de git-hub marketplace y un archivo donde tienes instaladas todas las dependencias.

```
# Cualquier archivo que se encuentre en el directorio .github/workflows

# Nombre de workflow

name: Hola Mundo

  

# Evento que se va a ejecutar

on: [push]

  
  

# se ejecutará cuando se ejecute el evento

jobs:

  #  Job que se ejecutará
  
    paquete:

    runs-on: ubuntu-latest

    steps:

      # plugin checkout de git hub intregrado

    - name: Checkout

      uses: actions/checkout@v4.2.1

      #Llamada para agregar el paquete en el archivo instalar.sh

    - name: ls

      run: |

        chmod  +x instalar.sh

        ./instalar.sh

```

### Uso Actions

Usando el martkeplace de git-hub podemos configurar que instale los paquetes que requiramos dentro nuestra aplicación esto facilita la tarea del desarrollo.
### Actions Reusar

Podemos crear mas directorios en los cuales guardamos actions y steps específicos que los utilizaremos para alcanzar mas objetivos para tener un desarrollo mas automatizado.

Archivo main principal donde llamamos al action:
![[Pasted image 20241021165256.png]]

Estructura de archivos y el uso del composite para que nos ejecute los steps en el archivo:
![[Pasted image 20241021165237.png]]