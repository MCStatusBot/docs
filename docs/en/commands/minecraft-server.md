# /minecraft-server

This command allows you to access all the settings related to your Minecraft server(s).

## /minecraft-server add
The `/minecraft-server add` command is used to add a new Minecraft server to the bot, allowing us to ping it and display it in our server list on the MCStatusBot website (only if your server is set to public).

To use this command, type `/minecraft-server add` and wait for the form to show up. If you don't receive a form, you will need to update your Discord client. The form contains the following fields (names ending with * are required):

 - "YOUR SERVER'S IP"* - This is the IP address or domain that you and your members use to connect to your server. It can look like 152.160.146.196, snekmc.schost.us, or 152.160.146.194:25567 (note that the number after the : is your server's port).

 - "YOUR SERVER'S ALT IPS" - These are alternative IP addresses/domains your server may have, separated by a comma (,) or space. For example, the address you would use to connect to my server, SnekMC, is snekmc.schost.us, but you can also connect to it using 152.160.146.198, so I would enter that here. This field is required to prevent others from accidentally duplicating your server.

 - "YOUR SERVER'S NAME"* - This is the name you would give your server, up to 50 characters in length. For example, my Minecraft server, snekmc.schost.us, is called "SnekMC".

 - "YOUR SERVER'S DESCRIPTION" - This will be a short description of what your server is about.

 - "YOUR SERVER TYPE"* - This is the type of server you have. If you play on PC (Linux, macOS, Windows), it will be Java. If you play on mobile, console, or Minecraft Windows 10 edition, then it will be Bedrock.

 - "YOUR SERVER'S TIMEZONE"* - This is the timezone of where your server is located. You can get a list here: https://docs.mcstatusbot.site/tz. For example, snekmc.schost.us is hosted by Snakecraft Hosting on their Michigan server, so I would enter "US/Michigan" exactly as it is, with no spaces and the capital letters in the right place.

Once you click submit and fill in all the information correctly, your server will be pinged and added to the Discord server you ran the command in, if you have permission to do so. 

![](https://cdn.discordapp.com/attachments/1086041829998329856/1086042251144216586/Screenshot_2023-03-16_at_21.43.43.png)

If you think someone is trying to impersonate your server, please report it.

### Common errors:
 - Minecraft Server Exists
   - This server has already been added. To verify that you own it, type `/minecraft-server view` and use the IP or ID of the server, and see if the username under owner is yours. If not, don't worry - see [recover my Minecraft server]().
<br>


## /minecraft-server list
list all the minecraft servers you own and have access to

there is one option `my-servers-only` setting this to ture will only show servers you own

![]()

## /minecraft-server view

view one of your minecraft servers and edit its settings 
this command takes on option `id` this can either be your minecraft servers id or ip.

![](https://cdn.discordapp.com/attachments/1086041829998329856/1086066854499450910/Screenshot_2023-03-16_at_23.21.52.png)