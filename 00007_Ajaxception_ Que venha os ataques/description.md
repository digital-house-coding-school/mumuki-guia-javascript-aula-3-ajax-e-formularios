**Esclarecimento: Os erros neste exercício não são exibidos tão bonitos quanto gostaríamos. Preste atenção ao texto em negrito e sublinhado para encontrar uma boa pista**

Chegamos ao final da história.

Nós trazemos todos os tipos. Nós temos eventos em cada `<li>`. Sabemos como obter o URL de referência clicando no `<li>`. Nós até simplificamos o código um pouco.

O que está faltando?

Nós também adicionamos no HTML um `<ul class="attacks">` que gostaríamos de ser preenchidos com ataques do tipo escolhido.

Seu desafio então é adicionar a seguinte lógica ao evento do `<li>`:

> 1. Limpe todo o conteúdo de `<ul class ="attacks">`

> 2. Faça um pedido por AJAX para o URL do tipo escolhido

> 3. O JSON que retornará o pedido tem um atributo chamado "moves" que contém um array com todos os ataques

> 4. Uma vez que o array de ataques é obtido, **para cada um** você deve adicionar um `<li>` no `<ul class ="attacks">` que diz no conteúdo o nome do ataque. Cada um dos ataques tem um atributo "name" com o texto que você precisa.

Infelizmente, dada a complexidade do exercício, a plataforma é curta para avaliarmos se a solução está correta, de modo que este exercício funcionará como um experimento.

Caso você goste, na faixa abaixo você encontrará a solução :wink: