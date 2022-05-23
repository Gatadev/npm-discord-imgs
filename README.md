# discordimgs

Este es un paquete por el cual podrás obtener imágenes de cualquier tipo aleatoriamente, no es la gran cosa, pero al menos tiene contenido multimedia...

## Instalacion
Instala el paquete usando la consola o buscándolo en la selección de paquetes: `discord-imgs`.
```
$ npm i discord-imgs
```
## Uso:
```js
const dimgs = require('discord-imgs');
```

## Metodos disponibles:

```js
//Memes
dimgs.randomMemeAll()
dimgs.randomMemeVideo()
dimgs.randomMemeImagen()

/* ==== Proximamente mas ==== */
```

## Ejemplos:

### Memes:

 - Memes de cualquier formato `mp4` `png` `jpg` `gif` etc..

```js
//Definir el paquete:
const dimgs = require('discord-imgs');

console.log(dimgs.randomMemeAll())
/*Devolvera un link de discord que sera de un meme,
ya sea imagen o video.*/
```

 - Memes de solo imágenes.
```js
//Definir el paquete:
const dimgs = require('discord-imgs');

console.log(dimgs.randomMemeImagen())
/*Devolvera un link de discord random
que solo seran de imagenes*/
```

 - Memes de solo vídeos.
 
```js
//Definir el paquete:
const dimgs = require('discord-imgs');

console.log(dimgs.randomMemeVideo())
/*Devolvera un link de discord random
que solo seran de videos*/
```