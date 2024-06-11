# FIAP Blog

O Blog FIAP é uma aplicação web desenvolvida com React e Vite, utilizando Contentful como CMS para gerenciamento de conteúdo. Este projeto é um exemplo de um blog simples, com componentes reutilizáveis e navegação entre páginas.

## Tecnologias Utilizadas

- React 18.2.0
- Vite 5.2.0
- React Router Dom 6.23.1
- Bootstrap 5.3.3
- Contentful 10.11.7
- ESLint 8.57.0

## Scripts Disponíveis

dev: Inicia o servidor de desenvolvimento.
npm run dev

build: Compila o projeto para produção.
npm run build

## Uso
Para iniciar o servidor de desenvolvimento, execute:
npm run dev

## Componentes
Card: Componente para exibir posts ou informações em um formato de cartão.
Footer: Componente de rodapé.
Header: Componente de cabeçalho.
Layout: Componente de layout para estruturação das páginas.

## Páginas
AllPosts: Página que lista todos os posts.
Home: Página inicial.
Post: Página para exibir um post específico.

## Integração com Contentful
Este projeto utiliza Contentful como CMS para gerenciar o conteúdo do blog. Certifique-se de configurar as credenciais de acesso ao Contentful no seu ambiente de desenvolvimento.

Crie um arquivo .env na raiz do projeto com as seguintes variáveis:
VITE_CONTENTFUL_SPACE_ID=seu_space_id
VITE_CONTENTFUL_ACCESS_TOKEN=seu_access_token


