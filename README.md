# typescript

verificar se já existe o NODE instalado:
* node -v

criar um projeto NODE:
* npm init (dentro da pasta)

instalar o typescript de modo global:
* npm install -g typescript

comando instalar liteServer:
* npm install lite-server

temos que criar o arquivo TSconfig
*tsc --init

-------
Como usar:

adicionamos a linha de comando abaixo dentro de scripts no arquivo package.json
*"start": "lite-server"
*para iniciar - npm start

Vamos dar start na aplicação!
criar um termninal exclusivo e rodar o comando:
* npm start

podemos compilar o typescript enquanto vamos atualizando ele.
* dentro de scripts no arquivo package.json adicionar a linha abaixo
* "watch": "tsc --watch"
* para iniciar - npm run watch


