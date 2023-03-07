# sitemap

The website sitemap this is mostly a dev reference but you may find it helpfull.

If your looking for the api docs please see https://api-docs.mcstatusbot.site/ and please do not attempt to use these endpoints they can be unreliable for your application.

<br>

## / 
> `GET`

the home the main page

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
ref | false | refrance id for analytics



## /login
> `GET`

redirects to discords OAuth2 portal

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
ref | false | refrance id for analytics



## /login/flow
> `GET`
where you get redirected back from discord

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
ref | false | refrance id for analytics
code | true | the code that lets us see account details


## /dashboard
> `GET`
the dashboard where you can see your account info, disord servers, and minecraft servers and manage them.

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
ref | false | refrance id for analytics



## /servers
> `GET`
lists your minecraft servers

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
ref | false | refrance id for analytics

## /servers/<server id>
> `GET`
gets information on your sererevrrvv

### Parameters

Parameter | Required | Description
--------- | --------- | -----------
ref | false | refrance id for analytics