Hagamos un último ejercicio con rectángulos: queremos poder redimensionarlos. Para eso necesitamos una función `estirar`, que tome un rectángulo y un factor de redimensión (un número) y denote el cuadrado con sus lados estirados en ese proporción. 

Por ejemplo, el programa: 

```puppet 
program {
  return (estirar(Rectangulo(base <- 2, altura <- 5, color <- Azul), 3))
}
```

denota `Rectangulo(base <- 6, altura <- 15, color <- Azul)`. 

> Escribí la función `estirar`