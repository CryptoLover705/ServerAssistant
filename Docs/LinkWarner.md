# LinkWarner Help

Remove messages containing links and warn users for it.

# linkwarner
 - Usage: `[p]linkwarner `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Settings for LinkWarner cog.

## linkwarner showsettings
 - Usage: `[p]linkwarner showsettings `

Show settings for the current server.

## linkwarner state
 - Usage: `[p]linkwarner state <new_state> `

Set if LinkWarner should be enabled for this server.<br/><br/>If used without a setting, this will show the current state.

## linkwarner channel
 - Usage: `[p]linkwarner channel `

Channel-specific settings for LinkWarner.

### linkwarner channel unsetmessage
 - Usage: `[p]linkwarner channel unsetmessage <channel> `

Unset link warning message for provided channel.

### linkwarner channel setmessage
 - Usage: `[p]linkwarner channel setmessage <channel> <message> `

Set link warning message for provided channel.<br/><br/>Those fields will get replaced automatically:<br/>$mention - Mention the user who sent the message with a link<br/>$username - The user's display name<br/>$server - The name of the server

### linkwarner channel ignore
 - Usage: `[p]linkwarner channel ignore <channel> <new_state> `

Set if LinkWarner should ignore links in provided channel.

### linkwarner channel domains
 - Usage: `[p]linkwarner channel domains `

Configuration for allowed/disallowed domains in the specific channel.

#### linkwarner channel domains clear
 - Usage: `[p]linkwarner channel domains clear <channel> `

Clear domains from the domains list of the provided channel.

#### linkwarner channel domains add
 - Usage: `[p]linkwarner channel domains add <channel> <domains> `

Add domains to the domains list of the provided channel.<br/><br/>Note: The cog is using exact matching for domain names<br/>which means that domain names like youtube.com and www.youtube.com<br/>are treated as 2 different domains.<br/><br/>Example:<br/>`[p]linkwarner channel domains add #channel youtube.com discord.com`

#### linkwarner channel domains remove
 - Usage: `[p]linkwarner channel domains remove <channel> <domains> `
 - Aliases: `delete`

Remove domains from the domains list of the provided channel.<br/><br/>Example:<br/>`[p]linkwarner channel domains remove #channel youtube.com discord.com`

#### linkwarner channel domains setmode
 - Usage: `[p]linkwarner channel domains setmode <channel> <new_mode> `

Change current domains list mode.<br/><br/>Available modes:<br/>`0` - Inherit the server setting and use domains<br/>      from both server's and channel's domain list.<br/>`1` - Only domains on the channel's domains list can be sent.<br/>`2` - All domains can be sent except the ones on the channel's domains list.

### linkwarner channel showsettings
 - Usage: `[p]linkwarner channel showsettings <channel> `

Show settings for the given channel.

## linkwarner unsetmessage
 - Usage: `[p]linkwarner unsetmessage `

Unset link warning message.

## linkwarner domains
 - Usage: `[p]linkwarner domains `

Configuration for allowed/disallowed domains in the server.

### linkwarner domains remove
 - Usage: `[p]linkwarner domains remove <domains> `
 - Aliases: `delete`

Remove domains from the domains list.<br/><br/>Example:<br/>`[p]linkwarner domains remove youtube.com discord.com`

### linkwarner domains clear
 - Usage: `[p]linkwarner domains clear `

Clear domains from the domains list.

### linkwarner domains setmode
 - Usage: `[p]linkwarner domains setmode <new_mode> `

Change current domains list mode.<br/><br/>Available modes:<br/>`1` - Only domains on the domains list can be sent.<br/>`2` - All domains can be sent except the ones on the domains list.

### linkwarner domains add
 - Usage: `[p]linkwarner domains add <domains> `

Add domains to the domains list.<br/><br/>Note: The cog is using exact matching for domain names<br/>which means that domain names like youtube.com and www.youtube.com<br/>are treated as 2 different domains.<br/><br/>Example:<br/>`[p]linkwarner domains add google.com youtube.com`

## linkwarner usedms
 - Usage: `[p]linkwarner usedms <new_state> `

Set if LinkWarner should use DMs for warning messages.<br/><br/>Note: This is NOT recommended as the user might block the bot or all DMs<br/>from the server and the warning might not get sent to the offender at all.<br/>This also means that the bot is more likely to get ratelimited for repeatedly<br/>trying to DM the user when they spam links.<br/><br/>If you're trying to minimize spam that the warning messages cause,<br/>you should consider enabling delete delay instead.

## linkwarner setmessage
 - Usage: `[p]linkwarner setmessage <message> `

Set link warning message.<br/><br/>Those fields will get replaced automatically:<br/>$mention - Mention the user who sent the message with a link<br/>$username - The user's display name<br/>$server - The name of the server

## linkwarner excludedroles
 - Usage: `[p]linkwarner excludedroles `

Settings for roles that are excluded from getting filtered.

### linkwarner excludedroles add
 - Usage: `[p]linkwarner excludedroles add <roles> `

Add roles that will be excluded from getting filtered.

### linkwarner excludedroles remove
 - Usage: `[p]linkwarner excludedroles remove <roles> `
 - Aliases: `delete`

Remove roles that will be excluded from getting filtered.

## linkwarner deletedelay
 - Usage: `[p]linkwarner deletedelay <new_value> `

Set the delete delay (in seconds) for the warning message.<br/><br/>Use `[p]linkwarner deletedelay disable` to disable auto-deletion.<br/><br/>Note: This does not work when the warning messages are sent through DMs.

### linkwarner deletedelay disable
 - Usage: `[p]linkwarner deletedelay disable `

Disable auto-deletion of the warning messages.

