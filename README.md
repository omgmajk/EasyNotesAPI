# EasyNotesAPI
Simple NodeJS-CRUD REST API with ExpressJS and MongoDB

## Setup

You will need the following installed:
* Node
* NPM
* MongoDb
* Nodemon or pm2

`npm i`

Start with `node server.js` or `nodemon server.js` or `pm2 start server.js`.

API will be started on `http://localhost:3000` serving all routes.

Authentication is static, change bearer in `app/controllers/note.controller.js` or add your own auth. 

## Howto

You can find the tutorial for this app at The CalliCoder Blog

[https://www.callicoder.com/node-js-express-mongodb-restful-crud-api-tutorial/](https://www.callicoder.com/node-js-express-mongodb-restful-crud-api-tutorial/)