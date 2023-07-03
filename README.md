# Cronjob-nodejs
Projecto foi criado para o estudo de background job

A API simula o cadrasto de um usuário e em paralelo faz um envio de e-mail, e essa comunicação com o serviço de e-mail é feita de um jeito assincrono utilizado um serviço de filas, assim aplicando o conceito de cronjob, para impletentação foi utilizado o express para criação do servidor e as rotas da API, a biblioteca bull com o redis para o serviço de filas, e o bull-board para o monitorar os cronjobs e as mensagens enviadas a cada job na fila
