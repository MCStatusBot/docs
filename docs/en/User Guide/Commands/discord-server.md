# /discord-server
This is where everything related to managing settings on your Discord server lives. You can create message and channel watchers, customize how the bot responds in your server, and more.

## /discord-server overview
This is where you can get an overview of your Discord server settings and then edit them.

To use this command, you must select the "category" option. There are a few categories available, and here is what each of them are:

### Basics
Here, you can get an overview of the number of channel watchers, message watchers, and Minecraft servers you have added to your Discord server. You can also view your current plan and a preview of your channel watchers channel text, and customize it.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090458273909575680/Screenshot_2023-03-29_at_03.11.48.png)


### Status Embed
Here, you can get an overview of your status embed settings. This embed is displayed when a user uses the [/ping] command or when a message watcher is set up.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090459020894163004/Screenshot_2023-03-29_at_03.14.47.png)


### Graph Colors
This shows you the hexadecimal color value of the colors of the graph that is displayed under all your chart embeds.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090459439074652181/Screenshot_2023-03-29_at_03.16.26.png)


### Chart Uptime Embed, Chart Playersonline Embed, Chart Most Active Embed
These settings are basically all the same, the only difference is what chart they affect.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090459920815628308/Screenshot_2023-03-29_at_03.18.21.png)


### Common errors:

<br>


## /discord-server link-mcserver
This command allows you to connect your already created Minecraft server to your Discord server.
Initially, it may seem a bit confusing, but it's actually straightforward to use. When you use the [/minecraft-server add]() command, the Minecraft server is automatically added to the Discord server where the command was executed, provided the user has the necessary permissions. The server is "pinged" at regular intervals to generate logs. However, let's say it's your friend's or favorite YouTuber's server, and you'd like to see its status and other details in your Discord server. In that case, you'll have to link it. This linking process is to make it easier to add a channel or message watcher and display the Minecraft server in a dropdown menu for other commands, making it simpler for you and your users.


![]()

### Common errors:

<br>


## /discord-server remove-mcserver
This command allows you to unlink a Minecraft server that is already connected to your Discord server. Please note that this does not delete the Minecraft server from the bot. If you want to delete the server completely, you need to use the /minecraft-server view command and then click on the delete button.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090465963813638224/Screenshot_2023-03-29_at_03.42.22.png)

To remove a server, select the dropdown menu where it says "Select A Mc Server," then find the name of the Minecraft server you would like to remove and click on it.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090466558381392042/Screenshot_2023-03-29_at_03.44.44.png)

### Common errors:

<br>


## /discord-server create-channel-watcher
this command will create a channel based watcher, what is a "channel watcher"? its a simple term we give the channel that automatically updates its name based on the minecraft server's status

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090468265521852436/Screenshot_2023-03-29_at_03.51.29.png)

### Common errors:

you get a "Can't Create Another Channel watcher" responce, this can be cause if:

- there are no minecraft servers linked to your discord server

- you have simply added a channel watcher for each and ever minecraft server linked to your discord server.