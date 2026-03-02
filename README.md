# Artigos — Blog News

Projeto frontend Next.js para exibir artigos, dicas e últimas notícias.

Link publicado no Vercel: https://artigos-jbeklnshg-jv-sgs-projects.vercel.app/

## Visão geral

Este repositório contém um site de artigos construído com Next.js (App Router) e React, usando CSS Modules para estilos. A estrutura é organizada por rotas no diretório `src/app` e componentes reutilizáveis em `src/components`.

## Principais funcionalidades
- Paginação de artigos e páginas individuais por `slug`.
- Seção de dicas e últimas notícias.
- Componentes reutilizáveis: `Card`, `Header`, `Grid`, `Footer`, `Title`.
- Publicação contínua via Vercel (link acima).

## Tecnologias
- Next.js
- React
- CSS Modules
- Vercel (deploy)

## Requisitos
- Node.js (versão 18+ recomendada)
- npm (ou yarn)

## Instalação e execução local

Instale dependências:

```bash
npm install
```

Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

O site ficará disponível em `http://localhost:3000` por padrão.

Para gerar a versão de produção e rodar localmente:

```bash
npm run build
npm run start
```

## Estrutura do projeto (resumo)

- [src/app](src/app) — rotas da aplicação (app router)
- [src/app/artigos](src/app/artigos) — páginas de artigos
- [src/app/artigos/[slug]](src/app/artigos/%5Bslug%5D) — página de artigo por slug
- [src/app/artigos/Dicas](src/app/artigos/Dicas) — página de dicas
- [src/app/artigos/ultimas-noticias](src/app/artigos/ultimas-noticias) — últimas notícias
- [src/components](src/components) — componentes reutilizáveis (Card, Header, Grid, Footer, Title)
- [src/lib/artigos.js](src/lib/artigos.js) — helpers / fonte de dados dos artigos
- [src/styles](src/styles) — estilos globais e CSS Modules
- [src/types](src/types) — tipos TypeScript

## Deploy

O projeto foi publicado no Vercel. O deploy automático pode ser configurado conectando o repositório ao Vercel. O link atualmente publicado é:

https://artigos-jbeklnshg-jv-sgs-projects.vercel.app/

## Como contribuir
- Abra uma issue para discutir mudanças maiores.
- Faça um fork/branch, implemente e envie um pull request.

## Próximos passos sugeridos
- Comitar o `README.md` e criar um branch de trabalho.
- Adicionar CI (opcional) e checks de lint/format.

## Licença
Adicionar licença conforme desejado (ex: MIT).
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
