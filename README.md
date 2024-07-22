# Notes App with Nodejs and Mysql

Notes App is a Multi Page Application using Nodejs and Mysql. The purpose of this web application is just to be an example for beginners.

![](docs/screenshot2.png)
![](docs/screenshot.png)


### Manual Installation

Node version = 18.19

MySQL version = 5.7

```
mysql -u MYUSR "-pMYPASSWORD" < ./database/db.sql # create database
npm install
npm run build
npm start
```

## File Structure

- database, it the folder with all the sql queries, you can use to recreate the database for this application
- src, it's all the code for the Backend and Frontend Application
- docs

## Environment Variables

- PORT
- DATABASE_HOST
- DATABASE_USER
- DATABASE_PASSWORD
- DATABASE_NAME
- DATABASE_PORT
- SECRET

Now you can visit http://localhost:4000

## Tools

- Nodejs
- Mysql
- Babel
- Docker
