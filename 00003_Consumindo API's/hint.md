```javascript
window.addEventListener("load", function () {
    fetch("https://pokeapi.co/api/v2/type/")
    .then (function(resposta) {
      return response.json();
    })
    .then (function(json) {
      tipos = json.results
    });
});
```

Nesse caso, a variável tipos é um array de objetos literais.

Cada um desses objetos tem o atributo "name" com o nome que você está procurando :wink: