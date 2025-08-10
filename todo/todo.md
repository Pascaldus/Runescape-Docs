---
title: To-Do
parent: todo
nav_order: 2
---

# To-Do List

Combat doelen — vink ze af als ze klaar zijn.  
De lijst wordt automatisch opgeslagen in je browser, dus je voortgang blijft bewaard.

# Berserker Ring Grind

<div id="todo-list">
  <label><input type="checkbox" data-id="barrows"> Barrows farmen tot 2500 Death runes.</label><br>
  <label><input type="checkbox" data-id="varlamore"> Varlamore Nobles tot gold voor 12.500 fire runes.</label><br>
  <label><input type="checkbox" data-id="iban"> Iban's Staff rechargen.</label><br>
  <label><input type="checkbox" data-id="rex"> Dagannoth Rex farmen voor Berserker ring of out of Death Runes.</label>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const checkboxes = document.querySelectorAll('#todo-list input[type="checkbox"]');
    
    checkboxes.forEach(checkbox => {
      const saved = localStorage.getItem('todo-' + checkbox.dataset.id);
      if (saved === 'true') checkbox.checked = true;
      
      checkbox.addEventListener('change', function() {
        localStorage.setItem('todo-' + checkbox.dataset.id, checkbox.checked);
      });
    });
  });
</script>
