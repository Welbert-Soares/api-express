# API Express

Esta é uma API construída com Express que implementa as operações CRUD.

## Endpoints

### GET /items

Retorna todos os itens.

### GET /items/:id

Retorna um item específico pelo ID.

### POST /items

Cria um novo item. Espera o seguinte formato JSON no corpo da requisição:

```json
{
    "name": "Nome do Item",
    "description": "Descrição do Item"
}
```

### PUT /items/:id

Atualiza um item específico pelo ID. Espera o seguinte formato JSON no corpo da requisição:

```json
{
    "name": "Novo Nome do Item",
    "description": "Nova Descrição do Item"
}
```

### DELETE /items/:id

Exclui um item específico pelo ID.

## Instalação

Para instalar e executar esta API, siga as seguintes etapas:

1. Clone o repositório
2. Instale as dependências com `npm install`
3. Inicie o servidor com `npm start`
