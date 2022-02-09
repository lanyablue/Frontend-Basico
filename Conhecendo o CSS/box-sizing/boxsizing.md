##

Já vimos um pouco sobre tamanho e espaçamento, mas os navegadores calculam de formas diferentes o tamanho de um elemento, e podemos inclusive dizer a ele qual é a forma que queremos utilizar, para isso existe a propriedade box-sizing, os principais valores para essa propriedade são box-content e border-box.

Vamos imaginar um elemento, só o conteúdo dele e uma borda, o que existe para fora da borda é o margin, o que existe para dentro da borda é o padding, tendo isso bem claro em mente conseguimos entender de maneira mais clara os valores da propriedade box-sizing. A pergunta que podemos fazer a partir disso é, como eu calculo o width e o height? É para isso que a propriedade box-sizing existe, para saber como se calcula esse width e esse height.

Começando pela propriedade content-box, ela já é o valor default, todos os elementos já nascem com o box-sizing contente-box, para calcular as dimensões de um elemento, consideramos apenas o conteúdo, o content. Veja o exemplo1.

O outro é border-box, ou seja, eu irei contar até a borda, então meu width será o conteúdo + padding + border. Agora vamos a um exemplo de como contar isso, temos um elemento de width e height de 100px (exemplo2), um padding de 30px, e irá começar um box-sizing content-box, quando usamos um box-sizing content-box o meu width e meu height representam meu conteúdo, e o final vai somando, então no final ele tem 160px e o conteúdo tem 100px.

Se trocarmos o box-sizing por border-box (exemplo3), o meu final terá 100px, pois o border-box considera o conteúdo  + padding + borda, só que nesse exemplo não temos borda, então ele considera que o conteúdo mais o padding é 100px. Só que existe um padding de 30px, portanto o conteúdo diminui para 70px, porque border-box o total width representa conteúdo + padding + borda e isso será 100px, então é preciso fazer um cálculo para saber quando que vale o conteúdo.

Essas coisas não ficam tão claras no código, nem mesmo quando visualizamos na tela, pois nem fazendo as contas fica claro como funciona, e as vezes não conseguimos ter a noção de quantos pixels tem o elemento e muito menos os espaçamentos, para isso existem ferramentas nos navegadores para ajudar a visualizar as coisas de uma forma mais clara. O nome dessa ferramenta é developetools, usada no google chrome, mas também existe em diversos outros navegadores.

Geralmente quando construímos uma página, queremos que todos os elementos sejam do tipo border-box, para ter um controle um pouco maior sobre o que está sendo montado, então colocamos borde-box em todos os elementos, é uma prática bem comum. Para adicionar ao css basta criar um seletor * e ditar seu box-sizing para border-box.

##