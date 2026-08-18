# Olá! Eu sou o Tiago Becker 👋

Desenvolvedor **Full Stack** (Node.js / React) — mantenho em produção, há **4 anos**, um sistema de e-commerce completo para um cliente real: API, storefront e painel administrativo. Gosto de resolver problemas de arquitetura de ponta a ponta, do banco de dados à experiência do usuário.

📩 [beckertiago09@gmail.com](mailto:beckertiago09@gmail.com) · 💬 [WhatsApp](https://wa.me/5551995204223) · 🌐 [Portfolio](https://tiagobecker.vercel.app)

---

## 🏆 Projeto em destaque — FichaAnamnese (E-commerce em produção)

**[anamnesis-ecommerce-platform](https://github.com/TiagoRBecker/anamnesis-ecommerce-platform)**
Sistema de e-commerce para venda de documentos digitais na área da saúde, **em produção contínua há 4 anos**, atendendo cliente real — não é um projeto de portfólio, é um sistema que sustenta um negócio de verdade. Composto por API (NestJS), storefront (Next.js) e painel administrativo (Next.js).

**Decisões técnicas que sustentam o sistema:**

- **Autenticação resiliente** — fluxo de refresh de JWT integrado ao NextAuth, evitando que o usuário perca sessão em uso prolongado
- **Orquestração de pós-pagamento com Strategy Pattern** — lida com múltiplos fluxos de conclusão de pedido de forma desacoplada e extensível
- **Webhook guard com log de IP** — validação e rastreabilidade de eventos de pagamento recebidos por webhook
- **Upload multipart para AWS S3** — envio de arquivos grandes (documentos/imagens) de forma confiável e resumível
- **Login social com detecção de conflito** — Google OAuth tratando colisão de contas já existentes
- **Cache inteligente no frontend** — React Query com invalidação de cache para manter dados sincronizados sem over-fetching
- **Carrinho persistente** — Zustand com persistência em localStorage, mantendo o carrinho entre sessões
- **Interceptor HTTP customizado** — camada Axios própria para tratamento centralizado de erros e renovação de token

> Esse projeto reúne os três repositórios do sistema (API, storefront, admin) apresentados como uma arquitetura única — não como projetos isolados.

---

## 🛠️ Stack

<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" height="28" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" height="28" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" height="28" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" height="28" />
</p>

**Backend:** Node.js, NestJS, PostgreSQL, Prisma, RabbitMQ, Redis, Jest  
**Frontend:** React, Next.js  
**Infra:** Docker, AWS, Nginx, GitHub Actions

---

## 🏗️ Arquitetura & Princípios

Aplicados no dia a dia, principalmente no case acima:

- **Arquitetura Hexagonal** — separação de domínio, adaptadores e interfaces
- **SOLID** — código modular e manutenível
- **Clean Code & Clean Architecture** — código limpo e desacoplado
- **Testável e escalável** — cobertura de testes unitários e de integração com Jest

---

## 📂 Outros projetos

| Projeto | Descrição |
|---|---|
| [editorial-management-system](https://github.com/TiagoRBecker/editorial-management-system) | Sistema editorial com controle de publicações, autores e fluxo de aprovação — NestJS + PostgreSQL |
| [obrafacil](https://github.com/TiagoRBecker/obrafacil) | Sistema de orçamento para construção civil com geração de propostas — TypeScript + Node.js |
| [case-site-institucional-guedesbampi](https://github.com/TiagoRBecker/case-site-institucional-guedesbampi) | Site institucional com SSR, rotas dinâmicas e SEO — Next.js + Nodemailer |
| [case-landpage-cotasracias](https://github.com/TiagoRBecker/case-landpage-cotasracias) | Landing page de captação de leads para consórcio — foco em conversão |
| [case-landpage-dividas](https://github.com/TiagoRBecker/case-landpage-dividas) | Landing page de captação de leads para advocacia — Next.js + SEO |

---

📍 Brasil · Atendimento remoto
