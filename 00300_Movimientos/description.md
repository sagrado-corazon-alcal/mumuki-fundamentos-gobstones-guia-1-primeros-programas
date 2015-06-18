Hasta ahora no tuvimos mucha emoción, porque el tablero lo generamos por vos. Pero la cosa se pone interesante ahora: un programa no solo tiene un tablero, sino que ¡puede mover al cabezal a nuestro antojo!

Por ejemplo, si tenemos un tablero **inicial** vacío, podemos fácilmente escribir un programa que mueva el cabezal una posición hacia el **norte**:

| Inicial |   | Final |
|:-------:|:-:|:-----:|
|![3x3h](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/3x3h.png)|<i class="fa fa-arrow-right"></i>|![3x3h01](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/3x3h01.png)|

El **código** del programa (es decir, la descripcion del programa que le daremos a la computadora) que hace esto es el siguiente:

```puppet
program {
  Mover(Norte)
}
```

> ¡No te vemos muy convencido! Copiá y pegá el código anterior en el editor a tu derecha y dale Enviar.
