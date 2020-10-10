# back_api_node

Api em Node.js

## Descrição

Api em Node.js para ser usado no back end de uma aplicação em Angular.

### Pré-requisito

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/edinilsonvida/back_api_node>

# Acesse a pasta do projeto no terminal/cmd
$ cd back_api_node

# Instale as dependências
$ npm install

# Mude a senha no arquivo db.config.js para a sua senha do MySql2

# Crie o banco de dados no MySql2

# Execute a aplicação 
$ npm start

# O servidor inciará na porta:3000 - acesse <http://localhost:3000>
```
### Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Body-Parser] (https://www.npmjs.com/package/body-parser)
- [Cors] (https://www.npmjs.com/package/cors/)
- [Express] (https://expressjs.com/)
- [MySql2] (https://www.npmjs.com/package/mysql2/)
- [Sequelize] (https://sequelize.org/)
- [Nodemon] (https://www.npmjs.com/package/nodemon)

### Rotas
- POST [Realizar postagem] http://localhost:3000/api/posts
- GET [Visualizar todas as postagens] http://localhost:3000/api/posts
- GET [Visualizar postagem específica pelo id] http://localhost:3000/api/posts/:id
- PUT [Atualizar uma postagem específico] http://localhost:3000/api/posts/:id
- GET [Visualizar postagem baseado no título] http://localhost:3000/api/posts?title=nome
- GET [Visualizar postagem true] http://localhost:3000/api/posts/published
- DELETE [Deletar um post por id] http://localhost:3000/api/posts/:id
- DELETE [Deletar todos os posts] http://localhost:3000/api/posts/