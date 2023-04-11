# Chat Front
Esse é um projeto Front end com React que consome o projeto Socket.io disponível em https://github.com/Carlos-hub/chatIOT.

## Instalação e Uso
1. Acesse a pasta via terminal e baixe as dependências com o comando `npm install`.
2. Acesse o arquivo App.tsx e altere a URL para aquela definida no projeto citado anteriormente, na variável `PORT_SOCKET`.
3. Execute o projeto com o comando `npm run dev`.
4. Acesse a URL que irá aparecer no seu console.

Os eventos emitidos para o back end são:
- joinRoom
- sendMessage

Os eventos ouvidos do back end são:
- receiveMessage

Você pode personalizar esses eventos de acordo com as necessidades do seu projeto.
