# Ideas APP API



### Stack

- Database - PostgreSQL
- REST API - NestJS
- GraphQL API - NestJS
- Rest Frontend - Angular with NGRX
- GraphQL Frontend - React (Native?) with Apollo Client


### Start

```
  git clone https://github.com/hoannd0612/DemoNestJS

```
```
  cd DemoNestJS
  ```
  Create file .env (Use Mysql)
  ```
  PORT=8080
SECRET='ThisIsASecretKey'
DATABASE_HOST='localhost'
DATABASE_USERNAME='root'
DATABASE_PASSWORD=''
DATABASE_NAME='ideaapp'

```
Config file ormconfig.js
```
  type: 'mysql',
  host: process.env.DATABASE_HOST,
  port: 3306,
  ```
  ```
    npm install

  ```
  ```
  npm start
  ```
