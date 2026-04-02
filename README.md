# myAPI

API de estudos desenvolvida com Laravel para gerenciamento de bandas.

---

## 🚀 Funcionalidades

- Listar todas as bandas
- Buscar banda por ID
- Buscar bandas por gênero
- Cadastrar nova banda via POST

---

## 📡 Rotas

### GET /api/bands
Lista todas as bandas.

### GET /api/bands/{id}
Retorna uma banda pelo ID.

### GET /api/bands/gender/{gender}
Retorna bandas filtradas por gênero.

### POST /api/bands/store
Cadastra uma nova banda.

---

## 📦 Exemplo de JSON para POST

```json
{
  "id": 6,
  "name": "Iron Maiden",
  "gender": "heavy metal"
}
```

---

## ⚙️ Como rodar o projeto

```bash
composer install
copy .env.example .env
php artisan key:generate
php artisan serve
```

A aplicação ficará disponível em:

http://127.0.0.1:8000

---

## 🛠️ Tecnologias

- PHP
- Laravel
- Postman

---

## 👨‍💻 Autor

Dudu Montezuma
