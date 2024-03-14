## database

this directory for database file

## create models
# using npm
npx sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string
# using yarn
yarn sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string

## generate migrations
# using npm
npx sequelize-cli migration:generate --name migration-example
# using yarn
yarn sequelize-cli migration:generate --name migration-example

## migrate
# using npm 
npx sequelize-cli db:migrate
# using yarn 
yarn sequelize-cli db:migrate