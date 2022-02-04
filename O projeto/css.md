#

Deixando um pouco o html de lado, iremos aplicar um estilo básico na nossa página deixando ela um pouco mais bonita. Como já dito isso, o responsável pelo visual e estilo da página é o CSS.
C - cascading
S - style
S - sheets

CSS é uma linguagem utilizada para escrever folhas de estilo que irão definir a aparência de um documento. Para escrever em CSS precisamos seguir apenas uma regra que irá definir a forma com que cada estilo será aplicado a cada elemento do html. A regra consiste em termos um seletor, propriedade e valor:

seletor{
	propriedade: valor,
}

#

Para entender essa regra, é preciso entender os três termos básicos do CSS. Vamos supor que queremos pintar a parede de uma casa com a cor rosa, para pintar essa parede precisamos responder três perguntas:
O que?    -pintar
Onde?     -paredes
Como?     -usando tinta rosa

#

É a mesma com o CSS, precisamos definir ONDE, que seria qual elemento do html que queremos aplicar um estilo, que será o SELETOR.
O QUE que irar fazer com esse elemento html, como por exemplo mudar a cor da fonte, tamanho, sendo isso a PROPRIEDADE

E por último definir COMO irá definir essa propriedade, ou seja, qual é a cor, ou qual é o tamanho, qual é o VALOR da propriedade, no caso o rosa.
Então para que a cor da fonte dos títulos h1 seja rosa, responda:

O que?    - propriedade (cor da fonte)
Onde?     - seletor (títulos h1)
Como?     - valor(rosa)

#

Vamos então fazer um exemplo real, supondo que queremos fazer essas três coisas. O código em CSS para fazer isso seria:

 h1{
	color : pink;
}

Para isso, vamos criar um arquivo chamado index.css e nele colocar o selector, a propriedade e seu valor.
Após fazer isso, para referenciar o arquivo de css no html colocamos a tag <link rel=”stylesheet” href=”index.css”>.  Essa tag link faz a ligação entre o arquivo html e o css, é como se o html conversasse com o arquivo css pegando tudo que tem dentro do arquivo css para ele usar na sua página. O atributo rel stylesheet serve para mostrar o tipo de relacionamento que os dois arquivos estão criando, no caso é do tipo folha de estilo. E o atributo href serve para mostrar em qual local ele encontrará o arquivo css.

#

Outro conceito importante é o reset de CSS. Por padrão os navegadores vêm com um css básico definido, para isso precisamos reseta-lo para poder utilizá-lo da forma que quisermos. 
Esse reset precisa ser um novo arquivo css referenciado da mesma maneira do anterior no html, precisamente acima do estilo, o reset precisa ficar por cima de qualquer alteração de style. 

Um exemplo é quando vamos colocar uma nova película no nosso celular, antes de colocar a película, é preciso limpar a tela do celular para depois aplicar a película, se primeiro for feito em ordem contraria a película ficaria defeituosa. Então a limpeza seria o reset, e a película nova o css.

#