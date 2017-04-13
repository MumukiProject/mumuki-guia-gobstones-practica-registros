¡Hola! 

En Gobstones contamos con varias herramientas para modelar los elementos de nuestros problemas. Por ejemplo, tenemos datos de tipos simples: números como el `5` o el `12`, o colores como `Rojo` y `Verde`. Así, por ejemplo, podríamos denotar la cantidad de maíz de la siguiente forma: 

```puppet
kilogramosDeMaiz := 22

//por ejemplo, podríamos denotar con Rojo al maíz transgénico
//y con Verde, al común
tipoDeMaiz = transgenico() 
```

Pero esto sólo nos sirve para modelar cosas muy sencillas. Representar una persona, un automóvil, una votación, una nota musical, un deseo, un suceso en un capítulo de Zamba, la transformación de un Pokémon o de Gokú, etc requieren de una nueva forma de representar información: registros :sunglasses:.

Un registro es una forma de agrupar un conjunto de campos (datos), que: 

 * siempre tiene la misma cantidad de campos
 * los campos pueden tener tipos de datos diferentes entre sí
 * no tiene orden entre los campos; los valores se referencian con identificadores (nombres de campos)

:exclamation: ¿Y cómo se escriben? [Mirá acá](http://inpr.web.unq.edu.ar/?dl_id=52)

Bueno, basta de introducción. ¡Vamos a practicar!