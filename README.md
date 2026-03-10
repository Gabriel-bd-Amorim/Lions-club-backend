# Lions Club Backend

Backend desenvolvido para o sistema de gestão do **Lions Club Corumbá**, responsável por gerenciar usuários, cadastro de pessoas e controle de inventário de produtos ortopédicos utilizados em comodatos.

A API fornece toda a lógica de negócio e comunicação com o banco de dados, permitindo que o sistema frontend realize operações como cadastro, autenticação e gerenciamento de itens.

Este projeto foi desenvolvido como parte de uma solução para melhorar o controle e a rastreabilidade dos recursos da instituição.

---

# Integração com o Frontend

Este backend é utilizado pelo frontend disponível em:

🔗 https://github.com/Gabriel-bd-Amorim/LionsClubCRB

O frontend consome esta API para realizar todas as operações do sistema.

---

# Tecnologias Utilizadas

- Node.js
- Express
- JWT (JSON Web Token)
- Swagger
- PostgreSQL
- Railway (deploy)

---

# Funcionalidades

A API oferece suporte para as seguintes operações:

## Autenticação
- Login de usuários
- Autenticação utilizando JWT

## Usuários
- Cadastro de usuários
- Controle de acesso ao sistema

## Pessoas (Comodato)
- Cadastro de pessoas que irão receber produtos ortopédicos
- Gerenciamento de registros de comodato

## Inventário
- Cadastro de itens
- Controle de estoque
- Filtragem de produtos

---

# Documentação da API

A documentação da API foi gerada utilizando **Swagger**, permitindo visualizar e testar os endpoints diretamente pelo navegador.

---

# Variáveis de Ambiente

Para rodar o projeto é necessário criar um arquivo `.env` com as seguintes variáveis:

```env
DATABASE_URL=
HOST=
NAME=
PASSWORD=
SECRET_KEY=
USER=
