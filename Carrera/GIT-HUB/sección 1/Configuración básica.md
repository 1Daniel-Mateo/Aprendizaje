
Para la creación de un proyecto de un Workflow sigue los siguientes pasos:

1. Crea una carpeta dentro de tu proyecto de desarrollo llamada .github dentro de esta crea el directorio Workflows(directorio donde se almacenaran tus archivos YAML) y en este directorio crear el archivo test.yml o test.yaml, cualquiera es correcto.
   
2. Define esta estructura básica:
   
![[git.png]]

3. Lo subes a git-hub y te correra un menu dentro de la herramienta de git hub
![[Pasted image 20241008155342.png]]
## Jobs & Steps

Cuando definimos las tareas que se van a realizar dentro de los jobs podemos correr las automatizar ramas de desarrollo usando Steps que realizaran distintas pruebas y que configuraremos según las necesidades que evaluemos.

## Eventos

Dependiendo el evento de git-hub que vayas ejecutar, así mismo ejecutara el workflow y donde los Jobs y Steps para que evalúen las condiciones sobre las ramas que detallemos.

```
# Cualquier archivo que se encuentre en el directorio .github/workflows

# Nombre de workflow

name: Hola Mundo

  

# Evento que se va a ejecutar

on: [push]

  
  

# se ejecutará cuando se ejecute el evento

jobs:

  #  Job que se ejecutará

  hola:

    #   Run: comando que se ejecutará sobre el servidor de GitHub Actions

    runs-on: ubuntu-latest

  

    #   Steps: conjunto de acciones que se ejecutarán

    steps:

      - name: Hola Mundo

        run: echo "Hola Mundo"

  

      - name: touch file

        run: touch hola.txt

  

      - name: Set text

        run: echo "Hola Mundo" >> hola.txt

  

      - name: Read file

        run: cat hola.txt

  
  

  #   Job que se ejecutará

  other:

    #   Run: comando que se ejecutará sobre el servidor de GitHub Actions

    runs-on: ubuntu-latest

  

    #     Steps: conjunto de acciones que se ejecutarán

    steps:

    - name: LS

      run: touch hola.txt
```











