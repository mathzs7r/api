# api — CRUD de Clientes (Express + JSON)

API REST em **Node.js + Express** que persiste clientes em arquivo `bd.json`.

## Rotas

| Método | Rota | Descrição |
|--------|------|-----------|
| GET | `/ola` | Health check |
| POST | `/cliente` | Cadastrar cliente (body JSON) |
| GET | `/cliente` | Listar todos |
| GET | `/cliente/:cpf` | Buscar por CPF |
| PUT | `/cliente/:cpf` | Atualizar por CPF |
| DELETE | `/cliente/:cpf` | Remover por CPF |

## Arquivos

- `index.js` — servidor Express
- `bd.json` — “banco” em arquivo

## Como rodar

```bash
npm install express   # se ainda não tiver
node index.js
# API em http://localhost:3000
```

## Autor

[mathzs7r](https://github.com/mathzs7r)
