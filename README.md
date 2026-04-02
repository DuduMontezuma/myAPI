# myAPI

API de estudos feita com Laravel para gerenciamento de bandas.

## 🚀 Funcionalidades

- Listar todas as bandas
- Buscar banda por ID
- Buscar bandas por gênero
- Cadastrar banda via POST

---

## 📡 Rotas

### GET /api/bands
Lista todas as bandas.

### GET /api/bands/{id}
Retorna uma banda pelo ID.

### GET /api/bands/gender/{gender}
Retorna bandas por gênero.

### POST /api/bands/store
Cadastra uma nova banda.

### Exemplo de JSON:
```json
{
  "id": 6,
  "name": "Iron Maiden",
  "gender": "heavy metal"
}
