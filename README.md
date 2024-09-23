# Projeto Web Mobile
 Projeto da turma WEBMOBILE <br/>
 Turma 02J

 Membros: <br/>
 Guilherme Miranda Bertinato da Rocha https://github.com/GBertinato  <br/>
 Débora Abreu https://github.com/DeborahAbreu  <br/>
 Jean Alex https://github.com/thucuru  <br/>
 Pedro Carvalho https://github.com/pedro068 <br/>

Este projeto consiste em uma página web simples e responsiva, construída utilizando HTML e CSS. O código foi estruturado para criar uma interface limpa, com elementos organizados de forma flexível graças ao uso do Flexbox.

No arquivo HTML, temos uma estrutura básica que inclui três seções principais: o cabeçalho (header), a seção principal (main) e o rodapé (footer). O cabeçalho e o rodapé possuem fundo colorido em um tom de roxo claro e o texto é centralizado. O conteúdo principal é composto por duas linhas de caixas (div com a classe box), cada uma contendo três caixas.

O CSS é responsável por definir o estilo e o layout da página. No início, as propriedades margin, padding, e box-sizing são resetadas no body para garantir uma base consistente, sem espaçamentos indesejados. Em seguida, o display: flex é aplicado no body, o que permite alinhar os elementos filhos (cabeçalho, conteúdo principal, e rodapé) em uma coluna, ocupando toda a altura da janela do navegador com a propriedade min-height: 100vh. A flexibilidade dessa abordagem garante que o conteúdo principal sempre ocupe todo o espaço disponível entre o cabeçalho e o rodapé, independentemente do tamanho da tela.

Dentro da seção principal, as caixas são organizadas utilizando display: flex e flex-wrap: wrap, permitindo que elas se ajustem automaticamente conforme o espaço disponível. Cada caixa tem uma largura calculada para ocupar um terço da linha (com um pequeno espaçamento entre elas) e uma altura fixa de 120px. A combinação de align-items: center e justify-content: center dentro das caixas garante que o conteúdo (o texto) seja sempre centralizado, tanto vertical quanto horizontalmente.

Além disso, o código inclui uma media query para ajustar o layout em telas menores. Quando a largura da tela é inferior a 768px, as caixas passam a ser exibidas em uma única coluna, ocupando toda a largura disponível, o que melhora a legibilidade e a usabilidade em dispositivos móveis.

O CSS também aplica uma sombra (box-shadow) às caixas, ao cabeçalho e ao rodapé, o que acrescenta uma sensação de profundidade e realça os elementos na página. As cores utilizadas seguem uma paleta consistente, com tons de roxo que harmonizam o visual geral da interface.

Esse código é um exemplo prático de como utilizar Flexbox para criar layouts responsivos de forma eficiente, mantendo uma estrutura simples e elegante. Ele pode ser facilmente adaptado ou expandido para projetos maiores ou mais complexos, conforme necessário.

 
 
