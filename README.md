<h1 align="center">github/frostmint</h1>



![Frostmint](/classid-img_banner.png)
## Python Bot Example
```
import discord
import os

client = discord.Client()

@client.event
async def on_ready():
    print('We have logged in as {0.user}'.format(client))

@client.event
async def on_message(message):
    if message.author == client.user:
        return

    if message.content.startswith('$hello'):
        await message.channel.send('Hello!')
client.run('TOKEN')
```
## Javascript Bot Example
```
const Discord = require("discord.js")
const client = new Discord.Client()

client.on("ready", () => {
  console.log(`Logged in as ${client.user.tag}!`)
})

client.on("message", msg => {
  if (msg.content === "ping") {
    msg.reply("pong");
  }
})

client.login('TOKEN');
```

## Before start to use it
### Java script
Download the module first
 
[**```↗️Download Nodejs in frostmint repository```**](https://github.com/frostmint/dl/)
 
[**```↗️Download Nodejs in official website```**](https://nodejs.org)
 
Then, open **cmd.exe/Terminal**, and type this:
```
npm install discord.js
```
or just go to [```discord.js.org/#/```](https://discord.js.org) to learn more about discord-js
### Python
[**```↗️Download Python in frostmint repository```**](https://github.com/frostmint/dl)
 
[**```↗️Download Python in official website```**](https://python.org)
 
Then, open **cmd.exe/Terminal** and type this:
```
pip install discord
```
or just go to [```https://discordpy.readthedocs.io/en/stable/api.html```](https://discordpy.readthedocs.io/en/stable/api.html) to learn about discord-py
## Repository
[**```↗️Open original: bot.py```**](https://github.com/frostmint/db/blob/main/bot.py)
 
[**```↗️Open original: bot.js```**](https://github.com/frostmint/db/blob/main/bot.js)
 
[**```↗️Open main repository: db```**](https://github.com/frostmint/db)

## Tools for programmer (Text editor)
[**```Visual Studio Code```**](https://code.visualstudio.com)
 
[**```Visual Studio IDE```**](https://visualstudio.com)
 
[**```Atom Text Editor```**](https://atom.io)
 
[**```Notepad++```**](https://notepad-plus-plus.org)

## Project
- The Boring Project of HTML
