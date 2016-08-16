Entendamos qué es lo que acabamos de hacer: escribir un programa.

Todo programa tiene exactamente un `program`: una sección del código que declara los comandos (acciones) que queremos que la máquina realice sobre el tablero **inicial**. Al **ejecutar** un programa obtendremos un tablero **final**.

La sintaxis de un `program` es bastante simple:

1. escribimos una línea (renglón) que diga `program`, seguido de una llave de apertura: `{`
1. a continuación, los comandos: uno por línea
1. y finalmente, una última llave que cierra la que abrimos anteriormente `}`

Algunos ejemplos de `program`s:


```puppet
program {
}
```

(no hace nada)


```puppet
program {
  Mover(Norte)
}
```

(mueve el cabezal una posición hacia el norte)

```puppet
program {
  Mover(Norte)
  Mover(Norte)
}
```

(mueve el cabezal dos posiciones hacia el norte)

> Sabiendo ésto, escribí un programa que en un tablero de 2x4 con el cabezal en el origen (la celda de abajo a la izquierda), mueva el cabezal tres veces hacia el norte:

| Inicial |   | Final |
|:-------:|:-:|:-----:|
|![2x4h00](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/2x4h00.png)|<i class="fa fa-arrow-right"></i>|![2x4h03](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/2x4h03.png)|
