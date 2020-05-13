# JavaScript js

![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/480px-Unofficial_JavaScript_logo_2.svg.png)

Lenguaje de programación que trabaja en la web, genera paginas dinámicas, es un lenguaje interpretado, orientado a objetos débilmente pitado y dinámico.

Es uno de los 3 estándares de programación web y también se pueden realizar aplicaciones móviles, desarrollar aplicaciones para escritorio, iot y back-end

## Elementos en el lenguaje

- Datos que se guardan en la memoria
- Tareas o funciones, lo que se hará con los datos

---

## Valores de js

### Primitivos

- Numéricos = 40
- String = "curso de javascript"
- Booleanos = true - false
- Valores vacíos = null - undefined

### Tipo objetos

- Array = se coloca información dentro []

    [1,2,3]

    array.push("") = añadir elemento a array

    array.pop("") = eliminar el ultimo elemento del array

    array.unshift("") = añadir elemento al inicio del array

    array.shift("") = borra un elemento del array

    array.indexof("") = indice de un elemento

- Objeto = se usan para guardar objetos {}

    {nombre : "kzarama"}

---

## Variables (Representacion de un lugar de memoria reservada para guardar un valor)

Tiene dos pasos: 

- Declarar: reservar el espacio de memoria para guardar un valor
- Inicializar: poner un valor en un espacio de memoria

### Tipos de variables

- var = representa una variable

    var nombre = "kzarama";

    var animales = ["Perro", "Gato"];

    var Perro = {

    nombre: "Dante",

    raza: "Husky"

    }

- const
- let

---

## Funciones

### Imprimir en consola

console.log();

Declarar función

```jsx
function myFunction() {
	return 1;
}
```

```jsx
var myFuntion = funtion(a, b){
	return a + b;
}
```

Llamar la función

```jsx
myFunction();
```

```jsx
myFuntion(1, 2);
```

return = retorna el resultado deseado en una función

---

## Operadores

- + = sumar - concatenar
- - = restar
- * = multiplicar
- / = dividir
- ! = operador unario - falso
- = = asignar
- == = comparar el valor, retorna booleano
- === = compara tipo y valor, retorna booleano
- < = menor, retorna booleano
- > = mayor, retorna booleano
- <= = menor igual, retorna booleano
- >= = mayor igual, retorna booleano
- && = y lógico
- || = o lógico
- ++ = variable = variable + 1
- += = variable = variable + numero

---

## Condicionales

reglas para validar si algo es verdadero o falso, necesita de un booleano en el condicional

```jsx
if (condicional) {
	// codigo
}
```

```jsx
if (condicional) {
	// codigo
} else {
	// si no se cumple la condicion
}
```

```jsx
if (condicional) {
	// codigo
} else if (condicional) {
	// condicion si no se cumple la condicion
} else {
	// si no se cumple ninguna condicion
}
```

## Condicional ternario

```jsx
condition ? true : false;
```

## Switch

```jsx
switch (numero) {
	case 1:
		// codigo
		break;
	case 2:
		// codigo
		break;
	default:
		// codigo
}
```

---

## Ciclos

### For

```jsx
for(var i = 0; i < 5; i++){
	// codigo
}
```

```jsx
for(var index of array){
	// codigo
}
```

### While

```jsx
while(condicion){
	// codigo
}
```

---

## Objetos

### Constructor

```jsx
function object(atributo1, atributo2, atributo3) {
	this.atributo1 = atributo1;
	this.atributo2 = atributo2;
	this.atributo3 = atributo3;
}
```

### Inicializar objeto

```jsx
var newObject = new object("atri1", a"atri2", "atri3");
```

### Declarar objeto

```jsx
var objects = {
	atributo1: "atri1",
	atributo2: "atri2",
	atributo3: "atri3",
	funcion: function(){
		// codigo
	}
};
```

---

## Recorrer arrays

### Filter

```jsx
var filteredObject = objeto.filter(function(object){
	return object.atributo1 == "atri1"
});
```

## Map

```jsx
var filteredObject = objeto.map(function(object){
	return object.atributo1
)
```

## Find

```jsx
var filteredObject = objeto.find(function(object){
		return object.atributo1 === "atri1"
});
```

## ForEach

```jsx
objects.forEach(function(object){
	return object.atributo1;
});
```

## Some

```jsx
var objectSome = objects.some(function(object){
	return object.atributo1 == "atri1"
});
```

---

### Hoisting = cuando las variables y las funciones se declaran antes de que se procese cualquier tipo de código, solo pasa en versiones anteriores de js

```jsx
console.log("Hola " + name);
var name = "kzarama";
```

---

[Kzarama - Overview](https://github.com/Kzarama)
