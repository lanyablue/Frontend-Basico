##

Seletores de tipo, neles adicionamos o código html pelo tipo da tag, logo se queremos aplicar um estilo para todos os elementos de paragrafo faremos um seletor, mas se por exemplo precisarmos aplicar uma margem para fazer o estilo de um bloco, não só para os elementos do tipo, mas também para os hs e/ou algum outro tipo futuro, neste momento o seletor por tag seria muito trabalhoso e engessado, para isso existe os seletores de classe.

Seletores basicamente são um rotulo, podemos rotular todos os elementos da maneira que quisermos no html, colocando nos elementos o atributo class junto com o valor desejado que seja um nome, e ele irá representar nossa classe. No css para referenciar esta classe, utilizamos a sintax: .nome-da-classe { propriedade: valor} (com o ponto)

Caso você queira mudar somente um elemento de uma classe, utilize o seletor id logo após a classe, esse já tem uma ideia contraria da classe. Enquanto a classe reutiliza código em vários lugares, a ideia do id é ser estritamente único, logo só será usado em um único lugar. Sua sintax: #meu-id { propriedade: valor} (com a hash)

Uma analogia interessante para entendermos a diferença entre class e id é comparar ao nosso CPF, existem várias pessoas chamadas Barbara no mundo, que seria a classe, porém cada uma tem seu CPF único, logo sendo o id.

Existe uma regra quando se trata de nomes de classes e ids, a melhor forma de nomeá-las é relacioná-la ao conteúdo, considerando o que ele é de verdade, não sendo relacionado a aparência e não como ele é, pois, aparência é facilmente alterável, o que de fato aquela classe é para o elemento é mais difícil de se encontrar porem o ideal. Alguns exemplos de nome de classe:  container, produtos, post, carrinho. Você pode mudar a aparência de um post por exemplo, mas ele continuara sendo um post, e isso possibilita que seu css fique mais manutenível e legível.

Já o id tem outra utilidade além de estilizar no css, que é poder ser referência do próprio href como forma de redirecionamento.

Veja os exemplos em exemplo.html

##



