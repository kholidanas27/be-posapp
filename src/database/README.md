## database

this directory for database file

## create models
# using npm
npx sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string
# using yarn
yarn sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string

## migrate models
# using npm
npx sequelize-cli migration:generate --name migration-example
# using yarn
yarn sequelize-cli migration:generate --name migration-example
