# Desenvolvimento do projeto passo a passo

## Criando o ambiente de desenvolvimento

- $npm create vite@latest -> criar o ambiente de desenvolvimento com as características necessárias.
  - Project name: movie_lib
  - Select a framework: react
  - Select a variant: react
- terminando de criar o projeto, devemos dar $cd movie_lib, $npm install para criar as dependência do projeto e adicionar outras para o projeto.
  - $npm install react-icons react-router-dom -> Icones para o projeto e pacote de rotas
- $npm run dev -> rodará o projeto na porta informada
- Agora iremos trazer as varáveis de ambiente, com isso trabalhar com chaves de API's. E para para isso, na pasta movies_lib criaremos o arquivo .env