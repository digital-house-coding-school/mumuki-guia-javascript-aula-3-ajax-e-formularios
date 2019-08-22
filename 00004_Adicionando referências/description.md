**Esclarecimento: Os erros neste exercício não são exibidos tão bonitos quanto gostaríamos. Preste atenção ao texto em negrito e sublinhado para encontrar uma boa pista**

O que vamos tentar fazer é clicar no nome de um tipo... e mostrar os pokemons associados a esse tipo!

Lembra da resposta da API? 
É nesse formato :

```javascript
{
  "results": [
    {
      "name":"fire",
      "url":"https://pokeapi.co/api/v2/type/10/",

    }
  ]
}
```

Ou seja, cada tipo tem uma URL de referência com mais informações.

Devemos guardar essa URL em algum lugar, que tal na `<li>` do exercício anterior?

Adicione a `<li>` do exercício anterior um atributo chamado "url" que contém a URL fornecida pela API.
