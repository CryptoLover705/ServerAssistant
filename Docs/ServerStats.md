# ServerStats Help

Gather useful information about servers the bot is in<br/>A lot of commands are bot owner only

## server-stats avatar_look (Slash Command)
 - Usage: `/server-stats avatar_look [member] `
 - `member:` (Optional) …

Display a users avatar in chat

## server-stats emoji_look (Slash Command)
 - Usage: `/server-stats emoji_look <emoji> `
 - `emoji:` (Required) …

Post a large size emojis in chat

## server-stats botstats (Slash Command)
 - Usage: `/server-stats botstats `

Display stats about the bot

## server-stats topic (Slash Command)
 - Usage: `/server-stats topic [channel] [topic] `
 - `channel:` (Optional) …
 - `topic:` (Optional) …

Sets a specified channels topic

## server-stats channeledit
 - Usage: `[p]server-stats channeledit `

Modify channel options

### server-stats channeledit name (Slash Command)
 - Usage: `/server-stats channeledit name <channel> <name> `
 - `channel:` (Required) …
 - `name:` (Required) …

Edit a channels name

### server-stats channeledit position (Slash Command)
 - Usage: `/server-stats channeledit position <channel> <position> `
 - `channel:` (Required) …
 - `position:` (Required) …

Edit a channels position

### server-stats channeledit sync (Slash Command)
 - Usage: `/server-stats channeledit sync <channel> <toggle> `
 - `channel:` (Required) …
 - `toggle:` (Required) …

Set whether or not to sync permissions with the channels Category

### server-stats channeledit nsfw (Slash Command)
 - Usage: `/server-stats channeledit nsfw <toggle> [channel] `
 - `toggle:` (Required) …
 - `channel:` (Optional) …

Set whether or not a channel is NSFW

### server-stats channeledit topic (Slash Command)
 - Usage: `/server-stats channeledit topic <topic> [channel] `
 - `topic:` (Required) …
 - `channel:` (Optional) …

Edit a channels topic

### server-stats channeledit bitrate (Slash Command)
 - Usage: `/server-stats channeledit bitrate <channel> <bitrate> `
 - `channel:` (Required) …
 - `bitrate:` (Required) …

Edit a voice channels bitrate

### server-stats channeledit userlimit (Slash Command)
 - Usage: `/server-stats channeledit userlimit <channel> <limit> `
 - `channel:` (Required) …
 - `limit:` (Required) …

Edit a voice channels user limit

## server-stats who_is (Slash Command)
 - Usage: `/server-stats who_is <user_id> `
 - `user_id:` (Required) …

Display servers a user shares with the bot

## server-stats serveredit
 - Usage: `[p]server-stats serveredit `

Edit various server settings

### server-stats serveredit name (Slash Command)
 - Usage: `/server-stats serveredit name <name> `
 - `name:` (Required) …

Change the server name

### server-stats serveredit verificationlevel (Slash Command)
 - Usage: `/server-stats serveredit verificationlevel <level> `
 - `level:` (Required) …

Modify the servers verification level

### server-stats serveredit systemchannel (Slash Command)
 - Usage: `/server-stats serveredit systemchannel [channel] `
 - `channel:` (Optional) …

Change the system channel

### server-stats serveredit afkchannel (Slash Command)
 - Usage: `/server-stats serveredit afkchannel [channel] `
 - `channel:` (Optional) …

Change the servers AFK voice channel

### server-stats serveredit afktimeout (Slash Command)
 - Usage: `/server-stats serveredit afktimeout <timeout> `
 - `timeout:` (Required) …

Change the servers AFK timeout

## server-stats topmembers (Slash Command)
 - Usage: `/server-stats topmembers [include_bots] [server] `
 - `include_bots:` (Optional) …
 - `server:` (Optional) …

Lists top members on the server by join date

## server-stats getserver (Slash Command)
 - Usage: `/server-stats getserver [server] `
 - `server:` (Optional) …

Display info about servers the bot is on

## server-stats getservers (Slash Command)
 - Usage: `/server-stats getservers <servers> `
 - `servers:` (Required) …

Display info about multiple servers

## server-stats nummembers (Slash Command)
 - Usage: `/server-stats nummembers [server] `
 - `server:` (Optional) …

Display number of users on a server

## server-stats getroles (Slash Command)
 - Usage: `/server-stats getroles [server] `
 - `server:` (Optional) …

Displays all roles their ID and number of members in order of

## server-stats getreactions (Slash Command)
 - Usage: `/server-stats getreactions <message> `
 - `message:` (Required) …

Gets a list of all reactions from specified message and displays the user ID,

## server-stats serverstats (Slash Command)
 - Usage: `/server-stats serverstats `

Gets total messages on the server and displays each channel

## server-stats channelstats (Slash Command)
 - Usage: `/server-stats channelstats [channel] `
 - `channel:` (Optional) …

Gets total messages in a specific channel as well as the user who

## server-stats serveremojis (Slash Command)
 - Usage: `/server-stats serveremojis [id_emojis] [server] `
 - `id_emojis:` (Optional) …
 - `server:` (Optional) …

Display all server emojis in a menu that can be scrolled through

# avatar_look (Hybrid Command)
 - Usage: `[p]avatar_look <member> `
 - Slash Usage: `/avatar_look <member> `

Display a users avatar in chat

# emoji_look (Hybrid Command)
 - Usage: `[p]emoji_look <emoji> `
 - Slash Usage: `/emoji_look <emoji> `

Post a large size emojis in chat

# botstats (Hybrid Command)
 - Usage: `[p]botstats `
 - Slash Usage: `/botstats `
 - Aliases: `bs`

Display stats about the bot

# topic (Hybrid Command)
 - Usage: `[p]topic <channel> [topic] `
 - Slash Usage: `/topic <channel> [topic] `
 - Restricted to: `MOD`

Sets a specified channels topic<br/><br/>- `channel` is optional and if not supplied will use the current channel<br/> - Note: The maximum number of characters is 1024

# channeledit (Hybrid Command)
 - Usage: `[p]channeledit `
 - Slash Usage: `/channeledit `
 - Restricted to: `MOD`

Modify channel options

## channeledit name (Hybrid Command)
 - Usage: `[p]channeledit name <channel> <name> `
 - Slash Usage: `/channeledit name <channel> <name> `
 - Restricted to: `MOD`

Edit a channels name

## channeledit sync (Hybrid Command)
 - Usage: `[p]channeledit sync <channel> <toggle> `
 - Slash Usage: `/channeledit sync <channel> <toggle> `
 - Restricted to: `MOD`

Set whether or not to sync permissions with the channels Category

## channeledit topic (Hybrid Command)
 - Usage: `[p]channeledit topic <channel> <topic> `
 - Slash Usage: `/channeledit topic <channel> <topic> `
 - Restricted to: `MOD`

Edit a channels topic

## channeledit nsfw (Hybrid Command)
 - Usage: `[p]channeledit nsfw <toggle> [channel=None] `
 - Slash Usage: `/channeledit nsfw <toggle> [channel=None] `
 - Restricted to: `MOD`

Set whether or not a channel is NSFW

## channeledit permissions (Hybrid Command)
 - Usage: `[p]channeledit permissions <permission> <channel> <true_or_false> <roles_or_users> `
 - Slash Usage: `/channeledit permissions <permission> <channel> <true_or_false> <roles_or_users> `
 - Restricted to: `MOD`
 - Aliases: `perms and permission`

Edit channel read permissions for designated role<br/><br/>`[channel]` The channel you would like to edit. If no channel is provided<br/>the channel this command is run in will be used.<br/>`[true_or_false]` `True` or `False` to set the permission level. If this is not<br/>provided `None` will be used instead which signifies the default state of the permission.<br/>`[roles_or_users...]` the roles or users you want to edit this setting for.<br/><br/>`<permission>` Must be one of the following:<br/> - create_instant_invite<br/> - manage_channels<br/> - add_reactions<br/> - priority_speaker<br/> - stream<br/> - read_messages<br/> - send_messages<br/> - send_tts_messages<br/> - manage_messages<br/> - embed_links<br/> - attach_files<br/> - read_message_history<br/> - mention_everyone<br/> - external_emojis<br/> - connect<br/> - speak<br/> - mute_members<br/> - deafen_members<br/> - move_members<br/> - use_voice_activation<br/> - manage_roles<br/> - manage_webhooks<br/> - use_application_commands<br/> - request_to_speak<br/> - manage_threads<br/> - create_public_threads<br/> - create_private_threads<br/> - external_stickers<br/> - send_messages_in_threads<br/> - use_soundboard

## channeledit position (Hybrid Command)
 - Usage: `[p]channeledit position <channel> <position> `
 - Slash Usage: `/channeledit position <channel> <position> `
 - Restricted to: `MOD`

Edit a channels position

## channeledit userlimit (Hybrid Command)
 - Usage: `[p]channeledit userlimit <channel> <limit> `
 - Slash Usage: `/channeledit userlimit <channel> <limit> `
 - Restricted to: `MOD`

Edit a voice channels user limit<br/><br/>- `<channel>` The voice channel you want to change the limit on.<br/>- `<limit>` The limt on number of users between 0 and 99.

## channeledit bitrate (Hybrid Command)
 - Usage: `[p]channeledit bitrate <channel> <bitrate> `
 - Slash Usage: `/channeledit bitrate <channel> <bitrate> `
 - Restricted to: `MOD`

Edit a voice channels bitrate<br/><br/>- `<channel>` The voice channel you want to change.<br/>- `<bitrate>` The new bitrate between 8000 and 96000.

# pruneroles
 - Usage: `[p]pruneroles `
 - Checks: `server_only`

Perform various actions on users who haven't spoken in x days<br/><br/>Note: This will only check if a user has talked in the past x days whereas<br/>discords built in Prune checks online status

## pruneroles remove
 - Usage: `[p]pruneroles remove <days> <removed_roles> `
 - Restricted to: `MOD`

Remove roles from users who haven't spoken in x days.<br/><br/>- `<days>` is the number of days since last seen talking on the server.<br/>- `[removed_roles...]` the roles to remove from inactive users.

## pruneroles list
 - Usage: `[p]pruneroles list <days> [role=None] `
 - Restricted to: `MOD`

List the users who have not talked in x days.<br/><br/>- `<days>` The days you want to search for.<br/>- `[role]` The role you want to check.

## pruneroles add
 - Usage: `[p]pruneroles add <days> <new_roles> `
 - Restricted to: `MOD`

Give roles to users who haven't spoken in x days<br/><br/>- `<days>` is the number of days since last seen talking on the server<br/>- `[new_roles...]` The new roles to apply to a user who is inactive

## pruneroles kick
 - Usage: `[p]pruneroles kick <days> [role=None] [reinvite=True] `
 - Restricted to: `MOD`

Kick users from the server who have been inactive for x days<br/><br/>- `<days>` is the number of days since last seen talking on the server<br/>- `[role]` is the specified role you would like to kick defaults to everyone<br/>- `[reinvite=True]` True/False whether to try to send the user a message before kicking

# setserverjoin
 - Usage: `[p]setserverjoin [channel=None] `
 - Restricted to: `BOT_OWNER`
 - Checks: `server_only`

Set a channel to see new servers the bot is joining

# removeserverjoin
 - Usage: `[p]removeserverjoin `
 - Restricted to: `BOT_OWNER`

Stop bots join/leave server messages

# who_is (Hybrid Command)
 - Usage: `[p]who_is <user_id> `
 - Slash Usage: `/who_is <user_id> `

Display servers a user shares with the bot<br/><br/>- `<user_id>` The user you want to search for, ID's are preferred but some name lookup works.<br/> - Note: This will only show shared servers between you and the bot.

# serveredit (Hybrid Command)
 - Usage: `[p]serveredit `
 - Slash Usage: `/serveredit `
 - Restricted to: `ADMIN`

Edit various server settings

## serveredit systemchannel (Hybrid Command)
 - Usage: `[p]serveredit systemchannel [channel=None] `
 - Slash Usage: `/serveredit systemchannel [channel=None] `
 - Restricted to: `ADMIN`
 - Aliases: `welcomechannel`

Change the system channel<br/><br/>This is the default discord welcome channel.<br/>- `[channel]` The channel you want to set as the system channel.<br/> - If not provided will be set to `None`.

## serveredit name (Hybrid Command)
 - Usage: `[p]serveredit name <name> `
 - Slash Usage: `/serveredit name <name> `
 - Restricted to: `ADMIN`

Change the server name<br/><br/>- `<name>` The new name of the server.

## serveredit verificationlevel (Hybrid Command)
 - Usage: `[p]serveredit verificationlevel <level> `
 - Slash Usage: `/serveredit verificationlevel <level> `
 - Restricted to: `ADMIN`
 - Aliases: `verification`

Modify the servers verification level<br/><br/>- `<level>` must be one of:<br/> - `none`<br/> - `low`<br/> - `medium`<br/> - `table flip`<br/> - `high`<br/> - `double table flip`<br/> - `extreme`

## serveredit afktimeout (Hybrid Command)
 - Usage: `[p]serveredit afktimeout <timeout> `
 - Slash Usage: `/serveredit afktimeout <timeout> `
 - Restricted to: `ADMIN`

Change the servers AFK timeout<br/><br/>- `<timeout>` must be a value of 60, 300, 900, 1800, or 3600.

## serveredit afkchannel (Hybrid Command)
 - Usage: `[p]serveredit afkchannel [channel=None] `
 - Slash Usage: `/serveredit afkchannel [channel=None] `
 - Restricted to: `ADMIN`

Change the servers AFK voice channel<br/><br/>- `[channel]` The channel you want to set as the system channel.<br/> - If not provided will be set to `None`.

# topmembers (Hybrid Command)
 - Usage: `[p]topmembers [include_bots=None] [server=None] `
 - Slash Usage: `/topmembers [include_bots=None] [server=None] `
 - Restricted to: `MOD`
 - Checks: `server_only`

Lists top members on the server by join date<br/><br/>- `[include_bots]` whether or not to display bots or members. By default this will show everyone.<br/>- `[server]` can be either the server ID or name.<br/> - Note: You must share the server with the bot for this to work.

# listchannels
 - Usage: `[p]listchannels [server] `
 - Restricted to: `BOT_OWNER`

Lists channels and their position and ID for a server<br/><br/>- `[server]` can be either the server ID or name.<br/> - Note: You must share the server with the bot for this to work.

# getserver (Hybrid Command)
 - Usage: `[p]getserver [server] `
 - Slash Usage: `/getserver [server] `

Display info about servers the bot is on<br/><br/>- `[server]` can be either the server ID or name.<br/> - Note: You must share the server with the bot for this to work.

# getservers (Hybrid Command)
 - Usage: `[p]getservers <servers> `
 - Slash Usage: `/getservers <servers> `
 - Restricted to: `ADMIN`

Display info about multiple servers<br/><br/>- `[servers]` can be multiple either the server ID or name.<br/> - Note: You must share the server with the bot for this to work.

# nummembers (Hybrid Command)
 - Usage: `[p]nummembers [server] `
 - Slash Usage: `/nummembers [server] `
 - Restricted to: `MOD`
 - Checks: `server_only`

Display number of users on a server<br/><br/>- `[server]` can be either the server ID or name.<br/> - Note: You must share the server with the bot for this to work.

# getroles (Hybrid Command)
 - Usage: `[p]getroles [server] `
 - Slash Usage: `/getroles [server] `
 - Restricted to: `MOD`
 - Aliases: `rolestats`
 - Checks: `server_only`

Displays all roles their ID and number of members in order of<br/>hierarchy<br/><br/>- `[server]` can be either the server ID or name.<br/> - Note: You must share the server with the bot for this to work.

# getreactions (Hybrid Command)
 - Usage: `[p]getreactions <message> `
 - Slash Usage: `/getreactions <message> `
 - Restricted to: `MOD`
 - Aliases: `getreaction`

Gets a list of all reactions from specified message and displays the user ID,<br/>Username, and Discriminator and the emoji name.

# serverstats (Hybrid Command)
 - Usage: `[p]serverstats `
 - Slash Usage: `/serverstats `
 - Restricted to: `MOD`
 - Checks: `server_only`

Gets total messages on the server and displays each channel<br/>separately as well as the user who has posted the most in each channel<br/><br/>Note: This is a very slow function and may take some time to complete

# channelstats (Hybrid Command)
 - Usage: `[p]channelstats [channel=None] `
 - Slash Usage: `/channelstats [channel=None] `
 - Checks: `server_only`

Gets total messages in a specific channel as well as the user who<br/>has posted the most in that channel<br/><br/>`limit` must be a number of messages to check, defaults to all messages<br/>Note: This can be a very slow function and may take some time to complete

# serveremojis (Hybrid Command)
 - Usage: `[p]serveremojis [id_emojis=False] [server] `
 - Slash Usage: `/serveremojis [id_emojis=False] [server] `
 - Aliases: `serveremojis`
 - Checks: `server_only`

Display all server emojis in a menu that can be scrolled through<br/><br/>`id_emojis` return the id of emojis. Default to False, set True<br/> if you want to see emojis ID's.<br/>- `[server]` can be either the server ID or name.<br/> - Note: You must share the server with the bot for this to work.

