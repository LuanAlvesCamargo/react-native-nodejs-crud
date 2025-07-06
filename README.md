# CRUD App - React Native + Node.js + MySQL

Este projeto é um exemplo completo de um aplicativo CRUD (Create, Read, Update, Delete) utilizando React Native no frontend mobile e Node.js + Express no backend, com persistência de dados em um banco MySQL.

> Desenvolvido com fins educacionais para reforçar conceitos de desenvolvimento fullstack, integração de APIs REST e comunicação entre front e backend.

## Tecnologias Utilizadas

### Backend

- Node.js
- Express.js
- MySQL
- Nodemon (ambiente de desenvolvimento)
- Body-parser
- Cors

### Frontend

- React Native
- Expo Go
- Axios

## Como Executar o Projeto

### 1. Backend (Node.js + MySQL)

```bash
cd backend
npm install
```

- Crie um banco de dados MySQL com o nome `crud_db` (ou altere o nome no arquivo `db.js`)
- Importe o arquivo `node.sql` para criar a estrutura da tabela `alunos`
- Inicie o servidor com:

```bash
npm start
```

A API estará disponível em: http://localhost:3000

### Endpoints da API

- GET /alunos - Lista todos os alunos
- POST /alunos - Cadastra um novo aluno
- PUT /alunos/:id - Atualiza os dados de um aluno
- DELETE /alunos/:id - Remove um aluno

### 2. Frontend (React Native)

```bash
cd frontend
npm install
npx expo start
```

- Use o aplicativo Expo Go no seu celular para escanear o QR Code gerado e visualizar o app.

## Principais Aprendizados

- Integração de React Native com uma API REST
- Manipulação de dados com Axios
- Boas práticas com Node.js e Express
- Organização de rotas, controllers e estrutura modular no backend
- Comunicação eficiente entre frontend e backend via HTTP

## Ferramentas de Apoio

- Node.js
- XAMPP ou outro ambiente MySQL
- Postman
- Expo Go
