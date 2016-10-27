Recordá que las funciones observadoras de campos son tus amigas. Por ejemplo, si declarás un registro Celular: 

```puppet
type Celular is record {
   field numero
   field compania
}
```

Automáticamente quedan disponibles funciones que permite inspeccionar los campos del registro, que se llaman igual que el campo: 

```puppet
program {
  unCelular := Celular(numero <- 152200000000, compania <- cloro())
  
  //notá que la función se llama 
  //igual que el campo
  return (numero(unCelular))
}
```


```puppet
program {
  //de igual forma existe una 
  //función compania, que toma un registro y 
  //denota su compañía
  return (numero(Celular(numero <- 15323020202, compania <- impersonal())))
}
  
```

