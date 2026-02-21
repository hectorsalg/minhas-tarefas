# Minhas Tarefas

O **Minhas Tarefas** é uma aplicação web de gestão de tarefas (To-Do List) desenvolvida com **React**, **TypeScript** e **Redux**. A aplicação permite aos utilizadores organizar as suas tarefas diárias de forma eficiente, utilizando uma interface moderna e responsiva construída com **Styled Components**.

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias e bibliotecas:

- **React 18**: Biblioteca principal para a construção da interface.
- **TypeScript**: Adiciona tipagem estática ao JavaScript para maior segurança e produtividade.
- **Redux Toolkit**: Para a gestão de estado global da aplicação.
- **React Router DOM**: Para a navegação entre as páginas (Home e Cadastro).
- **Styled Components**: Para a estilização baseada em componentes utilizando CSS-in-JS.
- **Prettier & ESLint**: Para a padronização e qualidade do código.

## 📋 Funcionalidades

- Visualização de listas de tarefas.
- Filtragem de tarefas por estado ou prioridade.
- Criação de novas tarefas através de um formulário dedicado na rota `/novo`.
- Persistência de dados e gestão de estado centralizada com Redux.

## 🛠️ Instalação e Execução

Para executar este projeto localmente, siga os passos abaixo:

1. **Clone o repositório:**

```bash
git clone [url-do-repositorio]

```

2. **Instale as dependências:**

```bash
npm install

```

3. **Inicie o servidor de desenvolvimento:**

```bash
npm start

```

A aplicação será aberta no endereço [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000).

## 🏗️ Estrutura de Pastas Principais

- `src/pages`: Contém as páginas principais da aplicação, como `Home` e `Cadastro`.
- `src/store`: Configuração do estado global com Redux.
- `src/styles`: Ficheiros de estilização global e temas com Styled Components.
- `src/App.tsx`: Ponto de entrada da aplicação com a definição das rotas.

## 🌐 Web

- Link da [Vercel](minhas-tarefas-hectorsalg.vercel.app/)

## 📜 Scripts Disponíveis

No diretório do projeto, pode executar:

- `npm start`: Executa a aplicação em modo de desenvolvimento.
- `npm run build`: Cria a versão de produção na pasta `build`.
- `npm test`: Inicia o executor de testes.
- `npm run format`: Formata o código automaticamente utilizando o Prettier.
