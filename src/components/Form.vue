<template>
  <form class="clear">
    <div class="input-group flex flex--column">
      <label for="text">Text</label>
      <input type="text" id="text" placeholder="Text" />
    </div>

    <div class="input-group flex flex--column">
      <label for="email">E-mail</label>
      <input type="email" id="email" placeholder="E-mailadres" />
    </div>

    <div class="input-group flex flex--column">
      <label for="number">Number</label>
      <input type="number" id="number" placeholder="Getal" />
    </div>

    <div class="input-group">
      <input type="checkbox" id="checkbox1" />
      <label for="checkbox1">Checkbox 1</label>

      <input type="checkbox" id="checkbox2" />
      <label for="checkbox2">Checkbox 2</label>

      <input type="checkbox" id="checkbox3" />
      <label for="checkbox3">Checkbox 3</label>
    </div>
  </form>
</template>