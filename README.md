# TS basics

- Instalaciones necesarias para trabajar cómodamente en TypeScript
- El compilador de TypeScript corriendo.

compile tsc file 
```js
$ tsc <filename.ts>
```
this will create a new js file

Watch mode
- compiles authomatically

```js
tsc <filename.ts> -w 
```

Initialize ts project 

```js
tsc -init
```

creates a esconfig.json file

```js
tsc *.ts -w
```

### ¿Qué son los tipos de datos?
 
Una introducción a los diferentes tipos de datos que existen en TypeScript.

Se dividen en dos:

**Primitivos**

- Booleanos.
- Números.
- Strings.
- Tipo Any.
- Arreglos.
- Tuplas.
- Enumeraciones
- Retorno void
- Null
- Undefined

**Compuestos**

- Objetos Literales
```js
let persona = {
  name: 'Sofia',
  lastName: Mejia
}
```
- Clases
```js
class Persona {
  name;
  lastName
}
````
- Funciones
