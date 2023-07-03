# Cronjob-nodejs
Projecto foi criado para o estudo de background job

A API simula o cadrasto de um usuário e em paralelo faz um envio de e-mail, e essa comunicação com o serviço de e-mail é feita de um jeito assincrono utilizado um serviço de filas, assim aplicando o conceito de cronjob, para impletentação foi utilizado o express para criação do servidor e as rotas da API, a biblioteca bull com o redis para o serviço de filas, e o bull-board para monitorar os cronjobs e as mensagens enviadas a cada job na fila.

Para rodar o projecto:

criar um arquivo ".env" na raiz do projecto com as seguintes configurações:

MAIL_HOST=
MAIL_PORT=
MAIL_USER=
MAIL_PASS=

REDIS_HOST=
REDIS_PORT=

Depois rodar os comandos:
1º npm install ou yarn install
2º npm run dev ou yarn dev


