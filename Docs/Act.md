# Act Help

This cog makes all commands, e.g. [p]fluff, into valid commands if<br/>you command the bot to act on a user, e.g. [p]fluff [botname].

# actset
 - Usage: `[p]actset `
 - Restricted to: `ADMIN`

Configure various settings for the act cog.

## actset embed
 - Usage: `[p]actset embed `
 - Restricted to: `ADMIN`

Manage tenor embed settings for this cog.

## actset ignore
 - Usage: `[p]actset ignore <command> `
 - Restricted to: `ADMIN`
 - Checks: `server_only_without_subcommand`

Ignore or unignore the specified action.<br/><br/>The bot will no longer respond to these actions.

### actset ignore global
 - Usage: `[p]actset ignore global <command> `
 - Restricted to: `BOT_OWNER`

Globally ignore or unignore the specified action.<br/><br/>The bot will no longer respond to these actions.

## actset customize
 - Usage: `[p]actset customize <command> [response] `
 - Restricted to: `ADMIN`
 - Aliases: `custom and customise`
 - Checks: `server_only_without_subcommand`

Customize the response to an action.<br/><br/>You can use {0} or {user} to dynamically replace with the specified target of the action.<br/>Formats like {0.name} or {0.mention} can also be used.

### actset customize global
 - Usage: `[p]actset customize global <command> [response] `
 - Restricted to: `BOT_OWNER`

Globally customize the response to an action.<br/><br/>You can use {0} or {user} to dynamically replace with the specified target of the action.<br/>Formats like {0.name} or {0.mention} can also be used.

## actset tenorkey
 - Usage: `[p]actset tenorkey `
 - Restricted to: `BOT_OWNER`

Sets a Tenor GIF API key to enable reaction gifs with act commands.<br/><br/>You can obtain a key from here: https://tenor.com/developer/dashboard

