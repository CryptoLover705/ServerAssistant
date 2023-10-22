# CycleStatus Help

Automatically change the status of your bot every minute

# cyclestatus
 - Usage: `[p]cyclestatus `
 - Restricted to: `BOT_OWNER`
 - Aliases: `cstatus`

Commands working with the status

## cyclestatus list
 - Usage: `[p]cyclestatus list `

List the available statuses

## cyclestatus toggle
 - Usage: `[p]cyclestatus toggle <value> `

Toggle whether the status should be cycled.<br/><br/>This is handy for if you want to keep your statuses but don't want them displayed at the moment<br/><br/>**Arguments**<br/>    - `value` Whether to toggle cycling statues

## cyclestatus usehelp
 - Usage: `[p]cyclestatus usehelp [toggle=None] `

Change whether the status should have ` | [p]help`<br/><br/>**Arguments**<br/>    - `toggle` Whether help should be used or not.

## cyclestatus forcenext
 - Usage: `[p]cyclestatus forcenext `
 - Checks: `CycleStatus`

Force the next status to display on the bot

## cyclestatus clear
 - Usage: `[p]cyclestatus clear `

Clear all of the statuses

## cyclestatus add
 - Usage: `[p]cyclestatus add <status> `

Add a status to the list<br/><br/>Put `{bot_server_count}` or `{bot_member_count}` in your message to have the user count and server count of your bot!<br/>You can also put `{bot_prefix}` in your message to have the bot's prefix be displayed (eg. `{bot_prefix}ping`)<br/><br/>**Arguments**<br/>    - `status` The status to add to the cycle.

## cyclestatus mode
 - Usage: `[p]cyclestatus mode <mode> `

Change [botname]'s status mode<br/><br/>**Arguments**<br/>    - `mode` The mode type. Valid types are:<br/>    `online, idle, dnd, and do not disturb`

## cyclestatus random
 - Usage: `[p]cyclestatus random <value> `

Have the bot cycle to a random status<br/><br/>**Arguments**<br/>    - `value` Whether to have random statuses be enabled or not

## cyclestatus remove
 - Usage: `[p]cyclestatus remove [num=None] `
 - Aliases: `del, rm, and delete`

Remove a status from the list<br/><br/>**Arguments**<br/>    - `num` The index of the status you want to remove.

## cyclestatus settings
 - Usage: `[p]cyclestatus settings `

Show your current settings for the cycle status cog

## cyclestatus type
 - Usage: `[p]cyclestatus type <status> `

Change the type of [botname]'s status<br/><br/>**Arguments**<br/>    - `status` The status type. Valid types are<br/>    `playing, listening, watching, and competing`

