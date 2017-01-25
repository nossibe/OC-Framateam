# Variable multiligne

La solution toute simple, inclure les tags de commentaires et changer la taille de la variable
```javascript
var sContent3 = function(){/*
<div class="svg-container">
</div>
*/}.toString().slice(14,-3)
```

