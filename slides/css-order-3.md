##  CSS - ordem e pesos na declaração

Portanto, além da posição do seu CSS declarado, a especificidade em que o CSS foi declarado também importa.

```css
ul li {
  color: #ccc;
}

li {
  margin: 10px;
  color: #fff;
}

li.favorite {
  color: green;
}

.favorite {
  color: gold;
}

```

<style type="text/css">
.reveal ul {
  padding: 0;
}

.reveal ul li {
  float: left;
  padding-left: 0;
  margin: 10px;
  margin-left: 80px;
  color: #fff;
}
</style>

<ul>
  <li>Charmander</li>
  <li>Squirtle</li>
  <li>Bulbasaur</li>
</ul>
