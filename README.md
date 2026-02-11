# Nodets-Petshop

Este é um projeto de um petshop simples criado usando Node.js e TypeScript. Ele permite que os usuários pesquisem e vejam informações sobre animais disponíveis para adoção.

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas:

- Node.js
- TypeScript
- Express.js
- Mustache-express

## Instalação

1. Clone este repositório para o seu ambiente local.
2. Navegue até o diretório do projeto.
3. Execute `npm install` para instalar as dependências.

## Configuração

1. Crie um arquivo `.env` na raiz do projeto.
2. Defina as seguintes variáveis de ambiente no arquivo `.env`:
   - `PORT`: porta em que o servidor será executado (padrão: 3000).
3. Salve o arquivo `.env`.

## Executando o projeto

1. Execute `npm run start-dev` para iniciar o servidor em modo de desenvolvimento.
2. Abra o navegador e acesse `http://localhost:3000` para visualizar o petshop.

## Rotas

- `/`: Página inicial com uma lista de animais disponíveis para adoção.
- `/dogs`: Página com uma lista de cachorros disponíveis para adoção.
- `/cats`: Página com uma lista de gatos disponíveis para adoção.
- `/fishes`: Página com uma lista de peixes disponíveis para adoção.
- `/search?q={query}`: Página de pesquisa com resultados de animais com base na pesquisa do usuário.

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver alguma sugestão de melhoria, sinta-se à vontade para abrir uma issue ou enviar uma pull request.