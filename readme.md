
# 🧪 Projeto: Easy CRM 2.0

Este projeto é um sistema completo com **Back-End em Node.js/TypeScript** e **Front-End em React/Vite**, incluindo autenticação via JWT, filas com RabbitMQ, e estilização moderna com TailwindCSS.

---

## 🧠 Back-End

| Camada           | Ferramenta / Biblioteca       | Descrição                                                              |
|------------------|-------------------------------|------------------------------------------------------------------------|
| Linguagem        | TypeScript                    | Tipagem estática para maior segurança e escalabilidade                 |
| Servidor Web     | Express                       | Framework HTTP leve e flexível                                         |
| Banco de Dados   | MySQL                         | Banco relacional                                                       |
| ORM              | Prisma                        | ORM moderno com migrations e tipagem                                   |
| Mensageria       | RabbitMQ (`amqplib`)          | Processamento assíncrono com filas                                     |
| Autenticação     | JWT (`jsonwebtoken`)          | Token seguro e stateless                                               |
| Segurança        | Helmet, dotenv                | Proteção de headers e configuração por ambiente                        |
| Utilitários      | Morgan, CORS, Body-parser     | Logging de requisições, CORS e parse de corpo JSON                     |

---

## 🎨 Front-End

| Camada                | Ferramenta / Biblioteca       | Descrição                                                              |
|-----------------------|-------------------------------|------------------------------------------------------------------------|
| Linguagem             | TypeScript                    | Tipagem forte no React                                                 |
| Framework             | React + Vite                  | SPA com dev server rápido e build otimizado                            |
| Estilização           | TailwindCSS                   | Estilos modernos com classes utilitárias                               |
| Roteamento            | React Router DOM              | Navegação entre páginas (SPA)                                          |
| HTTP Client           | Axios                         | Requisições HTTP com interceptação de headers                          |
| Autenticação          | JWT + localStorage            | Persistência de login e proteção de rotas                              |
| Estado Global         | React Context + Hooks         | Compartilhamento de autenticação e controle de sessão                  |

---

## 🚀 Como rodar o projeto

### 📦 Back-End

```bash
cd api-referrals
npm install
npx prisma generate
npx prisma migrate dev --name init
npm run dev
```

### 💻 Front-End

```bash
cd frontend-referrals
npm install
npm run dev
```

---

## 📌 Requisitos

- Node.js 18+ (recomendado)
- MySQL rodando localmente
- Docker (opcional para RabbitMQ)
- Prisma CLI

---

## ✨ Melhorias Futuras

- Upload de imagem com fila
- Admin dashboard
- Swagger para documentação
- Deploy: Render (back) + Vercel (front)

---

Feito com ❤️ por 2easy Insurance Dev Team
