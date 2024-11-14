# Matt-Food-Explorer-Backend
 Projeto food explorer: Backend do desafio final da trilha Explorer da Rocketseat. 


<h1 align="center" style="text-align: center;">
  Food Explorer
</h1>

> O que é: Um cardápio digital para um restaurante fictício

<p align="center">
  <a href="#project">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#structure">Estrutura</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#features">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#usage">Utilização</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#env-variables">Variáveis de Ambiente</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<h2 id="project">📁 Projeto</h2>

O projeto Food Explorer é o desafio final da trilha Explorer/Fullstack da Rocketseat. Ele consiste em uma aplicação de cardápio digital para um restaurante fictício, permitindo a visualização e gestão de pedidos tanto para clientes quanto para administradores.

Este é o repositório do backend da aplicação. O front-end, responsável pela interface do usuário, está disponível [aqui](https://github.com/kenichi-akira/Matt-Food-Explorer-Frontend).

<h2 id="structure">📌 Estrutura</h2>

A estrutura do banco de dados inclui as seguintes tabelas:

- Pratos  
- Ingredientes  
- Migrações (knex_migrations)  
- Controle de Migrações (knex_migrations_lock)  
- Pedidos  
- Itens dos Pedidos  
- Sequência do SQLite (sqlite_sequence)  
- Usuários

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

O projeto tem como dependências:

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

<h2 id="usage">💡 Utilização</h2>

O back-end do projeto está hospedado no endereço [(https://matt-food-explorer-backend.onrender.com)](https://matt-food-explorer-backend.onrender.com)

⚠️ **Importante**: Este projeto utiliza o Render, que é hospedagem gratuita para o back-end, enquanto o Frontend se encontra hospedado no Netlify. 
Portanto, pode haver atrasos no tempo de resposta do servidor caso esteja se tentando conectar no backend. O que pode demorar até mais de um minuto.

Você também pode executá-lo em sua máquina local. Certifique-se de ter o `Node.js` e o `npm` instalados antes de prosseguir com as etapas abaixo:


1. Clone o projeto:

   ```bash
   $ git clone https://github.com/kenichi-akira/Matt-Food-Explorer-Backend/tree/main
   
       Acesse a pasta do projeto:
   
   $ cd diretorio-do-projeto
   
       Instale as dependências:
   
   $ npm install
   
       Execute as migrações do banco de dados:
   
   $ npm run migrate
   
       Inicie o servidor:
   
   $ npm start

   O terminal mostrará o endereço local em que a aplicação está rodando. Para acessá-la, basta inserir esse endereço em seu navegador.

⚠️ Importante: Crie um arquivo .env de acordo com o arquivo .env.example e preencha os campos AUTH_SECRET e PORT com as informações adequadas.

<h2 id="env-variables">🔐 Variáveis de Ambiente</h2>

O projeto usa variáveis de ambiente definidas no arquivo .env. As principais variáveis são:

    AUTH_SECRET: utilizada para armazenar o segredo do token JWT.
    PORT: define a porta na qual o projeto será executado.

<h2 id="license">📝 Licença</h2>

Este projeto está sob a licença MIT.

Feito por Matthews Barcellos.
