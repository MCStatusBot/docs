# /discord-server

This command manages your Discord server settings, including creating message and channel watchers and customizing how the bot responds in your server.

<br>


## /discord-server overview

This command gives you an overview of your Discord server settings and allows you to edit them. To use this command, select the "category" option. There are several categories available:


#### Basics

This category shows the number of channel watchers, message watchers, and Minecraft servers you've added to your Discord server. You can also view your current plan, customize the channel watchers' text, and preview it.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090458273909575680/Screenshot_2023-03-29_at_03.11.48.png)


#### Status Embed

Here, you can see your status embed settings, which appear when someone uses the [/ping] command or when a message watcher is set up.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090459020894163004/Screenshot_2023-03-29_at_03.14.47.png)


#### Graph Colors

This category shows you the hexadecimal color value of the colors of the graph that is displayed under all your chart embeds.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090459439074652181/Screenshot_2023-03-29_at_03.16.26.png)


#### Chart uptime Embed, Chart playersonline Embed, Chart mostactive Embed

These settings are all similar, except for which chart they affect.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090459920815628308/Screenshot_2023-03-29_at_03.18.21.png)


<br>


## /discord-server link-mcserver

This command links your Minecraft server to your Discord server. It's easy to use. When you use the /minecraft-server add command, the Minecraft server is automatically added to the Discord server where the command was executed. However, let's say you want to see another server's status and details in your Discord server. In that case, you'll need to link it to add a channel or message watcher and display the Minecraft server in a dropdown menu for other commands.

<br>


## /discord-server remove-mcserver

This command removes the link between your Minecraft server and your Discord server. Please note that this doesn't delete the Minecraft server from the bot. To delete the server completely, use the /minecraft-server view command and then click on the delete button.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090465963813638224/Screenshot_2023-03-29_at_03.42.22.png)

To remove a server, select the dropdown menu where it says "Select A Mc Server," then find the name of the Minecraft server you want to remove and click on it.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090466558381392042/Screenshot_2023-03-29_at_03.44.44.png)

<br>


## /discord-server create-channel-watcher

This command creates a channel watcher that updates its name based on the Minecraft server's status.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090468265521852436/Screenshot_2023-03-29_at_03.51.29.png)


### Common errors:

- you get a "Can't Create Another Channel watcher" responce, this can be cause if:
  - You have already added a channel watcher for each Minecraft server linked to your Discord server.
  - You have yet to link a Mnecraft server to your discord server.

<br>


## /discord-server remove-channel-watcher

This command removes a channel watcher you have set up. After running the slash command, select the Minecraft server's channel watcher you want to remove using the dropdown menu, and it will attempt to remove the channel.


![](https://cdn.discordapp.com/attachments/1086041829998329856/1090601592685854780/Screenshot_2023-03-29_at_12.41.18.png)
![](https://cdn.discordapp.com/attachments/1086041829998329856/1090601655638163466/Screenshot_2023-03-29_at_12.41.33.png)

<br>


## /discord-server create-message-watcher

This command allows you to create a message watcher that will send you messages whenever something specific happens in your Minecraft server. For example, you can receive a message when a player joins or leaves the server, or when the server starts or stops.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1090617384076836986/Screenshot_2023-03-29_at_13.44.01.png)

### Common errors:

- you get a "Can't Create Another Message watcher" responce, this can be cause if:
  - You have already added a channel watcher for each Minecraft server linked to your Discord server.
  - You have yet to link a Mnecraft server to your discord server.


<br>


## /discord-server remove-message-watcher

This command allows you to remove a message watcher that you have previously set up. You will be asked which Minecraft server's message watcher you would like to remove using the dropdown menu and use it to select from the list of Minecraft servers that have an added message watcher. Once you select one, it will attempt to remove the message watcher and confirm with you.


![](https://cdn.discordapp.com/attachments/1086041829998329856/1090601592685854780/Screenshot_2023-03-29_at_12.41.18.png)
![](https://cdn.discordapp.com/attachments/1086041829998329856/1090617871203311766/Screenshot_2023-03-29_at_13.45.56.png)
