## Hi, This is faris
### Python Bot Example
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
client.run(os.getenv('TOKEN'))
```
### Javascript Bot Example
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

client.login(process.env.TOKEN)
```
### Contact Me
lptechub78@gmail.com
