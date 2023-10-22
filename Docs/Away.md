# Away Help

Le away cog

# away
 - Usage: `[p]away [delete_after=None] [message] `

Tell the bot you're away or back.<br/><br/>`delete_after` Optional seconds to delete the automatic reply. Must be minimum 5 seconds<br/>`message` The custom message to display when you're mentioned

# idle
 - Usage: `[p]idle [delete_after=None] [message] `

Set an automatic reply when you're idle.<br/><br/>`delete_after` Optional seconds to delete the automatic reply. Must be minimum 5 seconds<br/>`message` The custom message to display when you're mentioned

# offline
 - Usage: `[p]offline [delete_after=None] [message] `

Set an automatic reply when you're offline.<br/><br/>`delete_after` Optional seconds to delete the automatic reply. Must be minimum 5 seconds<br/>`message` The custom message to display when you're mentioned

# dnd
 - Usage: `[p]dnd [delete_after=None] [message] `
 - Aliases: `donotdisturb`

Set an automatic reply when you're dnd.<br/><br/>`delete_after` Optional seconds to delete the automatic reply. Must be minimum 5 seconds<br/>`message` The custom message to display when you're mentioned

# streaming
 - Usage: `[p]streaming [delete_after=None] [message] `

Set an automatic reply when you're streaming.<br/><br/>`delete_after` Optional seconds to delete the automatic reply. Must be minimum 5 seconds<br/>`message` The custom message to display when you're mentioned

# listening
 - Usage: `[p]listening [delete_after=None] [message] `

Set an automatic reply when you're listening to Spotify.<br/><br/>`delete_after` Optional seconds to delete the automatic reply. Must be minimum 5 seconds<br/>`message` The custom message to display when you're mentioned

# gaming
 - Usage: `[p]gaming <game> [delete_after=None] [message] `

Set an automatic reply when you're playing a specified game.<br/><br/>`game` The game you would like automatic responses for<br/>`delete_after` Optional seconds to delete the automatic reply. Must be minimum 5 seconds<br/>`message` The custom message to display when you're mentioned<br/><br/>Use "double quotes" around a game's name if it is more than one word.

# toggleaway
 - Usage: `[p]toggleaway [member=None] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Toggle away messages on the whole server or a specific server member.<br/><br/>Mods, Admins and Bot Owner are immune to this.

# awaytextonly
 - Usage: `[p]awaytextonly `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Toggle forcing the server's away messages to be text only.<br/><br/>This overrides the embed_links check this cog uses for message sending.

# awaysettings
 - Usage: `[p]awaysettings `
 - Aliases: `awayset`

View your current away settings

