# Variable multiligne

La solution toute simple, créer une fonction mettre le corps du contenu multilinge entre des tags de commentaires et changer la taille de la variable en enlevant fonction=(){/* et */}
```javascript
var sContent3 = function(){/*
<div class="svg-container">
</div>
*/}.toString().slice(14,-3)
```

