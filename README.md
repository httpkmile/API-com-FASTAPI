FastAPI - Projeto de Exemplo

Desenvolvi este projeto para demonstrar a criação de uma API web utilizando FastAPI, com uma arquitetura organizada em camadas para separar responsabilidades e facilitar a manutenção do código.

Utilizei SQLite assíncrono para persistência de dados, Pydantic para validação de entradas e rotas REST para cadastro e consulta de usuários.

Estrutura do projeto

src/main/server/server.py — inicializo a aplicação e registro as rotas.

src/main/routes/users_routes.py — defino os endpoints de criação e busca de usuários.

src/main/composer/ — organizo as dependências entre os componentes.

src/controllers/ — implemento a lógica de negócio para cadastro e consulta de usuários.

src/models/ — estruturo as entidades, os repositórios e a configuração do banco de dados.

src/views/ — organizo a conversão de requisições e respostas HTTP.

src/validators/ — valido os dados de entrada utilizando Pydantic.


Como executar:
Instalei as dependências listadas em requirements.txt:

pip install -r requirements.txt

Para iniciar o servidor, execute:

python run.py

