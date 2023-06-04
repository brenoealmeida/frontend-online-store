# Projeto Front-end - Mercado Livre

Este projeto é um front-end para uma plataforma de compras baseada na API do Mercado Livre. Ele permite aos usuários buscar, listar e comprar produtos, além de fornecer recursos adicionais como filtragem por categoria, visualização detalhada do produto, adição ao carrinho de compras e avaliações.

(Projeto realizado em grupo)

## Funcionalidades

A seguir estão listadas as principais funcionalidades implementadas no projeto:

1. **Módulo de acesso à API do Mercado Livre:** Implementação do módulo que permite a interação com a API do Mercado Livre para obter dados sobre produtos e categorias.

2. **Página de listagem de produtos vazia:** A página principal da plataforma exibe uma lista vazia de produtos. Os usuários podem buscar produtos, filtrar por categoria e adicionar itens ao carrinho de compras.

3. **Página do carrinho de compras:** Os usuários podem adicionar produtos ao carrinho de compras a partir da listagem de produtos. A página do carrinho de compras exibe os itens adicionados e permite a manipulação da quantidade de cada produto, bem como a exclusão de produtos do carrinho.

4. **Listagem de categorias de produtos disponíveis:** A tela principal exibe uma lista de categorias de produtos disponíveis. Essas categorias são obtidas por meio da API do Mercado Livre. A requisição para a API é feita apenas uma vez, após o carregamento da tela.

5. **Listagem de produtos buscados por termos:** Os usuários podem digitar termos de busca na tela principal e realizar uma busca por produtos. Os produtos retornados pela API do Mercado Livre são listados na tela, exibindo informações resumidas sobre cada um.

6. **Filtragem por categoria:** Os usuários podem selecionar uma categoria na tela principal e ver apenas os produtos dessa categoria. Ao clicar em uma das categorias listadas, a aplicação lista todos os produtos encontrados nessa categoria.

7. **Exibição detalhada de um produto:** Ao clicar em um produto na listagem, os usuários são redirecionados para uma página de detalhes desse produto. A página exibe informações detalhadas, como nome, imagem, preço e especificações técnicas. Também há um botão para adicionar o produto ao carrinho de compras.

8. **Adição de produtos ao carrinho a partir da listagem:** Os usuários podem adicionar produtos ao carrinho de compras diretamente da página principal, onde ocorre a listagem de produtos.

9. **Adição de produtos ao carrinho a partir da página de detalhes:** A partir da página de detalhes de um produto, os usuários podem adicionar o produto ao carrinho de compras.

10. **Visualização e manipulação da lista de produtos no carrinho:** A página do carrinho de compras exibe a lista de produtos adicionados, permitindo aos usuários aumentar, diminuir ou excluir produtos. Os produtos adicionados são armazenados no *local storage* e são renderizados ao entrar na página.

11. **Avaliação e comentário de um produto:** Na página de detalhes de um produto, os usuários podem adicionar avaliações sobre o produto. O formulário de avaliação inclui campos para e-mail, nota (entre 1 e 5) e comentários. O e-mail e a nota são obrigatórios, e o e-mail deve ser válido. As avaliações

## Tecnologias utilizadas

O projeto Trybe Futebol Clube foi desenvolvido utilizando as seguintes tecnologias:

- TypeScript
- Node.js
- Express.js
- Sequelize
- Docker
- Javascript

## Autores

Este projeto foi desenvolvido em grupo como parte do curso de Desenvolvimento Web da Trybe
[Breno Almeida](https://github.com/brenoealmeida)
