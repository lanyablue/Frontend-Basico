##

Por muito tempo, e até hoje algumas páginas têm a estrutura feita utilizando divs, mas como vimos, esse elemento não nos traz nenhum valor semântico, por isso, no html5 surgiram novas tags de estrutura, que diferente das divs, têm significado. Conheceremos agora algumas delas: header, section, article, aside, footer.

O header, em português cabeçalho, é usado para identificar o topo de uma página, e não somente isso, mas uma sessão, um artigo ou qualquer outro segmento de página. Pode se colocar títulos, textos introdutórios, menu de navegação e entre outras coisas. Para colocar o menu de navegação utilizamos a tag nav, essa tag serve para indicar que temos um conjunto de links de navegação.

Dando sequência, o próximo será todas as navegações do site, que como o nome já diz, utilizaremos a tag section. As sessões de um site é um agrupado de conteúdo correlacionado. O elemento section é genérico, mas é útil para identificar esses grupos de conteúdo. Dentro de uma sessão por exemplo, temos conteúdos mais específicos como artigos, posts de um blog, um comentário enviado por um usuário etc. Estes artigos podem ser identificados pela tag article e nos passa a ideia de um conteúdo independente da nossa página. 

Continuando com o fluxo da nossa página, conseguimos imaginar conteúdos que vem ao lado do conteúdo principal, geralmente servindo como algum complemento, por exemplo avisos, biografia do autor nos casos de artigo de posts, informações de perfil, links de blog, ou produtos relacionados, todo esse conteúdo vem ao lado, por isso nome da tag é bem sugestivo: aside. Todos estes elementos são elementos de bloco, e o aside não é diferente, elementos de bloco ficam em uma nova linha, mas visualmente colocamos o aside ao lado do texto, logo isso é trabalho do css, no html só dizemos que esse conteúdo tem essa função de acompanhar o conteúdo e esta separado do mesmo.

O último elemento da nossa página é o rodapé, que utilizamos a tag footer para representá-lo, como o próprio nome já diz, geralmente encontramos o footer no final, como fechamento de uma página, artigo, sessão ou qualquer outro pedaço de página. O exemplo pratico estará na pasta: Iniciando o projeto, arquivo index.html.

##

Começando o exemplo pelo header, o colocamos abaixo dentro do body englobando a lista inicial, fechando-o logo após o fim da lista, com a indentação correta. Além de ser um header, ele é um menu de navegação, então utilizaremos também a tag nav e o processo de utilização é o mesmo, abrimos antes da lista e a fechamos no após o fim da lista, mais uma vez com indentação. Aqui não irá mudar em nada na visualização da página, mas muda semanticamente pois temos um header/cabeçalho e um menu de navegação.

Outra parte simples de identificar é o footer, então o colocamos ao final da página, neste exemplo o preenchemos com informações do copyright da página.

Agora é vez de todas as outras partes que são sessões do site, logo marcamos todas elas com a tag de section. Todas bem divididas, uma para cada sessão de conteúdo. Todas essas mudanças não mudarão nada visualmente na página, mas acrescentará na semântica do html, trazendo valores para parte de acessibilidade, para o google e para diversos sistemas de busca e rankeamento.

##