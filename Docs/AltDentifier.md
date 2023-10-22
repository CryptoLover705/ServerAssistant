# AltDentifier Help

Check new users with AltDentifier API

# altcheck
 - Usage: `[p]altcheck [member] `
 - Restricted to: `MOD`
 - Checks: `server_only`

Check a user on AltDentifier.

# altset
 - Usage: `[p]altset `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Manage AltDentifier Settings.

## altset action
 - Usage: `[p]altset action <level> [action=None] `

Specify what actions to take when a member joins and has a certain Trust Level.<br/><br/>Leave this empty to remove actions for the Level.<br/>The available actions are:<br/>`kick`<br/>`ban`<br/>`role` (don't say 'role' for this, pass an actual role)

## altset unwhitelist
 - Usage: `[p]altset unwhitelist <user_id> `
 - Aliases: `unwl`

Remove a user from the AltDentifier whitelist.

## altset settings
 - Usage: `[p]altset settings `

View AltDentifier Settings.

## altset channel
 - Usage: `[p]altset channel [channel=None] `

Set the channel to send AltDentifier join checks to.<br/><br/>This also works as a toggle, so if no channel is provided, it will disable join checks for this server.

## altset whitelist
 - Usage: `[p]altset whitelist <user_id> `
 - Aliases: `wl`

Whitelist a user from AltDentifier actions.

