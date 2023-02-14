# ESTUDO_Node.js
ANDAMENTO - Node.js, API Rest com Express e MongoDB.

* Linguagem JS
node --version
v18.14.0

* Gerenciador de Pacotes
npm -v
9.3.1

* Criar uma pasta via terminal

mkdir alura-node

* Dentro da pasta alura-node, inicializa o projeto com resposta das perguntas padrões

npm init -y

alura-node/package.json:

{
  "name": "alura-node",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}


* Comando para abrir o VSCode

code .

* No VSCode via terminal, rodar o servidor 

node server.js

* Installar a bibliote Nodemon para fazer live reload

npm install nodemon@2.0.15 -D

* Para rodar algum script, para rodar o nodemon

npm run dev
