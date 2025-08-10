---
title: Doelen
parent: To-do
nav_order: 1
---

# To-Do List

Combat doelen — vink ze af als ze klaar zijn.  
De lijst wordt automatisch opgeslagen in je browser, dus je voortgang blijft bewaard.

## Berserker Ring Grind

<div id="todo-list">
  <label><input type="checkbox" data-id="barrows"> Barrows farmen tot 2500 Death runes.</label><br>
  <label><input type="checkbox" data-id="varlamore"> Varlamore Nobles tot gold voor 12.500 fire runes.</label><br>
  <label><input type="checkbox" data-id="iban"> Iban's Staff rechargen.</label><br>
  <label><input type="checkbox" data-id="rex"> Dagannoth Rex farmen voor Berserker ring of out of Death Runes.</label>
</div>

**Tip bij Berserker Ring looten:**  
Imbue hem op deze manier → [YouTube Video](https://youtu.be/-Rb1osRt1Fo)

---

## Zombie Axe Grind

<div id="todo-list-axe">
  <label>
    <input type="checkbox" data-id="armouredzombies">
    <a href="https://oldschool.runescape.wiki/w/Armoured_zombie_(Zemouregal%27s_Base)" target="_blank" rel="noopener">Armoured Zombies</a> killen voor Broken Zombie Axe.
  </label><br>

  <label>
    <input type="checkbox" data-id="smithing70">
    <a href="https://oldschool.runescape.wiki/w/Giants%27_Foundry/Strategies" target="_blank" rel="noopener">Smithing</a> tot level 70 levelen via Giants' Foundry.
  </label><br>

  <label><input type="checkbox" data-id="maken"> Zombie Axe maken.</label><br>
</div>

---

### Extra Tip
Out of food? Ga dan naar [Karambwan Cooking](https://pascaldus.github.io/Runescape-Docs/skilling/karambwan.html)

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const initCheckboxes = (selector) => {
      const checkboxes = document.querySelectorAll(selector + ' input[type="checkbox"]');
      checkboxes.forEach(checkbox => {
        const save
