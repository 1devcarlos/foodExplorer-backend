<h1 align="center">
    <a href="#"> Food Explorer - API Restful</a>
</h1>

<p align="center">

  <img alt="Static Badge" src="https://img.shields.io/badge/status-concluido-green">
	
  <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=49AA26&labelColor=000000" alt="welcome!" />
	
  <img src="https://img.shields.io/github/languages/count/Dev-Shinsei/foodExplorer-backend" alt="languages" />
	
  <img alt="Github" src="https://img.shields.io/github/license/1devcarlos/foodExplorer-backend" />

</p>


<p align="center">
 <a href="#-sobre">Sobre</a> •
 <a href="#-tecnologias">Tecnologias</a> •
</p>

---

## 💻 Sobre

API Restful - O Food Explorer é uma aplicação de menu digital para um restaurante fictício conhecido como foodExplorer.

Neste desafio, foram abordados os seguintes tópicos:

- Express;
- Rotas e métodos http;
- Parâmetros;
- Controllers;
- Middleware;
- SQL;
- Migrations;
- Query Builder;
- Knex;
- JWT;
- Armazenamento em disco;
- Cors;

---

## ⚙️ Funcionalidades

- [x] Projeto estruturado, com boa organização de pastas e divisão de componentes no frontend.
- [x] Arquivo README.md com instruções sobre como executar o projeto em ambiente de desenvolvimento.
- [x] Os usuários devem se autenticar para entrar na aplicação por meio da tela de login, aplicando o que foi aprendido nas aulas de autenticação JWT. A autenticação deve ser validada com uma senha.
- [x] O administrador fará upload de imagens para registrar os pratos.
- [x] Por fim, faça o deploy da aplicação.
- [x] Dê nomes significativos às suas funções e variáveis: trabalhe um pouco com os conceitos de Clean Code.
- [x] Os dados de admin, restaurante e usuários serão armazenados em um banco de dados.
- [x] Possibilidade de pesquisa por nome do prato, ingredientes ou prato favorito.
- [x] É essencial que a interface consuma sua própria API.
- [x] Interessante tornar a aplicação responsiva: utilize o conceito de Mobile First aprendido nas aulas.
- [x] Você decide onde aplicar animações, transições e transformações.
- [x] Atenda ao modelo proposto no Figma e contenha elementos indicativos de ação e estado.

Opcionais

- [x] O usuário pode adicionar itens ao carrinho clicando no botão "Adicionar". A quantidade é controlada pelos botões "-" e "+".
- [x] Ao clicar no botão "Meu Pedido", o usuário será redirecionado para uma tela onde poderá ver seu pedido, a soma total e os métodos de pagamento.
- [x] O usuário poderá excluir um prato do carrinho e o valor total do pedido será atualizado automaticamente.
- [x] O usuário pode marcar um prato como favorito, basta clicar

no ícone de coração ao lado de cada prato.
- [x] O administrador poderá visualizar e controlar o status de cada pedido por meio de um campo de seleção. Os pedidos serão exibidos em uma tabela ao clicar em "Pedidos".

---

## 🚀 Como Funciona

Este projeto está dividido em três partes:

1. Backend (pasta foodExplorer-backend)
2. Frontend (pasta foodExplorer-frontend)

### Pré-requisitos

Antes de começar, você precisará ter as seguintes ferramentas instaladas em sua máquina: [Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). Além disso, é recomendável ter um editor de código como o [VSCode](https://code.visualstudio.com/) para trabalhar com o código.

#### 🎲 Executando o Servidor (Backend)

```bash
# Clone este repositório
$ git clone git@github.com:1devcarlos/foodExplorer-backend.git

# Acesse a pasta do projeto no terminal
$ cd foodExplorer-backend

# Instale as dependências
$ npm install

# Execute a migração e o seed
$ npm migrate
$ npm seed

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# Login do administrador
$ email: admin@email.com
$ password: 33283982

# O servidor será iniciado na porta: 3333 - acesse http://localhost:3333
```

---

## 🛠 Tecnologias

As seguintes ferramentas foram utilizadas na construção deste projeto:

- [Express](https://expressjs.com/)
- [CORS](https://expressjs.com/en/resources/middleware/cors.html)
- [KnexJS](http://knexjs.org/)
- [SQLite](https://github.com/mapbox/node-sqlite3)
- [Node](https://github.com/node)
- [Multer](https://github.com/expressjs/multer)

---

## 💻 **Projeto**

## A aplicação que desenvolveremos é um menu digital para um restaurante fictício conhecido como Food Explorer.


Feito com ❤️ por Carlos Gomes 👋🏽 [Entre em Contato!](https://www.linkedin.com/in/1devcarlos/)
