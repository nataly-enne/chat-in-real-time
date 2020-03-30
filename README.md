## CHAT em tempo real
> Desenvolvimento de um chat em _real-time_ com NodeJS e Socket.io. 

> A aplicação do chat conversa com um servidor em NodeJS em tempo real.

### Como testar

1. Clone o projeto
```bash
git clone https://github.com/nataly-enne/chat-in-real-time.git
```

2. No terminal, dentro da pasta do projeto execute a instalação das bibliotecas

```bash
npm install ejs express socket.io # você pode usar "yarn add" no lugar do npm install se preferir
```

3. Inicie o servidor

```bash
node server.js
```

4. Abra uma aba no navegador no `localhost:3000` e outra aba anônima também no `localhost:3000`.

## Caso surja algum erro

> Crie um projeto limpo e apenas adicione a pasta public e o arquivo `server.js` na raiz.

1. Para criar um projeto do zero, entre no diretorio de uma pasta vazia pelo terminal e execute:

```bash
npm init -y # Irá criar o arquivo package.json 
```

2. Instalando as bibliotecas

```bash
npm install ejs express socket.io # você pode usar "yarn add" no lugar do npm install se preferir
```

3. Baixar o projeto ou dar um _git clone_ e em seguida adicionar a pasta `public` e o arquivo `server.js` na raiz do projeto.

4. Só testar o projeto, lembrando de inicializar o _server.js_ no terminal com `node server.js` e acessar no browser com `localhost:3000`.