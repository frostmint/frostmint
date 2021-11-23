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

## Before start to use it
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
