# Starboard Help

Create a starboard to *pin* those special comments indefinitely

# starboard
 - Usage: `[p]starboard `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Commands for managing the starboard

## starboard threshold
 - Usage: `[p]starboard threshold <starboard> <threshold> `

Set the threshold before posting to the starboard<br/><br/>`<name>` is the name of the starboard to change the threshold for<br/>`<threshold>` must be a number of reactions before a post gets<br/>moved to the starboard

## starboard blocklist
 - Usage: `[p]starboard blocklist `
 - Aliases: `blacklist`

Add/Remove channels/roles from the blocklist

### starboard blocklist remove
 - Usage: `[p]starboard blocklist remove <starboard> <channel_or_role> `

Remove a channel to the starboard blocklist<br/><br/>`<name>` is the name of the starboard to adjust<br/>`<channel_or_role>` is the channel or role you would like to remove from the blocklist

### starboard blocklist add
 - Usage: `[p]starboard blocklist add <starboard> <channel_or_role> `

Add a channel to the starboard blocklist<br/><br/>`<name>` is the name of the starboard to adjust<br/>`<channel_or_role>` is the channel or role you would like to add to the blocklist

## starboard emoji
 - Usage: `[p]starboard emoji <starboard> <emoji> `

Set the emoji for the starboard<br/><br/>`<name>` is the name of the starboard to change the emoji for<br/>`<emoji>` must be an emoji on the server or a default emoji

## starboard create
 - Usage: `[p]starboard create <name> [channel=None] [emoji=⭐] `
 - Aliases: `add`

Create a starboard on this server<br/><br/>`<name>` is the name for the starboard and will be lowercase only<br/>`[channel]` is the channel where posts will be made defaults to current channel<br/>`[emoji=⭐]` is the emoji that will be used to add to the starboard defaults to ⭐

## starboard cleanup
 - Usage: `[p]starboard cleanup `

Cleanup stored deleted channels or roles in the blocklist/allowlist

## starboard inherit
 - Usage: `[p]starboard inherit <starboard> `

Set whether to inherit the parent channels blocklist/allowlist settings.<br/>If this is enabled then starred messages in threads and forum channels<br/>will be filtered based on their parent channels blocklist/allowlist settings.<br/>e.g. if a message is starred in a thread and the parent channel is in the blocklist<br/>the message will not be starred.<br/><br/>`<name>` is the name of the starboard to adjust

## starboard allowlist
 - Usage: `[p]starboard allowlist `
 - Aliases: `whitelist`

Add/Remove channels/roles from the allowlist

### starboard allowlist add
 - Usage: `[p]starboard allowlist add <starboard> <channel_or_role> `

Add a channel to the starboard allowlist<br/><br/>`<name>` is the name of the starboard to adjust<br/>`<channel_or_role>` is the channel or role you would like to add to the allowlist

### starboard allowlist remove
 - Usage: `[p]starboard allowlist remove <starboard> <channel_or_role> `

Remove a channel to the starboard allowlist<br/><br/>`<name>` is the name of the starboard to adjust<br/>`<channel_or_role>` is the channel or role you would like to remove from the allowlist

## starboard channel
 - Usage: `[p]starboard channel <starboard> <channel> `
 - Aliases: `channels`

Change the channel that the starboard gets posted to<br/><br/>`<name>` is the name of the starboard to adjust<br/>`<channel>` The channel of the starboard.

## starboard colour
 - Usage: `[p]starboard colour <starboard> <colour> `
 - Aliases: `color`

Change the default colour for a starboard<br/><br/>`<name>` is the name of the starboard to toggle<br/>`<colour>` The colour to use for the starboard embed<br/>This can be a hexcode or integer for colour or `author/member/user` to use<br/>the original posters colour or `bot` to use the bots colour.<br/>Colour also accepts names from<br/>[discord.py](https://discordpy.readthedocs.io/en/latest/api.html#colour)

## starboard purge
 - Usage: `[p]starboard purge [time] `
 - Restricted to: `BOT_OWNER`

Define how long to keep message ID's for every starboard<br/><br/>`<time>` is the number of days or weeks you want to keep starboard messages for.<br/><br/>e.g. `[p]starboard purge 2 weeks`

## starboard remove
 - Usage: `[p]starboard remove <starboard> `
 - Aliases: `delete and del`

Remove a starboard from the server<br/><br/>`<name>` is the name for the starboard and will be lowercase only

## starboard toggle
 - Usage: `[p]starboard toggle <starboard> `

Toggle a starboard on/off<br/><br/>`<name>` is the name of the starboard to toggle

## starboard info
 - Usage: `[p]starboard info `
 - Aliases: `list`

Display info on starboards setup on the server.

## starboard selfstar
 - Usage: `[p]starboard selfstar <starboard> `

Toggle whether or not a user can star their own post<br/><br/>`<name>` is the name of the starboard to toggle

## starboard autostar
 - Usage: `[p]starboard autostar <starboard> `

Toggle whether or not the bot will add the emoji automatically to the starboard message.<br/><br/>`<name>` is the name of the starboard to toggle

# star
 - Usage: `[p]star <starboard> <message> `
 - Checks: `server_only`

Manually star a message<br/><br/>`<name>` is the name of the starboard you would like to add the message to<br/>`<message>` is the message ID, `channel_id-message_id`, or a message link<br/>of the message you want to star

# unstar
 - Usage: `[p]unstar <starboard> <message> `
 - Checks: `server_only`

Manually unstar a message<br/><br/>`<name>` is the name of the starboard you would like to add the message to<br/>`<message>` is the message ID, `channe_id-message_id`, or a message link<br/>of the message you want to unstar

