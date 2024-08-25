<h1 align="center">Todo List</h1>

<p align='center'> 
    <img src="https://img.shields.io/badge/Node-4d524e?style=for-the-badge&logo=node.js"/>
    <img src="https://img.shields.io/badge/mongo-4d524e?style=for-the-badge&logo=mongodb"/>  
    <img src="https://img.shields.io/badge/express-4d524e?style=for-the-badge&logo=express"/>
</p>


Uma simples aplicação de Todo List construída com Node.js, Express e MongoDB. Esta aplicação permite que os usuários criem, leiam, atualizem e excluam tarefas, proporcionando uma maneira prática de gerenciar atividades diárias. **Este projeto é para fins acadêmicos e não possui um processo de build.**

## Funcionalidades

- Criar novas tarefas
- Visualizar todas as tarefas
- Excluir tarefas
- Marcar tarefas como concluídas

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript para construir aplicações do lado do servidor.
- **Express**: Framework web para Node.js que lida com roteamento e middleware.
- **MongoDB**: Banco de dados NoSQL para armazenar tarefas.
- **Mongoose**: Biblioteca ODM (Object Data Modeling) para MongoDB e Node.js.
- **EJS**: Motor de template para renderizar views em HTML.

## Instalação

1. Clone o repositório:
   git clone https://github.com/seunome/todo-list.git

2. Navegue até o diretório do projeto:
   cd todo-list

3. Instale as dependências:
   npm install

4. Configure seu banco de dados MongoDB. Você pode usar uma instância local do MongoDB ou um serviço em nuvem como o MongoDB Atlas. A conexão com o banco de dados é feita diretamente pelo arquivo `config/database.js`.

5. Inicie a aplicação:
   npm run dev

6. Abra seu navegador e acesse `http://localhost:3000` para acessar a aplicação.

## Uso

- Para criar uma nova tarefa, navegue até a página "Nova Tarefa" e preencha o formulário.
- Você pode visualizar todas as tarefas na página principal.
- Cada tarefa pode ser editada ou excluída conforme necessário.
- Marque tarefas como concluídas marcando a caixa de seleção ao lado de cada tarefa.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.