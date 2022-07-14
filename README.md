# orm-sequelize

Projeto Node com o ORM Sequelize

---

Sequelize

- arquivos de configurações gerais: npx sequelize-cli init
- create schema: npx sequelize-cli model:create --name Pessoas --attributes nome:string,ativo:boolean,email:string,role:string
- create table: npx sequelize-cli db:migrate
- create seed: npx sequelize-cli seed:generate --name demo-pessoa
- migrando os dados: npx sequelize-cli db:seed:all
