**Esclarecimento: Os erros neste exercício não são exibidos tão bonitos quanto gostaríamos. Preste atenção ao texto em negrito e sublinhado para encontrar uma boa pista**

O que vamos tentar fazer é clicar no nome de um tipo... e mostrar os pokemons associados!

Se você se lembra da API, ficou assim:

```javascript
{
  "results": [
    {
      "name": "fogo",
      "url": "https://pokeapi.co/api/v2/type/10/",
    }
  ]
}
```

Ou seja, cada tipo tem uma URL de referência com mais informações.

A fim de recuperar este URL, então devemos tê-lo em algum lugar no `<li>`

É por isso que pedimos que você adicione ao exercício anterior um atributo no `<li>` chamado "url" que contém o URL fornecido pela API.