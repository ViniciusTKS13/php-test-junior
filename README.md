# Php Teste(Junior)
Desenvolva uma aplicação utilizando o framework Laravel, a aplicação deverá ter duas seções, sendo elas:
- Área logada:
  - CRUD de Notícias, cada notícia deverá conter: id, imagem, título, texto, categoria, data de criação;
  - CRUD de Categorias, cada categoria deverá conter: id, nome e categoria pai(opcional);

- Área deslogada:
  - Página inicial: com as 10 notícias mais recentes, exibindo a imagem, o título, nome da categoria, data da notícia e apenas os 100 primeiros caracteres do texto da notícia e colocar reticências caso o texto seja maior. Caso ocorra o click na notícia ir para uma página onde exiba ela completa.
  - Página da notícia: exibir a imagem, o título, nome da categoria, data da notícia, o texto completo e embaixo as 10 notícias mais recentes da mesma categoria da mesma forma que é exibido as notícias na página inicial.
  - Página geral de notícias: exibir todas as notícias podendo ordenar por título ou data, de forma ascendente ou descendente, filtrar por categoria ou por parte do título ou pelo título completo e um campo para limitar a quantidade de notícias a serem exibidas, com paginação.
 
O usuário logado deverá conseguir acessar a área deslogada, mas o usuário não logado não poderá ter acesso a área logada.

Bônus: 
- Botão “Ver Mais” na página inicial para carregar mais 10 notícias sem atualizar a página;
- Realizar a busca na página geral de notícias sem atualizar a página;
- Utilização de migrations;
- Utilização de seeds para popular a tabela de notícias;
- Responsividade;
- Pode utilizar JQuery para os 2 primeiros itens, mas caso não utilize e faça com JavaScript puro é um grande ponto;
