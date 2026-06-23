# in.orbit — Front-end

Interface web da aplicação **in.orbit**, projeto para cadastro e acompanhamento de metas a serem concluídas durante a semana, desenvolvido durante o NLW Pocket: Javascript da Rocketseat. Este repositório contém o **front-end**, que consome a [API do back-end](https://github.com/fernandoDusk/in-orbit-back-end.git).

## 🚀 Tecnologias

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/) — estilização
- [TanStack Query (React Query)](https://tanstack.com/query) — gerenciamento de estado e cache de requisições

## 📋 Pré-requisitos

Antes de começar, você precisa ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (versão 18+)
- Um gerenciador de pacotes: `npm`, `yarn` ou `pnpm`
- O [back-end do in.orbit](https://github.com/fernandoDusk/in-orbit-back-end.git) rodando localmente (necessário para consumir a API)

## ⚙️ Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/fernandoDusk/in-orbit.git
cd in.orbit/frontend
npm install
```

## ▶️ Executando o projeto

Modo de desenvolvimento (com hot reload):

```bash
npm run dev
```

> ⚠️ Certifique-se de que o back-end já está rodando antes de iniciar o front-end, para que as requisições funcionem corretamente.


## 📌 Funcionalidades

- Visualizar o resumo semanal de metas (concluídas vs. pendentes)
- Cadastrar uma nova meta com frequência desejada na semana
- Marcar uma meta como concluída
- Acompanhar o progresso visual das metas da semana

## 📄 Licença

Este projeto está sob a licença MIT.

---
