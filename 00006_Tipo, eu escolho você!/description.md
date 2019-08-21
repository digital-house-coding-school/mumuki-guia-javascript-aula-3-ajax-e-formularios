**Esclarecimento: Os erros neste exercício não são exibidos tão bonitos quanto gostaríamos. Preste atenção ao texto em negrito e sublinhado para encontrar uma boa pista**

Vamos modificar a palavra "click!" para algo mais interessante.

Gostaríamos que quando o usuário clicasse no tipo "fire" a tag `<p>` diz "fire: https://pokeapi.co/api/v2/type/10/"

Como você pode fazer para conseguir isso?

Dentro do evento definido para o `<li>` você pode usar a variável `this` que representará o <li> clicado.

Quer dizer:

> Dentro do evento, `this.innerHTML` lhe dará o nome do tipo clicado e` this.getAttribute ("url") `lhe dará o URL do tipo escolhido: wink:

Sucessos!