### 🙏 Agradecimentos

Este projeto foi inspirado no excelente trabalho da [Fernanda Kipper](https://github.com/Fernanda-Kipper), disponível no [repositório original](https://github.com/Fernanda-Kipper/login-app-backend) e no [vídeo do YouTube](https://www.youtube.com/watch?v=tJCyNV1G0P4), que guiou a construção desta API de login, registro e autenticação dos usuários.

# Spring Auth API

## 📌 Sobre o projeto

Este é o backend da aplicação de autenticação desenvolvida com **Java** e **Spring Boot**, que serve de base para o frontend em Angular disponível no repositório [ng-login-signup-app](https://github.com/eugeniobr25/ng-login-signup-app).

A API tem como objetivo fornecer endpoints seguros para cadastro, login e acesso autenticado de usuários, utilizando **JWT (JSON Web Tokens)** para garantir a segurança da autenticação.

## 🚀 Tecnologias utilizadas

- Java 17
- Spring Boot
- Spring Security
- JWT
- Maven

## 🔐 Funcionalidades

- Cadastro de novos usuários
- Login e geração de token JWT
- Autenticação e proteção de rotas
- Retorno de dados do usuário autenticado

## 🧪 Como executar o projeto localmente

1. Clone o repositório:

```bash
git clone https://github.com/eugeniobr25/spring-auth-api.git
```

2. Navegue até o diretório do projeto:

```bash
cd spring-auth-api
```

3. Compile e rode a aplicação com o Maven:
   
```bash
mvn spring-boot:run
```

4. A API estará disponível em:
   
```bash
http://localhost:8080
```
---
📂 Estrutura de pastas

```bash
src
└── main
    └── java
        └── com.example.loginauthapi
            ├── controller
            ├── domain
            ├── infra
            │   └── security
            ├── repository
            └── service
```
---
📬 Endpoints principais

| Método | Rota         | Descrição               | Protegido |
| ------ | ------------ | ----------------------- | --------- |
| POST   | /auth/signup | Cadastrar novo usuário  | ❌         |
| POST   | /auth/login  | Autenticação/login      | ❌         |
| GET    | /user        | Dados do usuário logado | ✅         |
---
🧠 Observações

Este projeto foi desenvolvido como parte de um exercício prático de aprendizado, conectando os conceitos de backend com frontend, utilizando autenticação moderna baseada em tokens.



