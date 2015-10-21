##  CSS - Classes

```html
  <div class="pokemons water-type">
    Squirtle
  </div>
  <div class="pokemons fire-type">
    Charmander
  </div>
  <div class="pokemons grass-type">
    Bulbasaur
  </div>
  <div class="pokemons">
    Pikachu
  </div>
```

<style type="text/css">
  .pokemons {
    font-size: 36px;
    padding: 10px;
    border: solid 1px white;
    color: #fff;
  }

  .water-type {
    background-color: rgb(109, 156, 190);
  }

  .grass-type {
    background-color: rgba(109, 156, 54, 1);
  }

  .fire-type {
    background-color: hsl(25, 89%, 50%);
  }
</style>

<div class="row">
  <div class="col-3 pokemons water-type">
    Squirtle
  </div>
  <div class="col-3 pokemons fire-type">
    Charmander
  </div>
  <div class="col-3 pokemons grass-type">
    Bulbasaur
  </div>
  <div class="col-3 pokemons">
    Pikachu
  </div>
</div>
