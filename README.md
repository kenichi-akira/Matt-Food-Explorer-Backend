# Matt-Food-Explorer-Backend
 Projeto food explorer: Backend do desafio final da trilha Explorer da Rocketseat. 


<h1 align="center" style="text-align: center;">
  Food Explorer
</h1>

> Cardápio digital para um restaurante fictício

<p align="center">
  <a href="#project">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#structure">Estrutura</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#features">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Utilização</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#env-variables">Variáveis de Ambiente</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tests">Testes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<h2 id="project">📁 Projeto</h2>

O projeto Food Explorer é o desafio final da trilha Explorer/Fullstack da Rocketseat. Ele consiste em uma aplicação de cardápio digital para um restaurante fictício, permitindo a visualização e gestão de pedidos tanto para clientes quanto para administradores.

Este é o repositório do backend da aplicação. O front-end, responsável pela interface do usuário, está disponível [aqui](https://github.com/placeholder/frontend-link).

<h2 id="structure">📌 Estrutura</h2>

A estrutura do banco de dados inclui as seguintes tabelas:

- Usuários
- Pratos
- Ingredientes dos pratos
- Favoritos
- Carrinhos
- Itens dos carrinhos
- Pedidos
- Itens dos pedidos

<h2 id="features">✨ Funcionalidades</h2>

A aplicação possui as seguintes funcionalidades:

### Funcionalidades Gerais
- Cadastro de usuário no banco de dados
- Autenticação de usuários com login
- Visualização de pratos
- Busca de pratos pelo nome e por ingredientes

### Funcionalidades Exclusivas para Clientes
- Favoritar pratos e visualizar a lista de pratos favoritos
- Visualizar o total do pedido com valores detalhados, excluir produtos do pedido e criar uma ordem de pedido

### Funcionalidades Exclusivas para Administradores
- Criar, editar e excluir pratos
- Alterar o status dos pedidos (ex.: Em andamento, Concluído)

<h2 id="technologies">💻 Tecnologias</h2>

O projeto foi desenvolvido com as seguintes tecnologias:

- Node.js
- JavaScript
- Bcrypt.js
- CORS
- Dotenv
- Express.js
- express-async-errors
- JSON Web Token
- Knex.js
- Multer
- PM2
- SQLite
- Jest para testes automatizados

<h2 id="usage">💡 Utilização</h2>

O back-end do projeto está hospedado no endereço https://placeholder-backend-link.com. 

⚠️ **Importante**: Este projeto utiliza uma hospedagem gratuita para o back-end, portanto, pode haver atrasos no tempo de resposta do servidor.

Você também pode executá-lo em sua máquina local. Certifique-se de ter o `Node.js` e o `npm` instalados antes de prosseguir com as etapas abaixo:

1. Clone o projeto:

```bash
$ git clone https://github.com/placeholder/backend-repo-link.git

    Acesse a pasta do projeto:

$ cd diretorio-do-projeto

    Instale as dependências:

$ npm install

    Execute as migrações do banco de dados:

$ npm run migrate

    Inicie o servidor:

$ npm start

⚠️ Importante: Crie um arquivo .env de acordo com o arquivo .env.example e preencha os campos AUTH_SECRET e PORT com as informações adequadas.
<h2 id="env-variables">🔐 Variáveis de Ambiente</h2>

O projeto usa variáveis de ambiente definidas no arquivo .env. As principais variáveis são:

    AUTH_SECRET: utilizada para armazenar o segredo do token JWT.
    PORT: define a porta na qual o projeto será executado.

<h2 id="tests">🏹 Testes</h2>

Para rodar os testes da aplicação, feitos com Jest, use o seguinte comando no terminal, dentro do diretório do projeto:

npm test

Os testes serão executados, e o resultado será exibido no terminal.
<h2 id="Insomnia">📁 Requisições via Insomnia</h2>

O repositório inclui o arquivo Insomnia_Requests_FoodExplorer.json, que pode ser importado no Insomnia. Isso permite testar todas as requisições da aplicação diretamente no Insomnia.
<h2 id="license">📝 Licença</h2>

Este projeto está sob a licença MIT.

Feito com 💜 por Matthews Barcellos 👋🏾
