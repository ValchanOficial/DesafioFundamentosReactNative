# Rocketseat - Desafio: Fundamentos do React Native

## Sobre o desafio

Desenvolvimento da aplicação GoMarketplace.

## Funcionalidades da aplicação
- **Listar os produtos da fake API:** Na página Dashboard, deve ser capaz de exibir uma listagem através de uma tabela, com os campos title, image_url e price.

- **Adicionar itens ao carrinho:** Deve ser capaz de adicionar itens ao carrinho.

- **Exibir itens do carrinho:** Na página Cart, deve ser possível exibir todos os itens do carrinho, junto com a quantidade, valor único, valor subtotal dos itens e total de todos os items.

- **Aumentar quantidade de itens do carrinho:** Na página Cart, deve permitir que o usuário aumente a quantidade de itens do mesmo produto.

- **Diminuir quantidade de um item do carrinho:** Na página Cart, deve permitir que o usuário decremente a quantidade de itens do mesmo produto.

- **Exibir valor total dos itens no carrinho:** Tanto na página Dashboard, tanto na página Cart, deve exibir o valor total de todos os itens que estão no carrinho.


## Start

```js
    yarn install                          // instala dependências
    yarn json-server server.json -p 3333  // fake API
    yarn android                          // inicia aplicação android
    yarn ios                              // inicia aplicação ios em caso de Mac
    yarn test                             // executa os testes
```
