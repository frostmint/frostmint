![Frostmint](/assets/img/img-banner.png)
## Python Bot Example
```
# install python module first
# python.org
# after that, type in cmd:
# pip install discord
# done

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
client.run(TOKEN)
```
### Before you started (python)
[Download Python](https://github.com/frostmint/dl)
```
Microsoft Windows [Version 10.0.19041.264]
(c) 2020 Microsoft Corporation. All rights reserved.

C:\> pip install discord
```
or just go to [https://discordpy.readthedocs.io/en/stable/api.html](https://discordpy.readthedocs.io/en/stable/api.html) to learn about discord-py
## Javascript Bot Example
```
/* install nodejs
https://nodejs.org/en/
open cmd, type "npm install discord.js"
done
*/

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

client.login(TOKEN)
```
### Before you started (javascript)
[Download NodeJS](https://github.com/frostmint/dl/)
```
Microsoft Windows [Version 10.0.19041.264]
(c) 2020 Microsoft Corporation. All rights reserved.

C:\> npm install discord.js
```
or just go to [discord.js.org/#/](https://discord.js.org) to learn more about discord-js
## Contact Me
lptechub78@gmail.com

## Repository
<a href="https://github.com/frostmint/db/blob/main/bot.py">Open original: bot.py</a>
<p> </p>
<a href="https://github.com/frostmint/db/blob/main/bot.js">Open original: bot.js</a>
<p> </p>
<a href="https://github.com/frostmint/db/">Open repository: db</a>
<p> </p>
