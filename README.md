GoBarber-NodeJs-Rocketseat
Um software como serviço para fornecer um agendamento entre barbeiros e clientes.

GoBarber-NodeJs-Rocketseat
Uso
Tecnologias
Instalação
Licença
Uso
O primeiro passo é criar sua conta, então você pode fazer o login e escolher um barbeiro, verificar a agenda dele e marcar uma consulta.

Tecnologias
Nó
Expressar
Sessão Expressa
Sequelizar
Postgres
Bcrypt
Nunjucks
Multer
Moment.JS
Connect-Loki
Connect-Flash
dotenv
Eslint-Airbnb
Nodemon
Instalação
Clone o projeto com

git clone https://github.com/ricardoricarte/GoBarber.git
Entre no projeto do caminho e instale as dependências com:

fio
Em seguida, você deve criar seu banco de dados do postgres (ou outro se desejar) e preencher seus próprios campos no arquivo .env.

Agora, você precisa criar tabelas com o comando:

npx sequelize db: migrate
Após a configuração do banco de dados, você pode iniciar o servidor com:

início do fio
Se você estiver no ambiente de desenvolvimento, poderá usar o servidor de desenvolvimento:

dev de fios
Licença
MIT