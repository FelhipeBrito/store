<<<<<<< HEAD
# 🛒 E-Commerce Store

Um projeto de e-commerce desenvolvido com **React**, **TypeScript** e **Vite**, criado com o objetivo de simular uma aplicação utilizada em um ambiente profissional.

O foco deste projeto é aplicar boas práticas de desenvolvimento Front-end, arquitetura escalável, componentização, consumo de APIs REST, gerenciamento de estado e organização de código utilizando uma estrutura **Feature First**.

---

## Objetivo

Este projeto foi desenvolvido como parte dos meus estudos para evoluir como desenvolvedor Full Stack.

Mais do que construir uma interface funcional, a proposta é praticar conceitos encontrados em aplicações reais, como:

* Arquitetura escalável
* Organização por funcionalidades (Feature First)
* Componentização
* Tipagem forte com TypeScript
* Integração com APIs REST
* Gerenciamento de estado
* Autenticação
* Responsividade
* Código limpo e reutilizável

---

## Tecnologias

### Front-end

* React
* TypeScript
* Vite
* React Router
* Axios
* CSS Modules *(ou outra solução de estilização utilizada)*

### Gerenciamento de estado *(planejado)*

* TanStack Query
* Zustand

### Ferramentas

* ESLint
* Prettier
* Git
* GitHub

---

## Funcionalidades

### Cliente

* Cadastro de usuário
* Login e autenticação
* Catálogo de produtos
* Busca de produtos
* Filtros
* Página de detalhes do produto
* Lista de favoritos
* Carrinho de compras
* Alteração de quantidade
* Checkout
* Histórico de pedidos
* Perfil do usuário
* Avaliações de produtos
* Aplicação de cupons

### Administração

* Login administrativo
* Cadastro de produtos
* Edição de produtos
* Exclusão de produtos
* Gerenciamento de pedidos
* Gerenciamento de usuários

---

## Estrutura do Projeto

```text
src/
│
├── app/
├── assets/
├── components/
├── features/
├── services/
├── hooks/
├── contexts/
├── constants/
├── utils/
├── styles/
└── types/
```

A aplicação utiliza uma arquitetura **Feature First**, na qual cada funcionalidade possui seus próprios componentes, hooks, serviços, tipos e páginas, facilitando a manutenção e a escalabilidade do projeto.

---

## Arquitetura

Este projeto procura seguir alguns princípios utilizados em aplicações de produção:

* Organização por funcionalidades
* Separação de responsabilidades
* Componentes reutilizáveis
* Serviços desacoplados
* Tipagem consistente
* Estrutura preparada para crescimento

---

## Roadmap

### Em desenvolvimento

* [ ] Sistema de autenticação
* [ ] Integração com API
* [ ] Página inicial
* [ ] Página de produtos
* [ ] Página de detalhes
* [ ] Carrinho de compras
* [ ] Favoritos
* [ ] Checkout
* [ ] Perfil do usuário
* [ ] Histórico de pedidos
* [ ] Painel administrativo

### Melhorias futuras

* [ ] Testes unitários
* [ ] Testes de integração
* [ ] Testes E2E
* [ ] Internacionalização (i18n)
* [ ] Dark Mode
* [ ] Lazy Loading
* [ ] Otimização de performance
* [ ] PWA

---

## Como executar o projeto

Clone o repositório:

```bash
git clone https://github.com/FelhipeBrito/store
```

Entre na pasta:

```bash
cd store
```

Instale as dependências:

```bash
npm install
```

Execute o projeto:

```bash
npm run dev
```

Build de produção:

```bash
npm run build
```

---

## Aprendizados

Durante o desenvolvimento deste projeto, estou praticando:

* React
* TypeScript
* Arquitetura Front-end
* Consumo de APIs REST
* Gerenciamento de estado
* Organização de projetos escaláveis
* Boas práticas de desenvolvimento
* Git e GitHub

---

## Status

🚧 Projeto em desenvolvimento.

Novas funcionalidades serão implementadas gradualmente conforme a evolução dos estudos.

---

## Licença

Este projeto foi desenvolvido para fins de estudo e portfólio.
=======
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default defineConfig([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...

      // Remove tseslint.configs.recommended and replace with this
      tseslint.configs.recommendedTypeChecked,
      // Alternatively, use this for stricter rules
      tseslint.configs.strictTypeChecked,
      // Optionally, add this for stylistic rules
      tseslint.configs.stylisticTypeChecked,

      // Other configs...
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])

```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default defineConfig([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      reactX.configs['recommended-typescript'],
      // Enable lint rules for React DOM
      reactDom.configs.recommended,
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])

```
>>>>>>> 6a4fdef (Primeiro commit)
