# Escopo e objetivo

Projeto desenvolvido como teste prático pra empresa Develcode. <br/>
Consiste de uma aplicação React Native para CRUD de usuários, com backend desenvolvido em Node.js e banco de dados Postgresql.

## Como Executar

- Backend:<br/>
Acesse a pasta backend no terminal.<br/>
Instale as dependencias com o comando: npm install<br/>
Para executar o servidor digite o comando: npm run dev<br/>
Ele poderá ser acessado através do link https://localhost:3000

- FrontEnd:<br/>
Acesse a pasta 'testedevelcode' no terminal.<br/>
Instale as dependencias com o comando: npm install<br/>
Para rodar em modo debug execute o comando: react-native run-android <br/>
Para gerar um apk execute o comando: react-native run-android --variant

## Troubleshooting

- Configuração do hostname e porta no backend<br/>
  Acesse o arquivo index.js em 'backend > src > index', e altera as variáveis hostname e port. Por padrão esta setado hostname = localhost" e port = "3000"
  
- Configuração da URL frontend<br/>
  Acesso o arquivo Api.js em 'frontend > testedevelcode > src > services', e altera a variável baseURL. Por padrão esta setado baseURL: 'http://localhost:3000',
