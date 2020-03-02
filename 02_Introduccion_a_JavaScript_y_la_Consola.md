# 2. Introducción a JavaScript y a la Consola 01:27:02

## Introducción a la sección 02:28

:+1:

## Temas puntuales de la sección 00:17


#### Temas de la sección

En esta sección tocaremos los siguientes temas:

* Historia de JavaScript

* Uso de JavaScript en la industria actual

* Hola Mundo en JavaScript

* Creación de variables y constantes

* Introducción a la consola de JavaScript

* Depuración y breakpoints

* Problemas con la declaración de variables con var

* Prompts, alerts, confirms.

Recuerden que al final de la sección tendrán el código fuente para que lo descarguen en caso de que sea necesario para compararlo o bien para tenerlo como respaldo.

## JavaScript y su historia 04:44

Creador: Brendan Eich, empleado de NetScape => LiveScript => JavaScript

Microsoft => JScript

En 1997 Se crea la especificación JS [ECMA](https://www.ecma-international.org/) (European Computer Manufacturers Association)

Comite creado ECMA TC39

* Primer Standar ECMA-262

## Usos de JavaScript 04:17

Con JS podemos crear muchos tipos de aplicaciones:

* [Google Maps](https://www.google.es/maps/@40.3813641,-3.7333547,4z)

* [Presentaciones con REVAL.JS](https://revealjs.com/#/)

* [Servidores Web con Node](https://nodejs.org/es/)

   * Manejar peticiones
   * Crear archivos en el sistema del servidor 
   * Conectarnos a BD
   * Recuperar información 
   * Generar información de respuesta a las peticiones 
   * Comunicación en tiempo real con sockets.
   
* Crear Video Juegos [On the Run](http://js13kgames.com/games/underrun/index.html)

* Aplicaciones Móviles 
   
   * Ionic
   * React Native
   * NativeScript
   * Electron (Aplicaciones Nativas)
   
* Aplicaciones Web

   * Angular
   * React
   * Vue
      

## Hola Mundo 13:52

### 1. Hola Mundo Desde el Navegador

Cada navegador tiene su propia implementación del ECMAScript por lo que cada uno tiene su propia versión de JS.

Vamos a abrir Google Chrome y con F12 las Herramientas de Desarrollador en la pestaña Consola.

Escribimos lo siguiente:

```js
> console.log('Hola Mundo');
  Hola Mundo
  undefined

> document.write('Hola Mundo');
undefined
```

Las anteriores son dos formas diferentes de hacer nuestro "Hola Mundo", la primera saca el mensaje en la Consola y la segunda en el HTML.

<img src="images/c2/2-hola-mundo-navegador.png">

### 2. Hola Mundo Desde Consola Node

Usando Node como interprete de JS.

```js
192:~ adolfodelarosa$ node --version
v12.14.0

192:~ adolfodelarosa$ node
Welcome to Node.js v12.14.0.
Type ".help" for more information.

> console.log('Hola Mundo');
Hola Mundo
undefined
> 
```

### 3. Hola Mundo Interpretando con Node

Vamos a creaer el archivo `app.js` con el contenido:

```js
console.log('Hola Mundo');
```

Y desde la terminal ejecutamos el comando:

```sh
192:01-fundamentos adolfodelarosa$ node app.js
Hola Mundo
192:01-fundamentos adolfodelarosa$ 
```

Vemos como interpreta el contenido JS de nuestro archivo.

### 4. Hola Mundo Dentro un Archivo HTML

*Mala Practica*

`index.html`:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
</head>
<body>
    <script>
        console.log('Hola Mundo desde HTML');
    </script>
</body>
</html>
```

### 5. Hola Mundo Importando Archiivo JS Desde un Archivo HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
</head>
<body>
    <script src="app.js"></script>
</body>
</html>
```

Al abrir el archivo con el navegador y ver la Consola, veremos el mensaje `Hola Mundo`

Aun que `<script src="app.js"></script>` puede ir dentro de la etiqueta `<head>` es recomendable ponerlo antes de cerrar la etiqueta body `</body>` para que se cargue todo nuestro código HTML y después los archivos JS evitando bloquear la página.

## Introducción a variables y comentarios 12:47

## Introducción a la consola 10:10

## Depuración y breakpoints 10:23

## Orden y lugar de las importaciones 09:42

## Principal problema con la inicialización de variables con Var 07:25

## Prompt, confirm y alert 10:49

## Código fuente de la sección 00:08
