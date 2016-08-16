Hasta ahora lo que hiciste no fue muy emocionante, porque no te enseñamos cómo darle instrucciones a la máquina y sólo te mostramos un tablero. En este ejercicio vamos a aprender una de las órdenes que podemos darle a la máquina: mover el cabezal.

Por ejemplo, partiendo de un tablero **inicial** vacío, podemos fácilmente escribir un programa que mueva el cabezal una posición hacia el **norte**:

| Inicial |   | Final |
|:-------:|:-:|:-----:|
|![3x3h](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/3x3h.png)|<i class="fa fa-arrow-right"></i>|![3x3h01](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/3x3h01.png)|

El **código** del programa (es decir, el **texto** de la descripción de la solución que le daremos a la computadora) que logra esto es el siguiente:

```puppet
program {
  Mover(Norte)
}
```

> ¿No nos creés? Copiá y pegá el código anterior en el editor y dale Enviar.