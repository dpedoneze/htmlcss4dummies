##  CSS - ordem e pesos na declaração

A ordem que importa é a ordem no momento da definição e não quando o mesmo é utilizado, portanto:

```css
.pokemons {
  color: gray;
}

.fire-type {
  color: red;
}
```

toda vez em que encadearmos as classes `.pokemons` e `.fire-type`, o texto será exibido com a cor vermelha.
