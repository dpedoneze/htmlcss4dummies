##  CSS - ordem e pesos na declaração


<img src="resources/css-specificity-2.png">

<style type="text/css">
.reveal ul {
  padding: 0;
}

.reveal ul li {
  color: #ccc;
}

.reveal li {
  float: left;
  padding-left: 0;
  margin: 10px;
  margin-left: 80px;
  color: #fff;
}

.reveal  li.favorite {
  color: green;
}

.favorite {
  color: gold;
}
</style>

<ul>
  <li class="favorite">Charmander</li>
  <li>Squirtle</li>
  <li>Bulbasaur</li>
</ul>

> Quando adicionamos `!important` em qualquer declaração, ela automaticamente recebe o peso máximo.
