# Oitavo desafio do bootcamp GoStack da Rocketseat (Relacionamentos com banco de dados no Node.js).

## Para rodar a aplicação siga os seguintes procedimentos:

### Obs: Para rodar essa aplicação será necessário fazer a instalação do Docker.

- Rodar o seguinte comando para criar uma imagem do PostgreSQL: <br/> sudo docker run --name goStackPostgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
- Iniciar o container do PostgreSQL: <br/> sudo docker start goStackPostgres
- Criar dois bancos de dados atráves de alguma ferramenta (utilizo o DBeaver) com os seguintes nomes: <br/>
gostack_desafio09
gostack_desafio09_tests
- Clone o repositório para a sua máquina usando o comando **git clone**.
- Acesse a pasta criada.
- Instale as dependências usando o comando **yarn**.
- Rode as migrations para o banco de dados usando o comando: **yarn typeorm migration:run**
- Para iniciar o backend digite o comando **yarn dev:server**.
