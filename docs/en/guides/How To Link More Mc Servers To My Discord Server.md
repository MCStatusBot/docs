# How To Link More Mc Servers To My Discord Server


## Introduction
first what is the difference between adding a mc server to the bot (/minecraft-server add) and linking a mc server to a discord server (/discord-server link-mcserver) and why do you need to add a server to the bot before linking it to your discord server.

Adding a Server to the Bot: This registers a Minecraft server with the bot, making it aware of the server's existence. When you add a server to the bot, you provide details like the server’s IP address, name, A Description, and more details, think of it as introducing the bot to the server. The bot now knows where the server is and can start gathering information br pining it, but it hasn’t yet associated that server with any particular Discord server.

Linking a Minecraft server to a Discord server: This command associates a previously registered Minecraft server with a specific Discord server, telling it hay we like these server(s) please show us their details.

<br>

## Setup

first you will need the Minecraft servers id, you can find this by doing `/minecraft-server view id:\<mc server ip\>` replacing <mc server ip> with the minecraft servers ip address or if you own this server and it has not been previouly added to the bot please first use the `/minecraft-server add` command

now you have the id of that minecraft server you can then do `/discord-server link-mcserver mc-server-id:<ID>` replacing <ID> with the mc server's id.


