Calculadora de Datas


Este é um projeto de calculadora de datas que permite calcular a distância entre uma data digitada e a data atual. A distância pode ser exibida em segundos, minutos, horas ou dias, conforme escolhido pelo usuário.

Tecnologias utilizadas
HTML
CSS
JavaScript
Moment.js (biblioteca JavaScript para manipulação de datas)

Funcionamento do Código
O código JavaScript possui duas funções principais:
calculateDateDifference(): Esta função é acionada quando o botão de cálculo é clicado. Ela recupera a data digitada pelo usuário, verifica se é válida e realiza o cálculo da diferença em relação à data atual. O resultado é exibido na página conforme a unidade de medida selecionada.
formatInputDate(event): Esta função é acionada toda vez que uma tecla é pressionada no campo de entrada de data. Ela formata automaticamente a entrada do usuário, adicionando as barras ("/") nos lugares corretos para que a data seja exibida no formato "DD/MM/YYYY".

Instruções de Uso
Digite uma data válida no campo "Digite uma data (Formato DD/MM/YYYY)".
Escolha a unidade de medida desejada no menu suspenso "Escolha como gostaria de exibir a distância entre as datas".
Clique no botão "Calcular" para calcular a diferença entre a data escolhida e a data atual.
O resultado será exibido abaixo do botão de cálculo.

Observações
Se a data digitada for inválida ou o campo estiver vazio, será exibido um alerta solicitando ao usuário que insira uma data válida.
Certifique-se de digitar a data no formato "DD/MM/YYYY" para obter resultados corretos.
Certifique-se de incluir a biblioteca Moment.js (moment.min.js) no mesmo diretório do arquivo HTML para que o código funcione corretamente.

Personalização
É possível personalizar o estilo do projeto modificando as propriedades CSS no arquivo timeDistance.css.
Para adicionar mais opções de unidade de medida, basta adicionar novos elementos <option> ao elemento <select> com os valores desejados.
  
Contribuição
Contribuições são bem-vindas! Se você tiver sugestões, melhorias ou correções para o projeto, fique à vontade para fazer um fork do repositório, realizar as modificações desejadas e enviar um pull request.
