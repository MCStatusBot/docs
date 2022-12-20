# Commands

## /add-mc-server
Adds a Minecraft server to the bot and gives you a id/code so you may add it to up to 10 discord servers, if discord server you are doing this command in doesn`t already have a Minecraft server added this one will be added and set as the default server.

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
ip | true | Your minecraft servers ip.
port | true | Your minecraft servers port.
domain | false | Your minecraft servers domain.
name | true | The name of your minecraft server this wll show up in server lists on the website and status channels/messages.
server-type | true | Weather or not this server is a bedrock server or java server.
private | true | If set to yes your minecraft server wont appear in any server lists and can only be added to discord servers by you.
timezone | true | The timezone code of your server see [TimeZones](/#timezones) for a list of timezone codes.



<br>

## /link-mc-server
Links your Minecraft server to the discord server you are running this command in.

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
id | true | Your minecraft servrs id that was given to you when you added it you can also find this id with the `/my-mc-servers` command and on the [dashboard](https://dash.mcstatusbot.site/my-mc-servers).



<br>

## /my-mc-servers
Lists your added Minecraft servers and their ids.



<br>

## /discord-server-info

Gets information on your discord server. default minecraft server, added mc servers and more.



<br>

## /enable-message-status
Enables an auto updating Minecraft server status embed in your selected channel

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
mc-server-id | true | The id of the minecraft server you would like to enable the message status for.
channel | true | The channel you would like the status embed to be sent in either at the channel by typing `#channel-name` or by giving it`s id.



<br>

## /enable-channel-status

Enables an auto updating channel status 


<br>

## /set-language

Set your language 

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
lang | true | The language code.


<br>

## /chart

Get a chart of your minecraft servers statistics

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
chart-type | true | The type of chart you would like to see.
mc-server | false | The id ip:port or domain of the minecraft server.