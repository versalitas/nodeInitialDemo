# CHAT with Socket.io

Instructions:
Clone repository and make sure that npm is installed.

Initialize terminal from inside the project folder.
Install node modules.

```
npm install

```
Convert .env.example to .env and adapt variables to current environment.

Run server with

```
npm start
```

or in developer mode

```
npm run dev
```
### SERVER

Server runs with express and http modules.

### SOCKET.io

The main idea behind Socket.IO is to send 
and receive any events with any data you want.

Basics:
https://socket.io/get-started/chat

Rooms:
https://socket.io/docs/v3/rooms/
https://www.geeksforgeeks.org/how-to-manage-users-in-socket-io-in-node-js/

Socket.io cheatsheet:
https://socket.io/docs/v4/emit-cheatsheet/#server-side

### MONGOOSE:

MongoDB deployed as persistance with mongoose as ORM.

https://mongoosejs.com/

### FRONT END:

TBD
GENERAL (stitching together a chat):
https://stackfame.com/mongodb-chat-schema-mongoose-chat-schema-chat-application
### Project Structure

Main structure of node.js project. 

- <b>app</b>:
    - <b>controllers</b> 
    - <b>middleware</b>
    - <b>models</b>
    - <b>routes</b>
    - <b>utils</b>
    - <b>.env.example</b>
    - <b>app.js</b>. Entry point.
- <b>.env</b>. Environment descriptor. See [dotenv doc](https://www.npmjs.com/package/dotenv).
- <b>.eslintrc</b>. Linter JS, static code analyzer. See [EsLint Docs](https://eslint.org/docs/user-guide/configuring/configuration-files).
- <b>.prettierignore</b>. Code formatter. See [Prettier Config](https://prettier.io/docs/en/configuration.html) and [Prettier Ignore](https://prettier.io/docs/en/ignore.html).
- <b>.ecosystem.config.js</b>. Process Manage at runtime. See [PM2 Docs](https://pm2.keymetrics.io/).
- <b>package.json</b>.










