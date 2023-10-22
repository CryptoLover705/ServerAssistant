# BanCheck Help

Look up users on various ban lists.<br/><br/>This cog allows server admins to check their members against multiple external ban lists.<br/>It can also automatically check new members that join the server,<br/>and optionally ban them if they appear in a list.<br/><br/>For a quick rundown on how to get started with this cog,<br/>check out [the readme](https://github.com/PhasecoreX/PCXCogs/tree/master/bancheck/README.md)

# banchecksetglobal
 - Usage: `[p]banchecksetglobal `
 - Restricted to: `BOT_OWNER`

Configure global BanCheck settings.<br/><br/>For a quick rundown on how to get started with this cog,<br/>check out [the readme](https://github.com/PhasecoreX/PCXCogs/tree/master/bancheck/README.md)

## banchecksetglobal settings
 - Usage: `[p]banchecksetglobal settings `

Display current settings.

## banchecksetglobal api
 - Usage: `[p]banchecksetglobal api <service> [api_key=None] `

Set (or delete) an API key for a global service.<br/><br/>Behind the scenes, this is the same as `[p]set api <service> api_key <your_api_key_here>`

# bancheckset
 - Usage: `[p]bancheckset `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Configure BanCheck for this server.<br/><br/>For a quick rundown on how to get started with this cog,<br/>check out [the readme](https://github.com/PhasecoreX/PCXCogs/tree/master/bancheck/README.md)

## bancheckset autoban
 - Usage: `[p]bancheckset autoban `

Manage which services are allowed to ban users automatically.

### bancheckset autoban enable
 - Usage: `[p]bancheckset autoban enable <service> `

Enable a service to ban users automatically.

### bancheckset autoban disable
 - Usage: `[p]bancheckset autoban disable <service> `

Disable a service from banning users automatically.

## bancheckset service
 - Usage: `[p]bancheckset service `

Manage the services BanCheck will use to lookup users.

### bancheckset service api
 - Usage: `[p]bancheckset service api <service> [api_key=None] `

Set (or delete) an API key for a service.

### bancheckset service settings
 - Usage: `[p]bancheckset service settings `

Display current settings.

### bancheckset service disable
 - Usage: `[p]bancheckset service disable <service> `

Disable a service.

### bancheckset service enable
 - Usage: `[p]bancheckset service enable <service> `

Enable a service.

## bancheckset autocheck
 - Usage: `[p]bancheckset autocheck `

Automatically perform BanChecks on new users.

### bancheckset autocheck disable
 - Usage: `[p]bancheckset autocheck disable `

Disable automatically checking new users against ban lists.

### bancheckset autocheck set
 - Usage: `[p]bancheckset autocheck set [channel=None] `

Set the channel you want AutoCheck notifications to go to.

## bancheckset settings
 - Usage: `[p]bancheckset settings `

Display current settings.

# bancheck
 - Usage: `[p]bancheck [member=None] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Check if user is on a ban list.

