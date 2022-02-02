#

Criando uma página com um título e um paragrafo
Quais são as tags que fazem esse tipo de marcação?
O título principal se usa a tag h1, sabemos que os títulos possuem vários níveis. No html conseguimos marcar até seis níveis de títulos. Começando por h1, seguindo por h2 e até h6. O h é uma abreviação para heading, que significa título ou cabeçalho, e os números apresentam os níveis do cabeçalho.
Já para marcar parágrafo, usamos a tag p, abreviação para paragraph.
Segue o exemplo do arquivo exemplo1.html 
(Lembrando que o nome do arquivo principal PRECISA ser index, por motivos de didáticas, neste resumo usarei exemplo1 e exemplo2!!!!!)

#

Para o navegador entender símbolos e caracteres especiais, precisamos especificá-lo para ler a nossa página em utf8. Para isso, usaremos a tag meta, que é usada para mostrar meta dados, ou seja, diz ao navegador dados sobre o nosso conteúdo. Segue o exemplo em exemplo1.html de como usar a tag meta.

#

Aqui vemos a principal diferença entre a tag meta e as outras tag que citadas, as anteriores servem para adicionar novos conteúdos, enquanto as metas servem para configurações em geral.
Uma outra tag usada para configurar a página é a tag title, nela definimos o nome que a página terá na aba do navegador, segue o exemplo em exemplo1.html.
Entretanto, o código do exemplo1.html está totalmente desorganizado, com o conteúdo junto das configurações. Para deixar o código um pouco mais organizado existem novas duas tags para acionarmos, a head e o body. 
Fazendo analogia a uma pessoa, no head, que seria a cabeça, temos toda a parte operacional, e no body, que seria o corpo, temos todo o conteúdo. Segue o exemplo dessa organização no exemplo2.html

#

E sobre a indentação apresentada no exemplo2, como uma convenção entre os programadores, definimos que para um código ficar legível, tudo que está dentro de uma tag precisa ser indentado com um tab a mais. Se colocarmos todo o conteúdo em uma linha só, o browser conseguirá ler o código da mesma forma, mas para facilitar a leitura do código, trabalhar em equipe e trabalho com códigos maiores, usamos a indentação, sendo então uma boa prática de programação.
No código do exemplo2.html está faltando a tag html, que serve para indicar ao browser que estamos nos comunicando pela linguagem html. A tag html fica no começo do código em cima do head, e no final do código também. Precisamos também citar qual versão do html estamos usando, portanto, na primeira linha do código utilizamos a tag !DOCTYPE html, que informa que o código está usando a versão mais recente do html. Segue as mudanças no exemplo2.html

Essa é a base necessária para se criar todos os códigos HTML.

#