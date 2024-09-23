#Api_rest
1. Crea un repositorio en git, coloca el nombre y almacena un archivo.txt para que puedas subirlo.
2. Inicializa el proyecto con npm init para inicializar el proyecto, se le asigna un nombre al paquete, si sigue con la versión que maneje, se le da una descripción, le pones el nombre y agregas el nombre de liciencia si es requerido y ya:
   
   ![[configuracion de paquete.png]]
   
3. Lista de primero paquetes a instalar
```
    express
    npm install -D @babel/cli @babel/core @babel/preset-env @babel/node
	bcryptjs
	body-parse
	connect-multiparty
	cors
	dotenv
	express-promise-router
	jsonwebtoken
	mongoose
	nodemon

```
4. Creamos dos archivos babelrc, main y configurara el packege.json.
* Packege.json: Cambias el ejecutor del paquete por el babel.
   
```
   "scripts": {

    "start": "nodemon --exec babel-node main.js"

  },
```
* Babel: Compilador JS que facilita que corre en distintos servidores
* main: Es el archivo que nos ayudara a gestionar las rutas y conexiones de toda la aplicación.

5. 
   