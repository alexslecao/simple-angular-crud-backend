# simple-angular-crud-backend
Sistema para registrar produtos. Como o foco do projeto foi no front-end, o backend está o mais simples possível.

## Preparando o Ambiente

### Banco de Dados
Banco de Dados: o banco será simulado com json server, um arquivo contendo o banco está no diretório ./db_json. O banco já está configurado e pronto para ser utilizado.

### Para executar o projeto
```sh
npm start
```

### Interface da API de exemplo e parâmetros (body)
Cadastro de produtos
| Método | Url                         | Parâmetros                                                                           |
| ------ | --------------------------- | ------------------------------------------------------------------------------------ |
| GET    | localhost:4001/products     | localhost:4001/localhost:4001/products?name_like=produto                             |
| GET    | localhost:4001/products/:id |                                                                                      |
| POST   | localhost:4001/products     | { "name": "Caneta", "price": 2.5}                                                    |
| PUT    | localhost:4001/products     | { "id": 1, "name": "Caneta", "price": 2.5 }                                          |
| DELETE | localhost:4001/products/:id |                                                                                      |
