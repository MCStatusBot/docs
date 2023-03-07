# Commands

## /setup
Basically does what /minecraft-server add does but automatically adds the mc server to your discord server.

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------

<br>

## /minecraft-server

### add
Adds a Minecraft server to the bot and gives you a id/code so you may add it to up to 10 discord servers, if discord server you are doing this command in doesn`t already have a Minecraft server added this one will be added and set as the default server.

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------


### view
view the details for a minecraft server

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | true | Your minecraft servers id.


### list
list all your minecraft server

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------


<br>

## /link-mc-server
Links your Minecraft server to the discord server you are running this command in.

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | true | Your minecraft servers id that was given to you when you added it you can also find this id with the `/my-mc-servers` command and on the [dashboard](https://dash.mcstatusbot.site/my-mc-servers).

<br>

## /channel-status
setup or disable channel status for a minecraft server



### enable
enables channel status

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | true | Your minecraft servers id that was given to you when you added it you can also find this id with the `/my-mc-servers` command and on the [dashboard](https://dash.mcstatusbot.site/my-mc-servers).
enable-playersonline | true | should we have another channel display how many players are online

### disable
disables channel status

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | true | Your minecraft servers id that was given to you when you added it you can also find this id with the `/my-mc-servers` command and on the [dashboard](https://dash.mcstatusbot.site/my-mc-servers).


<br>

## /message-status
setup or disable message status for a minecraft server



### enable
enables message status

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | true | Your minecraft servers id that was given to you when you added it you can also find this id with the `/my-mc-servers` command and on the [dashboard](https://dash.mcstatusbot.site/my-mc-servers).
channel | true | the channel where you want the message to be sent

### disable
disables message status

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | true | Your minecraft servers id that was given to you when you added it you can also find this id with the `/my-mc-servers` command and on the [dashboard](https://dash.mcstatusbot.site/my-mc-servers).


<br>

## /set-language

Set your language 

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
lang | true | The language code see https://docs.mcstatus/lang for codes.


<br>

## /chart

Get a chart of your minecraft servers statistics


### uptime
see a custom graph of a mcservers uptime over time

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | false | Your minecraft servers id domain or ip:port, if you dont give one it will use the discord servers default mc server.


### playersonline
see a custom graph of playersonline over time

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | false | Your minecraft servers id domain or ip:port, if you dont give one it will use the discord servers default mc server.

### mostactive
see a custom graph of the most active players.

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | false | Your minecraft servers id domain or ip:port, if you dont give one it will use the discord servers default mc server.


<br>

## /discord-server

### settings
see all your current settings for things todo with your discord server

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------

### edit-chart-grap
edit your charts graph colours

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------

### edit-embed-uptime
edit your uptime embed

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------

### edit-embed-playersonline
edit your playersonline embed

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------

### edit-embed-mostactive
edit your mostactive embed

#### Parameters

Parameter | Required | Description
--------- | --------- | -----------

<br>

## /cool-stats

Get cool stats of the bot uptime cpu ram, last ping details etc
