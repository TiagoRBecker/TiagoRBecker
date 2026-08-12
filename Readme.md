# Olá! Eu sou o Tiago Becker 👋

Desenvolvedor **Full Stack** (Node.js / React) — mantenho em produção, há **4 anos**, um sistema de e-commerce completo para um cliente real: API, storefront e painel administrativo. Gosto de resolver problemas de arquitetura de ponta a ponta, do banco de dados à experiência do usuário.

📩 [beckertiago09@gmail.com](mailto:beckertiago09@gmail.com) · 💬 [WhatsApp](https://wa.me/5551995204223)

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

![JavaScript](https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg) ![TypeScript](https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg) ![React](https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg) ![Node.js](https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg) ![NestJS](https://github.com/devicons/devicon/raw/master/icons/nestjs/nestjs-original-wordmark.svg) ![Next.js](https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg) ![Prisma](https://github.com/devicons/devicon/raw/master/icons/prisma/prisma-original.svg) ![PostgreSQL](https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg) ![Docker](https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg)

**Backend:** Node.js, NestJS, PostgreSQL, Prisma, RabbitMQ, Redis, Jest
**Frontend:** React, Next.js
**Infra:** Docker, AWS, Nginx, GitHub Actions

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
| [editorial-management-system](https://github.com/TiagoRBecker/editorial-management-system) | Sistema de gestão editorial |
| [obrafacil](https://github.com/TiagoRBecker/obrafacil) | Sistema de orçamento (TypeScript) |
| [case-site-institucional-guedesbampi](https://github.com/TiagoRBecker/case-site-institucional-guedesbampi) | Site institucional |
| [case-landpage-cotasracias](https://github.com/TiagoRBecker/case-landpage-cotasracias) | Landing page |
| [case-landpage-dividas](https://github.com/TiagoRBecker/case-landpage-dividas) | Landing page |

---

📍 Brasil · Atendimento remoto
