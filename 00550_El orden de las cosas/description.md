Cuando trabajamos en Gobstones, hacemos las cosas en un cierto orden. Por ejemplo, si tenemos este programa:

```gobstones
program {
  Mover(Norte)
  Mover(Este)
}
```

una forma posible de leerlo (llamada **operacional**) es como lo haría una máquina, en orden, de arriba hacia abajo:

1. primero se mueve al norte: `Mover(Norte)`
1. luego se mueve al este: `Mover(Este)`

Y de hecho **se ejecuta de esa forma**. Esto es _cómo_ lo hace.

Sin embargo, los humanos somos mejores hablando del todo, del resultado final: el objetivo del programa, es decir, _qué_ es lo que hace. Y si lo pensamos así (**denotacionalmente**) lo que hace es: **mueve el cabezal al noreste**.

Por eso hay varias formas de resolver un mismo problema: podemos escribir varios programas que hagan lo mismo (el _qué_), pero que lo hagan de forma diferente (el _cómo_).

> Veamos si entendiste esto: escribí otro programa que haga lo mismo que el de arriba (mover hacia el noreste), pero de manera distinta. **Ojo:** tiene que funcionar en un tablero de 2x2.
