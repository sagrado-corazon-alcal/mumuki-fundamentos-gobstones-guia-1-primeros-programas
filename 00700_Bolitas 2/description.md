Algo interesante de nuestros tableros es que en sus celdas podemos poner cualquier cantidad de bolitas de cualquier color.

Por ejemplo, si tenemos este tablero:

![5x2h](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/5x2h.png)

y ejecutamos el siguiente programa:

```puppet
program {
  Poner(Rojo)
  Poner(Rojo)
  Poner(Azul)
  Poner(Verde)
  Poner(Rojo)
}
```

el cabezal colocará en la celda actual tres bolitas rojas, una azul y una verde.

> ¡Copiá este programa en el editor y fijate cómo queda el tablero!