Genial, ya entendiste cómo mover el cabezal del tablero usando la operación `Mover` y las direcciones (`Sur`, `Oeste`, etc). Vayamos un paso más allá: las **bolitas**.

En cualquier celda de nuestro tablero podemos poner `bolitas`. Las hay de distintos colores:

 * Rojas (`Rojo`)
 * Azules (`Azul`)
 * Negras (`Negro`)
 * Y verdes (`Verde`)

Por ejemplo, este es un tablero con una bolita roja y una negra:

![2x2r10n11](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/2x2r10n11.png)

Además de moverse, el cabezal también puede poner bolitas en la **celda actual**. Para eso contamos con la operación `Poner`, que le dice al cabezal que deposite una bolita del color dado:

```puppet
program {
  Poner(Rojo)    
}
```

> ¡Probá este programa! Copiá el código en el editor, envialo, y verás lo que pasa al ejecutarlo sobre este tablero:

![3x3h](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/3x3h.png)
