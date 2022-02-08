##

Para ler o CSS de uma maneira mais fácil, começamos da direita para a esquerda,  que no caso do exemplo o seletor mais a direito é um p que vem logo antes das chaves, logo olharemos primeiro para esse seletor antes das chaves, pois é nesse elemento que será aplicado o estilo, todo o resto dos seletores a esquerda são qualificadores, deixam o seletor mais específico. 

No nosso exemplo da batalha naval, que faz a fonte ficar com a cor azul, ele possui dois tipos de seletores, ele possui a classe, que é a .batalha-naval, e o seletor de tipo que é o p, referenciando uma tag. Sempre que separar um espaço significa que entraremos um nível, ou seja, que está dentro. Neste exemplo pegamos todos os p que são filhos de .batalha-naval

##

No segundo exemplo, é quase a mesma coisa com a exceção do navio, percebemos que não temos um espaço entre o seletor do tipo p com a classe navio, no css os espaços ou a falta deles nos seletores muda totalmente o seletor final, quando não temos o espaço, selecionamos a classe daquele elemento específico, ou seja, no exemplo selecionamos todas as classes navio que também são parágrafos e que são filhos de .batalha-naval
Ou seja, sempre que tivermos um espaço, entramos um nível a mais no elemento, ou seja, um elemento é filho do outro, quando não tivermos o espaço a classe pertence ao elemento que está junto

##