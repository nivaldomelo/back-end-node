yarn init -y
yarn add express
yarn add @types/express -D
yarn add typescript -D
yarn tsc --init
yarn add ts-node-dev -D


# para upload de arquivos
yarn add multer
yarn add @types/multer -D

yarn add csv-parse
yarn add swagger-ui-express
yarn add @types/swagger-ui-express -D


docker build -t rentx .
docker run -p 3333:3333 rentx

# Instalar o ORM do banco de dados - typeORM

yarn add typeorm reflect-metadata
yarn add pg


