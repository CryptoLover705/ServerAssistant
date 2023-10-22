# ClearChannel Help

A cog to delete ALL messages of a channel!<br/><br/>⚠ The channel will be cloned, and then **deleted**.

# clearchannel (Hybrid Command)
 - Usage: `[p]clearchannel [confirmation=False] `
 - Slash Usage: `/clearchannel [confirmation=False] `
 - Restricted to: `GUILD_OWNER`
 - Checks: `server_only`

Delete ALL messages from the current channel by duplicating it and then deleting it.<br/><br/>For security reasons, only the server owner and the bot owner can use the command. Use the "permissions" cog for more options.<br/>⚠ The channel will be cloned, and then **deleted**.

# setclearchannel (Hybrid Command)
 - Usage: `[p]setclearchannel `
 - Slash Usage: `/setclearchannel `
 - Restricted to: `GUILD_OWNER`
 - Aliases: `clearchannelset`
 - Checks: `server_only`

Configure ClearChannel for your server.

## setclearchannel modalconfig (Hybrid Command)
 - Usage: `[p]setclearchannel modalconfig [confirmation=False] `
 - Slash Usage: `/setclearchannel modalconfig [confirmation=False] `
 - Aliases: `configmodal`
 - Checks: `server_only`

Set all settings for the cog with a Discord Modal.

## setclearchannel resetsetting (Hybrid Command)
 - Usage: `[p]setclearchannel resetsetting <setting> `
 - Slash Usage: `/setclearchannel resetsetting <setting> `
 - Checks: `server_only`

Reset a setting.

## setclearchannel channeldelete (Hybrid Command)
 - Usage: `[p]setclearchannel channeldelete <value> `
 - Slash Usage: `/setclearchannel channeldelete <value> `
 - Checks: `server_only`

If this option is disabled, the bot will not delete the original channel: it will duplicate it as normal, but move it to the end of the server's channel list.<br/><br/>Default value: True<br/>Dev: <class 'bool'>

## setclearchannel custommessage (Hybrid Command)
 - Usage: `[p]setclearchannel custommessage <value> `
 - Slash Usage: `/setclearchannel custommessage <value> `
 - Checks: `server_only`

Specify a custom message to be sent from the link of another message or a json (https://discohook.org/ for example).<br/><br/>Use `{name}` or `{icon_url}` for the user.<br/><br/>Default value: ...<br/>Dev: <class 'AAA3A_utils.settings.CustomMessageConverter'>

## setclearchannel dmauthor (Hybrid Command)
 - Usage: `[p]setclearchannel dmauthor <value> `
 - Slash Usage: `/setclearchannel dmauthor <value> `
 - Checks: `server_only`

If this option is enabled, the bot will try to send a dm to the author of the order to confirm that everything went well.<br/><br/>Default value: ...<br/>Dev: <class 'bool'>

## setclearchannel showsettings (Hybrid Command)
 - Usage: `[p]setclearchannel showsettings [with_dev=False] `
 - Slash Usage: `/setclearchannel showsettings [with_dev=False] `
 - Checks: `server_only`

Show all settings for the cog with defaults and values.

## setclearchannel firstmessage (Hybrid Command)
 - Usage: `[p]setclearchannel firstmessage <value> `
 - Slash Usage: `/setclearchannel firstmessage <value> `
 - Checks: `server_only`

If this option is enabled, the bot will send a message to the emptied channel to inform that it has been emptied.<br/><br/>Default value: True<br/>Dev: <class 'bool'>

