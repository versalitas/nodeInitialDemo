Install npm.
Convert .env.example to .env and if necessary change port
Run server.

```
npm install
npm start
```
TASK: Game with two dice. If the sum of the roll adds up to 7 = win.
addPlayer: Player registers with unique name. Is assigned an id and register date. If no nome 
showScores: numRolls, scoreDice1, scoreDice2, totalScore winPercentage
deletePlayerScores
showPlayers: playerName, winPercentage, winMedian



ENDPOINTS

POST /players 
create player with unique name or anonymous, adds id and register date.

PUT /players/{id} 
modify player name

GET/players return list of alls Players with winPercentage

POST /games/{id}: player(id) rolls the dice
DELETE /games/{id}: delete all rolls of player
GET /games/{id}: list of all rounds of player (id)
GET /ranking: player ranking according to winPercentage, and winMedium
GET /ranking/loser: return Player with less winPercentage
GET /ranking/winner: return Player with best winPercentage


### Project Structure

Main structure of node.js project. Folders / files:

- <b>\_\_tests__</b>. Tests folder. See [Jest Docs](https://jestjs.io/es-ES/docs/configuration) and [Chai Docs](https://www.chaijs.com/)
- <b>app</b>:
    - <b>config</b>
    - <b>controllers</b>
    - <b>crons</b>
    - <b>middleware</b>
    - <b>models</b>
    - <b>routes</b>
    - <b>tmp</b>
    - <b>app.js</b>. Entry point.
- <b>.env</b>. Environment descriptor. See [dotenv doc](https://www.npmjs.com/package/dotenv).
- <b>.eslintrc</b>. Linter JS, static code analyzer. See [EsLint Docs](https://eslint.org/docs/user-guide/configuring/configuration-files).
- <b>.prettierignore</b>. Code formatter. See [Prettier Config](https://prettier.io/docs/en/configuration.html) and [Prettier Ignore](https://prettier.io/docs/en/ignore.html).
- <b>.ecosystem.config.js</b>. Process Manage at runtime. See [PM2 Docs](https://pm2.keymetrics.io/).
- <b>package.json</b>.

//sources

https://www.npmjs.com/package/sequelize
https://sequelize.org/docs/v6/core-concepts/model-basics/
https://javascript.plainenglish.io/save-time-learn-sequelize-in-7-mins-part-1-3e4fde67d037
https://betterprogramming.pub/an-introduction-to-sequelize-a-node-js-object-relational-mapper-orm-267a51c2d978




