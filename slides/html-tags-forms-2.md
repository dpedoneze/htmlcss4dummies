##  HTML - formulários

```html
<form class="row" name="pkm_form" action="" method="get">
  <label for="pkms">Pokemon</label>
  <select name="pkms" id="pkms">
    <optgroup label="Starter">
      <option>Pikachu</option>
      <option>Bulbasauro</option>
      <option>Squirtle</option>
      <option selected>Charmander</option>
    </optgroup>
    <optgroup label="Tipo Pedra">
      <option>Onix</option>
      <option>Geodude</option>
    </optgroup>
    <optgroup label="Tipo Fogo (desabilitados)" disabled>
      <option>Vulpix</option>
      <option>Rapidash</option>
      <option>Magmar</option>
    </optgroup>
  </select>

  <fieldset>
    <legend>Tem certeza?</legend>
    <input name="sure" id="yes" type="radio"><label for="yes">SIM</label>
    <input name="sure" id="no" type="radio"><label for="no">NÃO</label>
  </fieldset>
</form>
```

<form class="row" name="pkm_form" action="" method="get">
  <div class="col-5">
    <label for="pkms">Pokemon</label>
    <select name="pkms" id="pkms">
      <optgroup label="Starter">
        <option>Pikachu</option>
        <option>Bulbasauro</option>
        <option>Squirtle</option>
        <option selected>Charmander</option>
      </optgroup>
      <optgroup label="Tipo Pedra">
        <option>Onix</option>
        <option>Geodude</option>
      </optgroup>
      <optgroup label="Tipo Fogo (desabilitados)" disabled>
        <option>Vulpix</option>
        <option>Rapidash</option>
        <option>Magmar</option>
      </optgroup>
    </select>
  </div>
  <div class="col-offset-1 col-5">
    <fieldset>
      <legend>Tem certeza?</legend>
      <input name="sure" id="yes" type="radio"><label for="yes">SIM</label>
      <input name="sure" id="no" type="radio"><label for="no">NÃO</label>
    </fieldset>
  </div>
</form>
