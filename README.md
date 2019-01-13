# Suta-bot

{
  "name": "Octo-bot",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "Octogone",
  "license": "ISC",
  "dependencies": {
    "discord.js": "^11.4.2",
    "express": "^4.16.4",
    "ffmpeg": "0.0.4",
    "figlet": "^1.2.1",
    "mathjs": "^5.2.2",
    "meme-maker": "^2.1.2",
    "moment": "^2.22.2",
    "nekos.life": "^1.1.5",
    "node-gyp": "^3.8.0",
    "opusscript": "0.0.6",
    "os-utils": "0.0.14",
    "rebuild": "^0.1.2",
    "redis-session": "^0.1.0",
    "youtube-search": "^1.1.3",
    "yt-search": "^0.3.0",
    "ytdl-core": "^0.24.0"
  },
  "devDependencies": {},
  "description": ""
}

const Discord = require('discord.js');
const client = new Discord.Client();

console.log('connexion................')

client.on('ready', () => {

console.log(`connected as ${client.user.tag}')

}

client.login(process.env
TOKEN) 
