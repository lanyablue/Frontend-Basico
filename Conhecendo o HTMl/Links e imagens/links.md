##

Falando de uma visão macro de uma página, sobre cada um dos elementos que podemos colocar em cada “pedaço” da página, podemos fazer links, que é a base da web, linkar uma pagina uma na outra, gerar mais conteúdo e organizar toda essa rede de informação.

No html temo a tag (<a>) que define hiperlink, esta tag precisa sempre saber o destino do link, para onde irá ao clicar nele, toda essa informação colocamos no atributo href. Por exemplo, ao clicarmos no texto google, que esta marcado com a tag a, iremos para a página do google (www.google.com.br).

Supondo que temos um texto que tenha referencias em três partes, a primeira delas a nome das empresas, na segunda página com portifólio das palestras, e por último na palavra e-mail o link do e-mail de contato. No primeiro caso queremos listar as empresas, que são links externos, logo basta colocar como valor do href o link da empresa, esse tipo de link é chamado de link ABSOLUTO, pois você está passando o link por inteiro com http://www e tudo mais. No segundo caso, teremos que linkar para uma página do portifólio das palestras, no caso não é uma pagina externa, e sim uma página do seu próprio site, basta apenas colocar como href o nome do arquivo, por exemplo (palestras.html). O que acontece quando colocamos apenas o nome do arquivo? O navegador pega o site que você está no momento e troca e o final dele, isso é chamado de link relativo, a dica para saber se o link é absoluto ou relativo é só olhar se ele começa com http. E no último caso queremos linkar um endereço de e-mail, para isso colocamos o valor do href com mailto:email@gmail.com.

Veja o exemplo pratico em Iniciando o projeto/index.html

##

Para colocar uma imagem na página utilizaremos a tag img, com o atributo src. O atributo src funciona da mesma forma que o href dos links, e existem os endereços relativos e absolutos neste atributo também. É obrigatório o uso do atributo alt com o texto descritivo da imagem ainda dentro da tag img, caso a imagem não carregue por algum motivo, o texto descritivo aparecerá no lugar indicando sobre o que seria aquela imagem. E outro aspecto importante é que precisamos nos preocupar em fazer páginas web para pessoas com deficiência, utilizando a acessibilidade, pois essas pessoas utilizarão softwares de leitura de tela para navegarem, e através da descrição do alt, a pessoa é capaz de “ler” a imagem.

##