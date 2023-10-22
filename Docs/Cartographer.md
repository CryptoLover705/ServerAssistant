# Cartographer Help

Backup & Restore tools for Discord servers.<br/><br/>This cog can backup & restore the following:<br/>- Categories (permissions/order)<br/>- Text channels (permissions/order)<br/>- Voice channels (permissions/order)<br/>- Forum channels  (permissions/order)[Not forum posts]<br/>- Roles (permissions and what members they're assigned to)<br/><br/>When restoring, some roles may not be fully restored (such as order) if they were higher than the bot's role.

# cartographer
 - Usage: `[p]cartographer `
 - Checks: `server_only`

Open the Backup/Restore menu

# cartographerset
 - Usage: `[p]cartographerset `
 - Checks: `server_only`

Backup & Restore Tools

## cartographerset allow
 - Usage: `[p]cartographerset allow <server> `
 - Restricted to: `BOT_OWNER`

Add/Remove a server from the allow list

## cartographerset restorelatest
 - Usage: `[p]cartographerset restorelatest [delete_existing=False] `

Restore the latest backup for this server<br/><br/>**Arguments**<br/>- delete_existing: if True, deletes existing channels/roles that aren't part of the backup.

## cartographerset ignore
 - Usage: `[p]cartographerset ignore <server> `
 - Restricted to: `BOT_OWNER`

Add/Remove a server from the ignore list

## cartographerset maxbackups
 - Usage: `[p]cartographerset maxbackups <max_backups> `
 - Restricted to: `BOT_OWNER`

Set the max amount of backups a server can have

## cartographerset autobackups
 - Usage: `[p]cartographerset autobackups `
 - Restricted to: `BOT_OWNER`

Enable/Disable allowing auto backups

## cartographerset view
 - Usage: `[p]cartographerset view `
 - Restricted to: `BOT_OWNER`

View current global settings

## cartographerset backup
 - Usage: `[p]cartographerset backup `

Create a backup of this server

