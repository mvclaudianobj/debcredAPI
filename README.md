# API DebCred
API para transações débito & crédito

## Descrição

A API oferece os seguintes endpoints:
- Criar e editar a conta do usuário
- Criar transações de Débito e  Crédito
- Visualizar as transações do usuário

## Diagramas

![](https://github.com/mvclaudianobj/debcredAPI/blob/main/img/1.png)

![](https://github.com/mvclaudianobj/debcredAPI/blob/main/img/2.png)

## Tecnologias
- Node.js v10+
- Express
- Swagger tools
- Sequelize
- Sucrase
- Winston (Log)
- JWT
- PostgresSQL
- Jest
- SQLite

## Instruções de Instalação
- Clone esse repositorio
- instale o nodeJS, preferencialmente v12.22, utilizado nos testes locais
- execute a instalação com: npm install

## Instruções de Execução
- Crie um arquivo .env dentro do diretório do projeto com os parametros necessários, conforme exemplo env.example
- Dentro do diretório do projeto execute: npm start
- Para executar em modo daemon instale o forever: 'npm install -g forever' e execute: 'forever start -c "npm start" ./'

### Acessando a documentação da API
O projeto foi escrito usando a documentação interativa do swagger. Para acessar, execute a aplicação acesse: https://debcredapi.devsolutions.info/docs/

## License

This project is under the MIT license. See the [LICENSE](https://github.com/mvclaudianobj/debcredAPI/blob/main/LICENSE) for more information.

---

