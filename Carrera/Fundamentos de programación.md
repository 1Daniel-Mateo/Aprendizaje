#fundamentos_basicos 

[[Frameworks]]
[[Python]]
[[Git, Git-Hub y Git Hub Actions]]
[[APIS]]
[[Linux]]
[[Fundamentos en análisis de datos]]
[[JAVA SCRIPT]]

Procesos de crear instrucciones que pueda entender una computadora utilizando lenguajes de programación que son interpretes para la computadora y el desarrollador, utilizando estas herramientas se pueden desarrollar programas software orientados a solucionar necesidades especificas.
### **LENGUAJES**

Los lenguajes de programación son los interpretes que transforman el lenguaje humano a maquina y estos son los mas comunes para el desarrollo software.

1. JAVA
2. JAVASCRIPT
3. PYTHON
4. C#
5. C++
6. RUBY
7. SWIFT

**Variables:** Espacios de memoria en la computadora que se utilizan para la ingreso de datos temporales, que después se usaran para la transmisión de información almacenada en la variable. 
### **TIPO DE DATOS**

Son definiciones de la información ingresada dentro de los datos los cuales al categorizarse por tipo facilita su extracción.
![[tabla de datos.jpg]]
### **OPERADORES LÓGICOS**
Se usan para comparar dos variables o expresiones y obtener un valor verdadero o falso.

![[comparadores.png]]

### **CONDICIONES**
Grupo de sentencias que permite tomar una decisión entre una opción y otra opción según expresión que escojas.

#### **Estructuras condiciones**

###### *Condición simple*:
Esta se compone de las opciones de si, si no y no para evaluar si una condición si cumple con la solicitud:

```
if(condicion){
  // Líneas de código que se ejecutan
    si la expresión es cierta.
}else if(condicion){
//Líneas de código que se ejecutan
    si la expresión no es cierta.
}else {
//Líneas de código que se ejecutan
    si la expresión no es cierta en ninguna de las condiciones anteriores.
}
```
###### *Condición Anidada*: 
Son condiciones que contienen otras sub condiciones que se organizan en bloques que están dentro del código:

```
if(condicion){
  // Líneas de código que se ejecutan
    si la expresión es cierta.
}else if(condicion){
//Líneas de código que se ejecutan
    si la expresión no es cierta.
}else {
//Líneas de código de subcondicion anidada
	if(condicion){
	  // Líneas de código que se ejecutan si la expresión es cierta.
	}
	else {
		//Líneas de código que se ejecutan si la expresión no es cierta en ninguna de las condiciones anteriores.
	}
}
```
###### *Condición Múltiple: 
Son condiciones que contienen varias alternativas posibles de condición que se seleccione:

```
switch (expresion) {
    case constante1:
        conjunto de sentencias que se ejecutarán
        si expresion == constante1 es cierto.
        break;
    case constante2:
        conjunto de sentencias que se ejecutarán
        si expresion == constante2 es cierto.
        break;
    ...
    case constanteK:
        conjunto de sentencias que se ejecutarán
        si expresion == constanteK es cierto.
        break;
    default:
        conjunto de sentencias que se ejecutarán
        si expresion no retorna un valor coincide
        con ninguna de las constantes anteriores.
}
```
### **BUCLES** 
Es un proceso repetitivo, iterativo o ciclo el cual permite que un conjunto de sentencias se repitan o tengan un fin definido.
###### *Bucle for:* 
Estructura de código que permite la repetición de una tarea un numero especifico de veces:

```
for(initialization; condition; update)
{
	// hacer algo
}
```

- `initialization`, una sentencia que se ejecuta antes de entrar en el bucle
- `update`, sentencia que se ejecuta en cada iteración del bucle
- `condition`, sentencia que se evalúa para continuar el bucle
###### *Bucle do-while:*
Bloque de código que se repite al menos una vez y luego verifica una condición para evaluar si continuar y salir del bloque.

frase: Haz esto -> mientras se cumpla esto

```
do
{
    // Bloque de código a ejecutar mientras la condición sea verdadera
}
while(condicion)

// resto de código

```
###### *Bucle while:*
Bloque de código que se repite en mientras una condición evalué que es verdadera.

```
while(condicion){
// Bloque de código a ejecutar mientras la condición sea verdadera
}

```

**COMENTARIOS**

En desarrollo necesitas dejar referencias o saber como funciona necesitas comentarios estas son líneas cortas que se usan para indicar partes del código en especifico.

Estas líneas varían según la sintaxis; sin embargo su lógica es la misma

```

# cometarios python
/* comentarios javascript y typescript */
// comentarios java
```