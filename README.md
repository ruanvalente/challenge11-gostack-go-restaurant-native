<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h2 align="center">
  Desafio 11: GoRestaurant Mobile
</h2>

## 🚀 Sobre o desafio

Nesse desafio, foi desenvolvido mais uma aplicação, a GoRestaurant. Agora na sua versão mobile ! Colocando em prática o que aprendi até agora dentro do **`React Native`** junto com **`TypeScript`**, praticando o conceito de consumo de uma API rest usando o **`JSON Server`** para simular uma API rest fake.


## 🔨 Tecnologias:

- [ReactJs][reactjs]
- [React Native](https://reactnative.dev/)
- [TypeScript][typescript]
- [Polished](https://github.com/styled-components/polished)
- [Styled Components](https://styled-components.com/)
- [Axios][axios]
- [JSON Server](https://www.npmjs.com/package/json-server)

## 🚀 Como rodar este projeto

Para clonar e executar este aplicativo, você precisará de [Git](https://git-scm.com), [NodeJs][nodejs] Instalado em seu computador.

### 🌀 Clonando o repositório

```bash
# Clone este repositório
$ git clone git@github.com:ruanvalente/challenge11-gostack-go-restaurant-native.git

# Acesse a pasta do projeto no terminal/cmd
$ cd challenge11-gostack-go-restaurant-native
```

### 🧭 Rodando a aplicação web

```bash
# Instale as dependências
$ yarn

# Execute a fake api
$ yarn json-server server.json -p 3333

# Execute no seu terminal 
$ yarn start

# Execute a Aplicação no Android ou ios
$ yarn react-native run-android 
$ yarn react-native run-ios

# Execute o teste da Aplicação
$ yarn test

# O frontend da aplicação inciará na porta:3000 - acesse: 

# http://localhost:3000

# O backend (fake) da aplicação inciará na porta:3333 - acesse:

# Resources:
# http://localhost:3333/foods

# Home
# http://localhost:3333

```

## 🛠 Funcionalidades da aplicação

- **`Listar os pratos de comida da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem, com o campo `name`, `value` e  `description` de todos os pratos de comida que estão cadastrados na sua API.

- **`Listar as categorias da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem, com o campo `title` e `image_url` de todas as categorias que estão cadastrados na sua API.

- **`Filtrar pratos de comida por busca ou por categorias`**: Em sua página Dashboard permitir que o input de pesquisa e os botões de categoria façam uma busca na API de acordo com o que estiver selecionado ou escrito no input.

- **`Listar os pedidos da sua API`**: Sua página `Orders` deve ser capaz de exibir uma listagem, com o campo as informações do produto pedido, com `name` e `description` de todos os pedidos que estão cadastrados na sua API.

- **`Listar os pratos favoritos da sua API`**: Sua página `Favorites` deve ser capaz de exibir uma listagem, com o campo as informações do produto favorito, com `name` e `description` de todos os pedidos que estão cadastrados na sua API.

- **`Realizar um pedido`**: Na sua página `Dashboard`, ao clicar em um item, você deve redirecionar o usuário para a página `FoodDetails`, onde será possível realizar um novo pedido, podendo controlar a quantidade desse item pedido, ou adicionar ingredientes extras. Todo o valor deve ser calculado de acordo com a quantidade pedida.


## 🤔 Como contribuir para o projeto

- Faça um **fork** do projeto;
- Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
- Salve as alterações e crie uma mensagem de commit contando o que você fez:`git commit -m "feature: My new feature"`
- Envie as suas alterações: `git push origin my-feature`

> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)

## 📝 Licença

Este projeto esta sobe a licença MIT. Veja a [LICENÇA][license] para saber mais.

<p align="center">
Feito com ❤️ por Ruan Valente 👋🏽 
</p>

[nodejs]: https://nodejs.org/
[express]: https://expressjs.com/
[uuidv4]: https://www.npmjs.com/package/uuidv4
[nodemon]: https://www.npmjs.com/package/nodemon
[rs]: https://rocketseat.com.br
[license]: https://opensource.org/licenses/MIT
[postgres]: https://www.postgresql.org/
[multer]: https://www.npmjs.com/package/multer
[reactjs]: https://reactjs.org/
[axios]: https://www.npmjs.com/package/axios
[babel]: https://babeljs.io/
[webpack]: https://webpack.js.org/
[rs]: https://rocketseat.com.br
[license]: https://opensource.org/licenses/MIT
[typescript]: https://www.typescriptlang.org/
