# 🍔 Make Your Burger

Uma aplicação para montagem de hambúrgueres personalizados, permitindo que o usuário escolha os ingredientes e envie o pedido. O projeto utiliza Vue.js 3 para o frontend e `json-server` para simular um backend.

## 📝 Observação

Este projeto foi desenvolvido como parte de um curso para aprimorar minhas habilidades em desenvolvimento web com Vue.js. O código foi digitado por mim, com base nas aulas, e não é uma cópia direta.

## 🚀 Tecnologias Utilizadas

-   **Vue.js 3 (Composition API):** Framework reativo para a construção da interface.
-   **Vue Router:** Para gerenciamento de rotas da aplicação.
-   **JSON-Server:** Simula uma API RESTful para o backend, utilizando um arquivo `db.json`.
-   **Gestão de Estado:** Implementação de fluxo de dados entre componentes para controle de status de pedidos em tempo real.

## ⚙️ Como Rodar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_REPOSITORIO>
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd make-your-burger
    ```
3.  **Instale as dependências:**
    ```bash
    npm install
    ```
4.  **Inicie o servidor de desenvolvimento do frontend:**
    ```bash
    npm run serve
    ```
5.  **Em um novo terminal, inicie o backend com `json-server`:**
    ```bash
    npm run backend
    ```
6.  **Acesse a aplicação em seu navegador, geralmente em `http://localhost:8080`**.

## 📦 Build para Produção

Para compilar e minificar os arquivos para produção, rode o seguinte comando:

```bash
npm run build
```

## 🔧 Scripts Disponíveis

-   `npm run serve`: Inicia o servidor de desenvolvimento.
-   `npm run build`: Gera a build de produção.
-   `npm run lint`: Executa o linter para análise de código.
-   `npm run backend`: Inicia o `json-server` para o backend fake.

## 📂 Estrutura do Projeto

```text
make-your-burger/
├── db/
│   └── db.json       # Banco de dados fake para o json-server
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   ├── components/
│   ├── router/
│   ├── stores/
│   └── views/
├── package.json
└── vue.config.js
```