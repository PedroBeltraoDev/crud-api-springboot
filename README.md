# CRUD de Usuários com Spring Boot

API RESTful desenvolvida em **Java com Spring Boot**, utilizando **MySQL** como banco de dados e arquitetura baseada em camadas. Essa aplicação permite **cadastrar, listar, buscar, atualizar e deletar usuários**.

---

## 🚀 Tecnologias Utilizadas

- Java 17
- Spring Boot 3.5.3
- Spring Web
- Spring Data JPA
- MySQL
- Lombok
- Maven

---

## 🧱 Estrutura do Projeto

- `controllers/` → Endpoints da API (`UserController`)
- `entities/` → Classe de domínio (`User`)
- `repositories/` → Interface JPA + classe DTO (`UserRequest`)
- `resources/application.properties` → Configurações de banco de dados

---

## 📌 Funcionalidades

- ✅ Criar usuário (`POST /users`)
- ✅ Listar todos os usuários (`GET /users`)
- ✅ Buscar usuário por ID (`GET /users/get/{id}`)
- ✅ Atualizar usuário (`PUT /users/update/{id}`)
- ✅ Deletar usuário (`DELETE /users/delete/{id}`)

---

## 📦 Exemplo de Requisição

### ➕ Criar Usuário
```http
POST /users
Cria um novo usuário.
Body (JSON):
{
  "name": "Nome do Usuário",
  "email": "email@exemplo.com"
}

GET /users
Retorna todos os usuários cadastrados.

GET /users/get/{id}
Retorna um usuário específico pelo ID.

PUT /users/update/{id}
Atualiza um usuário pelo ID.
Body (JSON):
{
  "name": "Novo Nome",
  "email": "novoemail@exemplo.com"
}

DELETE /users/delete/{id}
Deleta um usuário pelo ID.
```
---

📫 **Contato:**  
[Pedro Beltrão]  
[LinkedIn](https://www.linkedin.com/in/pedro-beltrão123/) • [GitHub](https://github.com/PedroBeltraoDev) • pedrobeltraodev@gmail.com

