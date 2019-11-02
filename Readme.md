# NodeJS e API

## Atualização: 02 de novembro de 2019 - 12:09
## Criação: 08 de fevereiro de 2019
## Prática : @douglasabnovato

## Ferramentas : 

![Rocketseat](/images/logo-rocketseat.png)
![Docker](/images/logo-docker.png)
![Robo 3T](/images/logo-robo3t.png)
![Nodejs](/images/logo-nodejs.png)
![ReactJS](/images/logo-reactjs.jpg)
![Git](/images/logo-git.png)
![Github](/images/logo-github.png)
![HTML/CSS/Javascript](/images/logo-html-css-js.jpeg)
![VSCode](/images/logo-VSCode.png)
![Yarn](/images/logo-yarn.png)

### Aula 1 . O que é API Rest e NodeJS
- javascript para Frondend, com ReactJS e React Native, e agora para Backend com NodeJS.
- API Rest : separa o backend, servidor e banco de dados, do frondend.
- **NodeJS**, **MongoDB**, **Express**

### Aula 2 . Instalando NodeJS- API Rest : separa o backend do frondend.
- `node -v`, npm -v, mkdir node-api, cd node-api
- npm init
- npm install express

### Aula 3 . Criando a estrtura

### Aula 4 . Criando a primeira rota
- utilizando o **express**
- server.js
- `node server.js`
- http://localhost:3001/

### Aula 5 . Utilizando Nodemon
- npm install -D nodemon
- node server.js
- npm run dev
- abre : http://localhost:3001/
- package.json/dependencies:
```json
"dependencies": {
    "express": "^4.16.4",
    "mongoose": "^5.4.9",
    "mongose": "0.0.2-security"
  }
```

### Aula 6 . Instalando MongoDB
- docker : máquina de conteinerização
- windows 10 home não possui "Hyper -v", por isso, problema com virtualização.
- máquina virtual , docker tools, prompt
- utilizando virtualbox + docker tools
- ```docker``` 
- ```docker run --name mongodbrs -p 27017:27017 -d mongo```
- ```docker ps```
- Robot 3T
- depois de fechar o notebook :
1. ```docker ps -a``` : saber imagens que estão pausadas
2. ```docker start mongodb``` : ou mongodbrs : nome das minhas conexões
3. ```docker ps``` : para verificar qual conexão está rodando
- abre : http://localhost:27017/

### Aula 7 . Conectando Database
- ```npm install mongoose``` : código javascript para usar bd, ao invés de SQL.

### Aula 8 . Criando Model de produto
- Model de produto : www.producthunt.com
- biblioteca require-dir : `require('./src/models/Product');` : com isso, não há necessidade desse require em todos os models do projeto.
- require-dir : `npm install require-dir`

### Aula 9 . Reestruturação de arquivos
- Controllers : Product Controller : `ProductController.js`

### Aula 10 . Utilizando Insomnia
- Insomnia 

### Aula 11 . Criaçaõ de registro
- registros : rever aqui

### Aula 12 . CRUD

### Aula 13 . Paginação de Lista

### Aula 14 . Adicionando CORS


:. Do curso `NodeJS`. <br/>
Por Diego Fernandes - Rocketseat : https://rocketseat.com.br/