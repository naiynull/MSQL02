____________________________________________________________ANOTAÇÃO BANCO DE DADOS__________________________________________________________________________________________ 




API->interface da aplicação  o cliente vai guardar os dados da API
cliente para servidor(conexão): é feita pelo https(online)
host do mysql-> localhost 
https: (protocolo )
get: pedindo alguma coisa para API
obs: são partes diferentes (servidor  diferente )
cliente para servidor 
http://127.0.0.1:3333  
 -


--------------COMANDOS-------------------------------
sudo systemctl start mysql
node -v
npm init adonis-ts-app@latest hello-world
npm i @adonisjs/lucid
node ace configure @adonisjs/lucid
npm i @adonisjs/auth
node ace configure @adonisjs/auth
node ace-> ele vai ler o seu codigo e criar as tabelas 
migration:run-> migra uma tabela para o banco de dados 
validator register-> validar
node ace serve --watch->  mesma coisa que o npm run dev
SELECT * -> olhar os clientes 
------------------------------------------------------

----------------SCRIPT---------------------
dev->acessar a visualização 
biuld->gera aversão para ir para o servidor
start-> testar a versão online
test-> testar o código 
-------------------------------------------


--------------------------------------------OBSERVAÇÕES-----------------------------------------------------------------------------------
->As senhas enviadas são quitrogafadas em uma única mão ou seja ela não é traduzida, para autenticação será comparada de forma quitrogafadas 
->quando uma reposição chegar nesse endereço é encaminhada para a patinha start 
->lucid funciona como uma ponte direta de conexão se excluir ou incluir em um, ambas são afetadas 
-------------------------------------------------------------------------------------------------------------------------------------------




---------------------------------------------------------------------------------------------------------------------------------
variável de ambiente-> para usar nesse ambiente/local
.envi-> não vai para o github, se ele subir poderá ter acesso ao seu msql
slint-> software que cobra o erros tipo como espaços e tals, NÃO USAR 
migration-> possui o comando de cria a tabele resumindo mexe com a extrutura da tabela 
migração-> você cria e modifica a sua tabela, fazendo grandes e pequenas alterações com o sistema rodando(sistema contino)
ex: instagram, fecebook etc.
unique -> ferifica o email
migration -> migração da tabela para o servido 
ORM -> mapeamento de objeto relacional    
classe mod -> modelo de dados  vai fazer o orm 
---------------------------------------------------------------------------------------------------------------------------------



---------------TABELA-------------------------------------
tabela do usuario-> mantem os dados do usuario
tabela de tokens-> usuarios onlines e a expiração dos tokens 
-----------------------------------------------------------




------------ERRO------------
400- requisição errada 
401 - senha errada 
402 - método de pagamento
------------------------------



----------------------CONTROLER------------------------------------------------
-> ele verifica o dado vindo da requisição e busca os "caminhos " para o uso
->chama o validate e ferifica se é viavel 
-> chama os atributos que precisa 
-> retorna 
-------------------------------------------------------------------------------





------------------------------------LOGIN----------------------------------------------------------------------------
atmp-> pegar o pesuart e comparar o pesuart e retorna se é valido ou não se for vailido ele manda o token que dura apenas 24h 
findbyorfaild-> se o email ou senha estiver errado ele retorna erro 
try-> tentando
catch-> quando o try estiver errado 
------------------------------------------------------------------------------------------------------------------------------






----------------------------ROUTER-------------------------------------
-> a mesma ideia da rota em redes pega de um local e envia para outro
------------------------------------------------------------------------








-------------------------------BYFORSAVER---------------------------------------------
byforsaver-> antes de salvar vai fazer um hast da senha(criptografia)
middleware -> fica no meio 
mnada uma API o servidor confere e manda o token o middleware confere e ver se é veridico 
----------------------------------------------------------------------------------------






-----------------------------------------------------------------------------------------
closs-> permite conexões de varíos locais 
->ele tem que permite de varios locais diferentes 
ex: lazaro manda da casa dele, a alice da casa dela ou seja locais diferentes 


Noen-> hospedar o banco de dados 
Hander-> hospedar o java script 
arm -> gerenciador de pacote (npm)
----------------------------------------------------------------------------------------


ROTEIRO 
abrir o php myadmin
acessar o seu bancoi de dados (não executar)
criar o arquivo .env 
copiar o que esta no arquivo .env.example 
configuarar os dados no .env(mudar o user, senha, nome do banco de dados )
sudo systemctl start mysql


