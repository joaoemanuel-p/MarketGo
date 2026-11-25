# 🛒 MarketGo

Aplicativo mobile de compras e delivery desenvolvido em React Native com Expo, integrado ao Supabase para autenticação, banco de dados PostgreSQL e controle de acesso por RLS.

O projeto foi desenvolvido como atividade acadêmica do curso de Análise e Desenvolvimento de Sistemas (ADS) do IESB, com foco em desenvolvimento mobile, integração com banco de dados, segurança e organização de aplicações.

## 🎯 Objetivo

Desenvolver uma aplicação de compras e delivery que permita ao usuário navegar por lojas e produtos, montar um carrinho, realizar o checkout e acompanhar seus pedidos.

A aplicação utiliza o Supabase como backend, com autenticação de usuários, PostgreSQL, Row Level Security (RLS) e funções SQL para operações críticas relacionadas aos pedidos.

## 🚀 Funcionalidades

- Cadastro e autenticação de usuários;
- Login e gerenciamento de sessão;
- Listagem de lojas;
- Catálogo de produtos;
- Visualização de produtos;
- Adição e remoção de produtos do carrinho;
- Alteração de quantidades;
- Cálculo do subtotal e total do carrinho;
- Checkout;
- Criação de pedidos;
- Visualização do histórico de pedidos;
- Acompanhamento do status dos pedidos;
- Cancelamento de pedidos quando permitido;
- Atualização controlada do status dos pedidos;
- Validação de dados com Zod;
- Formulários com React Hook Form;
- Gerenciamento de estado e dados com TanStack Query;
- Persistência e autenticação utilizando Supabase;
- Controle de acesso utilizando Row Level Security (RLS);
- Testes automatizados da aplicação e do banco de dados.

## 🛠️ Tecnologias

| Tecnologia | Utilização |
|---|---|
| React Native | Desenvolvimento da aplicação mobile |
| Expo | Ambiente e ferramentas para desenvolvimento React Native |
| Expo Router | Navegação baseada em rotas |
| TypeScript | Tipagem e organização do código |
| Supabase | Backend e integração com banco de dados |
| PostgreSQL | Banco de dados relacional |
| Row Level Security (RLS) | Controle de acesso aos dados |
| TanStack Query | Gerenciamento de dados e requisições |
| React Hook Form | Gerenciamento de formulários |
| Zod | Validação de dados |
| Jest | Testes automatizados |
| PGlite | Testes relacionados ao banco de dados |
| Prettier | Padronização de código |

## 📁 Estrutura do projeto

```text
MarketGo/
├── app/                    # Rotas e telas da aplicação
├── assets/                 # Imagens e recursos visuais
├── scripts/                # Scripts auxiliares
├── src/
│   ├── components/         # Componentes reutilizáveis
│   ├── constants/          # Constantes da aplicação
│   ├── context/            # Contextos da aplicação
│   ├── hooks/              # Hooks personalizados
│   ├── lib/                # Configurações e bibliotecas
│   ├── schemas/            # Schemas de validação
│   ├── services/           # Serviços e acesso aos dados
│   ├── theme/              # Configurações visuais
│   ├── types/              # Tipos TypeScript
│   └── utils/              # Funções utilitárias
├── supabase/
│   ├── schema.sql          # Estrutura do banco de dados
│   ├── seed.sql            # Dados iniciais
│   └── tests/              # Testes do banco de dados
├── __tests__/              # Testes da aplicação
├── .env.example            # Exemplo das variáveis de ambiente
├── .gitignore              # Arquivos ignorados pelo Git
├── app.json                # Configuração do Expo
├── App.tsx                 # Componente principal
├── index.ts               