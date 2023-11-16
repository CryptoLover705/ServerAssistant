# ExtendedModLog Help

Extended modlogs<br/>Works with core modlogset channel

# modlog
 - Usage: `[p]modlog `
 - Restricted to: `ADMIN`
 - Aliases: `modlogtoggle and modlogs`
 - Checks: `server_only`

Toggle various extended modlog notifications<br/><br/>Requires the channel to be setup with `[p]modlogset modlog #channel`<br/>Or can be sent to separate channels with `[p]modlog channel #channel event_name`

## modlog embeds
 - Usage: `[p]modlog embeds <true_or_false> <events> `
 - Aliases: `embed`

    Set modlog events to use embeds or text<br/><br/>    - `<true_or_false>` The desired embed setting either on or off.<br/>    <br/>- `[events...]` must be any of the following options (more than one event can be provided at once):<br/> - `channel_change` - Updates to channel name, etc.<br/> - `channel_create`<br/> - `channel_delete`<br/> - `commands_used`  - Bot command usage<br/> - `emoji_change`   - Emojis added or deleted<br/> - `server_change`   - Server settings changed<br/> - `message_edit`<br/> - `message_delete`<br/> - `member_change`  - Member changes like roles added/removed, nicknames, etc.<br/> - `role_change`    - Role updates permissions, name, etc.<br/> - `role_create`<br/> - `role_delete`<br/> - `voice_change`   - Voice channel join/leave<br/> - `member_join`<br/> - `member_left`<br/> - `invite_created`<br/> - `invite_deleted`<br/> - `thread_create`<br/> - `thread_delete`<br/> - `thread_change`<br/> - `stickers_change`

## modlog member
 - Usage: `[p]modlog member `
 - Aliases: `members and memberchanges`

Toggle individual member update settings.

### modlog member pending
 - Usage: `[p]modlog member pending `

Toggle pending updates for members.

### modlog member roles
 - Usage: `[p]modlog member roles `
 - Aliases: `role`

Toggle role updates for members.

### modlog member all
 - Usage: `[p]modlog member all <set_to> `

Set all member update settings.<br/><br/>- `<set_to>` True or False what to set all the member update settings to.

### modlog member avatar
 - Usage: `[p]modlog member avatar `

Toggle avatar updates for member changes.

### modlog member flags
 - Usage: `[p]modlog member flags `

Toggle flags updates for members.<br/><br/>This includes things like:<br/>- `did_rejoin`<br/>- `completed_onboarding`<br/>- `bypasses_verification`<br/>- `started_onboarding`

### modlog member timeout
 - Usage: `[p]modlog member timeout `

Toggle timeout updates for members.<br/><br/>Note: Due to a discord limitation this will not update when a members<br/>timeout has expired and may display a before timeout in the past.

### modlog member nickname
 - Usage: `[p]modlog member nickname `
 - Aliases: `nicknames`

Toggle nickname updates for member changes.

### modlog member settings
 - Usage: `[p]modlog member settings `

Show the current settings on member updates.

## modlog delete
 - Usage: `[p]modlog delete `

Delete logging settings.

### modlog delete bulkdelete
 - Usage: `[p]modlog delete bulkdelete `

Toggle bulk message delete notifications.

### modlog delete ignorecommands
 - Usage: `[p]modlog delete ignorecommands `

Toggle message delete notifications for valid bot command messages.

### modlog delete individual
 - Usage: `[p]modlog delete individual `

Toggle individual message delete notifications for bulk message delete.

### modlog delete cachedonly
 - Usage: `[p]modlog delete cachedonly `

Toggle message delete notifications for non-cached messages.<br/><br/>Delete notifications for non-cached messages<br/>will only show channel info without content of deleted message or its author.

## modlog ignore
 - Usage: `[p]modlog ignore <channel> `

Ignore a channel from message delete/edit events and bot commands.<br/><br/>- `<channel>` the channel or category to ignore events in

## modlog channel
 - Usage: `[p]modlog channel <channel> <events> `

    Set the channel for modlogs.<br/><br/>    - `<channel>` The text channel to send the events to.<br/>    <br/>- `[events...]` must be any of the following options (more than one event can be provided at once):<br/> - `channel_change` - Updates to channel name, etc.<br/> - `channel_create`<br/> - `channel_delete`<br/> - `commands_used`  - Bot command usage<br/> - `emoji_change`   - Emojis added or deleted<br/> - `server_change`   - Server settings changed<br/> - `message_edit`<br/> - `message_delete`<br/> - `member_change`  - Member changes like roles added/removed, nicknames, etc.<br/> - `role_change`    - Role updates permissions, name, etc.<br/> - `role_create`<br/> - `role_delete`<br/> - `voice_change`   - Voice channel join/leave<br/> - `member_join`<br/> - `member_left`<br/> - `invite_created`<br/> - `invite_deleted`<br/> - `thread_create`<br/> - `thread_delete`<br/> - `thread_change`<br/> - `stickers_change`

## modlog bot
 - Usage: `[p]modlog bot `
 - Aliases: `bots`

Bot filter settings.

### modlog bot edits
 - Usage: `[p]modlog bot edits `
 - Aliases: `edit`

Toggle message edit notifications for bot users.

### modlog bot change
 - Usage: `[p]modlog bot change `

Toggle bots from being logged in user updates.<br/><br/>This includes roles and nickname.

### modlog bot deletes
 - Usage: `[p]modlog bot deletes `
 - Aliases: `delete`

Toggle message delete notifications for bot users.<br/><br/>This will not affect delete notifications for messages that aren't in bot's cache.

### modlog bot voice
 - Usage: `[p]modlog bot voice `

Toggle bots from being logged in voice state updates.

## modlog all
 - Usage: `[p]modlog all <true_or_false> `

Turn all logging options on or off.<br/><br/>- `<true_or_false>` True of False, what to set all loggable settings to.

## modlog unignore
 - Usage: `[p]modlog unignore <channel> `

Unignore a channel from message delete/edit events and bot commands.<br/><br/>- `<channel>` the channel to unignore message delete/edit events.

## modlog settings
 - Usage: `[p]modlog settings `

Show the servers current ExtendedModlog settings

## modlog emojiset
 - Usage: `[p]modlog emojiset <emoji> <events> `

    Set the emoji used in text modlogs.<br/><br/>    - `<new_emoji>` can be any discord emoji or unicode emoji the bot has access to use.<br/>    <br/>- `[events...]` must be any of the following options (more than one event can be provided at once):<br/> - `channel_change` - Updates to channel name, etc.<br/> - `channel_create`<br/> - `channel_delete`<br/> - `commands_used`  - Bot command usage<br/> - `emoji_change`   - Emojis added or deleted<br/> - `server_change`   - Server settings changed<br/> - `message_edit`<br/> - `message_delete`<br/> - `member_change`  - Member changes like roles added/removed, nicknames, etc.<br/> - `role_change`    - Role updates permissions, name, etc.<br/> - `role_create`<br/> - `role_delete`<br/> - `voice_change`   - Voice channel join/leave<br/> - `member_join`<br/> - `member_left`<br/> - `invite_created`<br/> - `invite_deleted`<br/> - `thread_create`<br/> - `thread_delete`<br/> - `thread_change`<br/> - `stickers_change`

## modlog commandlevel
 - Usage: `[p]modlog commandlevel <level> `
 - Aliases: `commandslevel`

Set the level of commands to be logged.<br/><br/>- `[level...]` must include all levels you want from:<br/> - `NONE`<br/> - `MOD`<br/> - `ADMIN`<br/> - `GUILD_OWNER`<br/> - `BOT_OWNER`<br/><br/>These are the basic levels commands check for in permissions.<br/>`NONE` is a command anyone has permission to use, where as `MOD`<br/>can be `mod or permissions`

## modlog resetchannel
 - Usage: `[p]modlog resetchannel <events> `

    Reset the modlog event to the default modlog channel.<br/>    <br/>- `[events...]` must be any of the following options (more than one event can be provided at once):<br/> - `channel_change` - Updates to channel name, etc.<br/> - `channel_create`<br/> - `channel_delete`<br/> - `commands_used`  - Bot command usage<br/> - `emoji_change`   - Emojis added or deleted<br/> - `server_change`   - Server settings changed<br/> - `message_edit`<br/> - `message_delete`<br/> - `member_change`  - Member changes like roles added/removed, nicknames, etc.<br/> - `role_change`    - Role updates permissions, name, etc.<br/> - `role_create`<br/> - `role_delete`<br/> - `voice_change`   - Voice channel join/leave<br/> - `member_join`<br/> - `member_left`<br/> - `invite_created`<br/> - `invite_deleted`<br/> - `thread_create`<br/> - `thread_delete`<br/> - `thread_change`<br/> - `stickers_change`

## modlog colour
 - Usage: `[p]modlog colour <colour> <events> `
 - Aliases: `color`

    Set custom colours for modlog events<br/><br/>    - `<colour>` must be a hex code or a [built colour.](https://discordpy.readthedocs.io/en/latest/api.html#colour)<br/>    <br/>- `[events...]` must be any of the following options (more than one event can be provided at once):<br/> - `channel_change` - Updates to channel name, etc.<br/> - `channel_create`<br/> - `channel_delete`<br/> - `commands_used`  - Bot command usage<br/> - `emoji_change`   - Emojis added or deleted<br/> - `server_change`   - Server settings changed<br/> - `message_edit`<br/> - `message_delete`<br/> - `member_change`  - Member changes like roles added/removed, nicknames, etc.<br/> - `role_change`    - Role updates permissions, name, etc.<br/> - `role_create`<br/> - `role_delete`<br/> - `voice_change`   - Voice channel join/leave<br/> - `member_join`<br/> - `member_left`<br/> - `invite_created`<br/> - `invite_deleted`<br/> - `thread_create`<br/> - `thread_delete`<br/> - `thread_change`<br/> - `stickers_change`

## modlog toggle
 - Usage: `[p]modlog toggle <true_or_false> <events> `

    Turn on and off specific modlog actions<br/><br/>    - `<true_or_false>` Either on or off.<br/>    <br/>- `[events...]` must be any of the following options (more than one event can be provided at once):<br/> - `channel_change` - Updates to channel name, etc.<br/> - `channel_create`<br/> - `channel_delete`<br/> - `commands_used`  - Bot command usage<br/> - `emoji_change`   - Emojis added or deleted<br/> - `server_change`   - Server settings changed<br/> - `message_edit`<br/> - `message_delete`<br/> - `member_change`  - Member changes like roles added/removed, nicknames, etc.<br/> - `role_change`    - Role updates permissions, name, etc.<br/> - `role_create`<br/> - `role_delete`<br/> - `voice_change`   - Voice channel join/leave<br/> - `member_join`<br/> - `member_left`<br/> - `invite_created`<br/> - `invite_deleted`<br/> - `thread_create`<br/> - `thread_delete`<br/> - `thread_change`<br/> - `stickers_change`

