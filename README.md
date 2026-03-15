# 🐍 NLW Operator — Python Track

Projeto desenvolvido durante a **Next Level Week (NLW) Operator** da **Rocketseat**, na trilha **Python**.

Este projeto tem como objetivo praticar conceitos de **desenvolvimento backend com Python**, criação de APIs, organização de projetos e boas práticas de desenvolvimento.

---

## 📸 Preview

Aplicação: 

```md
![preview](./.github/preview.png)
```

---

## 🧠 Tecnologias Utilizadas

Este projeto foi desenvolvido com as seguintes tecnologias:

- **Python**
- **FastAPI**
- **SQLite**
- **SQLAlchemy**
- **Pydantic**
- **Uvicorn**

---

## 📂 Estrutura do Projeto

```bash
src/
 ├── database/
 │   ├── connection.py
 │   └── models.py
 │
 ├── routes/
 │   └── routes.py
 │
 ├── schemas/
 │   └── schemas.py
 │
 ├── services/
 │   └── services.py
 │
 └── main.py
```

A estrutura foi organizada separando responsabilidades em camadas:

- **routes** → rotas da API  
- **services** → regras de negócio  
- **schemas** → validação de dados  
- **database** → conexão e modelos do banco  

---

## ⚙️ Como rodar o projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/CamilleGFAlmeida/nlw-operator-2026-python.git
```

### 2️⃣ Acesse a pasta do projeto

```bash
cd nlw-operator-2026-python
```

### 3️⃣ Crie um ambiente virtual

```bash
python -m venv venv
```

### 4️⃣ Ative o ambiente virtual

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

### 5️⃣ Instale as dependências

```bash
pip install -r requirements.txt
```

### 6️⃣ Rode o servidor

```bash
uvicorn src.main:app --reload
```

O servidor iniciará em:

```
http://127.0.0.1:8000
```

---

## 📚 Documentação automática da API

Uma das vantagens do **FastAPI** é a geração automática de documentação.

Após rodar o projeto, acesse:

**Swagger UI**

```
http://127.0.0.1:8000/docs
```

**Redoc**

```
http://127.0.0.1:8000/redoc
```

---

## 💡 Conceitos aplicados

Durante o desenvolvimento foram praticados conceitos importantes como:

- Criação de **APIs REST com FastAPI**
- Estruturação de projetos backend
- Validação de dados com **Pydantic**
- Persistência de dados com **SQLite**
- Organização em **camadas (routes, services, schemas)**
- Documentação automática de APIs

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com fins **educacionais**, acompanhando a trilha **Python da NLW Operator**, com foco em:

- Aprender desenvolvimento **backend com Python**
- Construir **APIs modernas**
- Aplicar **boas práticas de arquitetura**

---

## 📌 Melhorias futuras

- [ ] Adicionar autenticação
- [ ] Implementar testes automatizados
- [ ] Utilizar banco de dados PostgreSQL
- [ ] Deploy da API

---

## 👩‍💻 Autora

Feito com 💜 por **Camille Almeida**

GitHub:  
https://github.com/CamilleGFAlmeida

---

## 📄 Licença

Este projeto está sob a licença **MIT**.
