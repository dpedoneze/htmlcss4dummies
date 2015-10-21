##  CSS - encadeamento

> Classes podem ser encadeadas, para então formarem novas classes dinâmicas

```css
.pokemons {
  color: white;
  font-size: 30px;
}

.shiny {
  color: gold;
}

```

<style type="text/css">
  .pokemons {
    color: white;
    font-size: 30px;
  }

  .shiny {
    color: gold;
  }
</style>

<div class="row">
  <div id="ivesaur" class="col-6 pokemons">
    Pikachu
  </div>
  <div class="col-6 pokemons shiny">
    Pikachu Shiny
  </div>
</div>
