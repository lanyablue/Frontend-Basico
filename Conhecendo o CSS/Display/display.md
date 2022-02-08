##

Agora que conseguimos definir tamanhos para os nossos elementos, é importante também conseguir definir a forma como eles irão aparecer na tela. Sobre elementos em bloco e inline, retomando, já havia dito que os elementos têm um comportamento padrão, mas podemos modificá-lo, isso com a propriedade display do css, que é bem importante para conseguirmos controlar o nosso layout. Vamos ver agora os valores dessas propriedades e como elas funcionam.

O primeiro é deixarmos o nosso elemento em bloco, esses elementos possuem uma quebra de linha em cima e em baixo, e não permite que outros elementos sejam posicionados ao lado dele, 
Outra forma também já citada é a inline, ou seja, em linha, isso significa que o elemento é renderizado dentro do bloco na mesma linha, ou seja não ocorre uma quebra, ‘span’ e o ‘a’ são os mais conhecidos dele. Esses elementos podem ser colocados dentro de um parágrafo, que é um bloco, sem quebrar o seu fluxo.

Agora para ter o tamanho definido do block e a característica de ser em linha do inline, existe um valor que é a mistura deles, que é o inline-block, a diferença deste elemento para o inline, é que o inline-block respeita as propriedades enquanto o inline não respeita, e ele também mantem o elemento em linha como o inline faz, além de mostrar os elementos, podemos também esconde-los, para isso existe o valor none, que é como se o elemento não existisse, ele é retirado totalmente da tela, existe um elemento que é o display none por padrão que não iremos falar dele nesse curso, mas a titulo de curiosidade é a tag script, ela é usada para adicionar Javascript na página, assim como a tag style é usada para adicionar css na página.

Uma visão diferente para pensarmos em uma página, é imaginar que tudo são blocos, cada um dos elementos sem exceção, não importa se é um círculo, ou texto, vamos tentar começar a imaginar tudo em uma página como um bloco. Por exemplo se acessarmos a página do google, tudo é bloco, a logo, o texto, as caixinhas, e esses blocos podem ter altura largura, pading, margem, borda, etc e essa forma de pensar é extremamente importante pois todas as páginas funcionam assim, em blocos mesmo que o bloco não estejam explícitos.

Primeiro ponto que podemos pensar é que todo bloco tem um tamanho, ou seja, uma largura e uma altura, essas propriedades no css se chama width e hight. Começando pelo width, o valor padrão dele vai depender do display do elemento, se for um elemento block o padrão é ser 100% da largura, pegando todo o espaço horizontal disponível. Elementos inline-block se ajustam ao tamanho horizontal do conteúdo por padrão, já elemento inline eles não têm tamanho fixo, e a propriedade widht não consegue ser aplicada a eles. Então para elementos que não são inline, podemos definir um valor especifico, sobrescrevendo o valor padrão.

Veja o exemplo em O projeto/index.css

##