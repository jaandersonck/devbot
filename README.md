# devbot 
Devbot is a multipurpose Discord bot with various features. It is written entirely in javascript. See the update changelog at [CHANGELOG.md](https://github.com/alacriware/devbot/blob/canary/CHANGELOG.md).

# deploying with nodejs
Devbot can also be deployed on nodejs, by cloning the source code and running index.js with the process manager of your choice. 

Sensitive bot configuration should be stored in a `.env` file in the project root. The file should be formatted as below:
```
HOST=localhost
DB=devbot
DB_USER=dbuser
DB_PASSWORD=dbpass
TOKEN=BOTTOKEN
operators=0,0
clientId=0
```
