# LadderJS demo app


This demo app shows you how to bootstrap a LadderJS (the NodeJS MVC framework) app. It uses `babel-node` and `nodemon`.
You can fork this repository as a boilerplate for your projects.

## Installation

First, create a Postgre SQL database:
```console
$ createdb <DATABASE>
```

Then, add a `.env` file at the root of your project:
**/.env**
```
# The database connection string
DATABASE_URL=postgres://<USER>:<PASSWORD>@<DATABASE>
# Enable the Sequelize logging, disabled by default
DB_LOGGING=true
```

```console
$ npm install
$ yarn dev
or
$ npm run dev
```