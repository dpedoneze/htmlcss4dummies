##  CSS - box-sizing

A propriedade `box-sizing` é utilizada para calcular a largura e altura dos elementos.
Por padrão, essa propriedade é `content-box`, a qual não leva em conta os valores de borda e padding do elemento.

```css
* {
  webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
         box-sizing: border-box;
}
```

> Utilizando `border-box`, não é necessário ficar (re)calculando os valores de altura e largura quando a borda e/ou o padding do elemento se alterar.
