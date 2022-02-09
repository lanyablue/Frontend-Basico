##

Margin x Padding

Agora pensando um pouco além do tamanho, é estranho termos uma página e o conteúdo colado um ao outro, geralmente colocamos um espaçamento entre eles, uma distância para dar um respiro, um layout no geral, para isso temos duas propriedades: margin, padding. As duas colocam esse espaçamento, então qual a diferença entre elas?

Margin: Imagine que temos um bloco, um conteúdo, quando utilizarmos a propriedade margin acrescentamos um espaço para fora, externo ao elemento, ou seja, para fora dessa “caixinha” que é o conteúdo.
Enquanto o Padding, acrescentamos um espaço interno ao elemento, ou seja, para dentro da “caixinha”.

O que separa esses dois tipos de espaçamento é o border, que é o que determina o espaço do conteúdo, então para dentro é o pading e para fora o margin.
Estas duas propriedades também têm suas formas de serem utilizadas, a primeira delas é especificando cada um dos lados, que são eles o margin-top, margin-bottom, margin-left, margin-right, e o mesmo para o padding, exemplo em  exemplo_margin.png. Existe também a forma reduzida, que você usa apenas a propriedade margin, ou a propriedade padding, por motivos de didáticas usaremos de exemplo apenas o margin, mas os mesmos se aplicam ao padding. Existem quatro formas de você representar estes valores, uma dica é que sempre comece no top, siga o sentido horário e os opostos são agrupados. 

##

Então se tivermos quatro valores: Veja esses exemplos também em margin.png
margin: 1em, 2em, 3em, 5em;
margin: top right left bottom

##

Agora podemos ter três valores, percebe que iremos remover o valor do left, então teríamos:
Margin: 1em, 2em, 3em;
Margin: top right/left bottom;

##

Primeiro é o top, o segundo é o right, por removermos o left utilizamos o oposto a ele, então ele se junta ao right, e o último é o bottom. Então o primeiro valor do exemplo representa top, o segundo o right e o left, e o terceiro o bottom. Veja o exemplo também em margin2.png.

Agora podemos representar com apenas dois valores, então removeremos o bottom, logo o processo é o mesmo, primeiro é o top e o oposto que é o bottom, e o segundo valor é o right e left que é oposto a ele. Exemplo margin3

E se tivermos só um valor, ele representará todos os lados, top bottom right left. Então essa ideia sempre começa no top, seguindo no sentido horário fazendo o agrupamento dos opostos. Então quatro valores é um em cada um. Três valores é o top, right e left que se agrupam e depois o bottom. Dois valores, top e bottom agrupam,  o right e left se também agrupam. E com um valor, todos são agrupados. 

Tanto o margin quanto o padding, eles funcionam um pouco diferente nos elementos inline. Começando pelo margin, ele só funciona nas medidas horizontas, ou seja, para o left e para o right, isso somente em elementos inline. Uma forma de pensar é que em um texto, é difícil mexer somente em uma palavra, só em um span sem alterar todo o restante do texto, com o padding é bem parecido, ele até aparece como se ele fosse aplicado, mas nada acontece, ele não é de fato renderizado, e só funciona nesse cenário com left e right.

##