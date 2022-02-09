##

Border: 
Agora que já temos o tamanho definido, seria interessante conseguirmos marcar o nosso bloco, adicionar uma borda ao nosso retângulo. Para isso existe a propriedade border, quando pensamos em uma borda podemos definir três valores: a espessura, o estilo, e a cor. Isso divide os valores da borda em: borda widht, borda style, borda color.

Na borda width, são usadas as unidades de medidas que já vimos, e ele define a espessura. O border color também já aprendemos com as cores, ou os hexadecimais. 

O modelo style existem diversos tipos de valores, os mais usados são: solid, dashed e o none, veja outros exemplos em borders.png. Para definirmos uma borda, usamos da seguinte forma: border-color: black, por exemplo, borda-width:5px, border-style: solid e entre outros citados anteriormente. Podemos utilizar essas propriedades separadamente, ou podemos usá-las todas juntas na propriedade border, a sequência fica:

##
border: border-width border-style border-color;
border: 1px, solid, #fff 
##

Como o retângulo tem quatro lados, podemos definir a borda de cada um desses lados, no caso de border definimos que todos os lados terão esta propriedade. E se quisermos definir cada borda de um jeito diferente? Utilizaremos o border-top para a borda de cima, border-bottom para a borda de baixo, border-right na borda da direita, e border-left na borda da esquerda. Veja o exemplo em borda_especifica. E assim utilizamos a mesma forma de definir os valores, então por exemplo border-bottom-5px, solid, #fff. Também podemos definir somente um dos estilos para uma delas, então supondo que queremos definir a espessura do border-top, então utilizaremos border-top-widht5px, e isso vale para outras propriedades também, o style e color.

##