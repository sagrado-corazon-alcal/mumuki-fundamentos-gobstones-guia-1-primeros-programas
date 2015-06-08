Ahora que combinamos operaciones, la cosa se pone un poco mas complicada, porque hay que tener mas cuidado con el orden. Por ejemplo, estos dos programas no son equivalentes:


```puppet
program {
  Poner(Rojo)
  Mover(Este)
  Poner(Negro)
  Mover(Norte)
  Poner(Verde)
}
```

y

```puppet
program {
  Mover(Este)
  Poner(Rojo)
  Poner(Negro)
  Mover(Norte)
  Poner(Verde)
}
```

**¡Pensá por qué!**