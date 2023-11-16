# ReactLog Help

Log when reactions are added or removed.

# reactlog (Hybrid Command)
 - Usage: `[p]reactlog `
 - Slash Usage: `/reactlog `
 - Restricted to: `ADMIN`
 - Aliases: `reactionlog`
 - Checks: `server_only`

Reaction logging configuration commands.

## reactlog blacklist (Hybrid Command)
 - Usage: `[p]reactlog blacklist `
 - Slash Usage: `/reactlog blacklist `
 - Restricted to: `MOD`
 - Aliases: `bl`

Add/remove a member from reactlog blacklist.

### reactlog blacklist remove (Hybrid Command)
 - Usage: `[p]reactlog blacklist remove <member> `
 - Slash Usage: `/reactlog blacklist remove <member> `

Remove a member from reactlog blacklist.

### reactlog blacklist add (Hybrid Command)
 - Usage: `[p]reactlog blacklist add <member> `
 - Slash Usage: `/reactlog blacklist add <member> `

Add a member to reactlog blacklist.

## reactlog settings (Hybrid Command)
 - Usage: `[p]reactlog settings `
 - Slash Usage: `/reactlog settings `

Show current reaction log settings.

## reactlog grouped (Hybrid Command)
 - Usage: `[p]reactlog grouped [toggle=None] `
 - Slash Usage: `/reactlog grouped [toggle=None] `

Set whether to group reaction logging embeds.<br/><br/>This is useful if your bot is in many servers and has a lot of users.

## reactlog ignore (Hybrid Command)
 - Usage: `[p]reactlog ignore `
 - Slash Usage: `/reactlog ignore `
 - Restricted to: `MOD`

Add/remove a channel from reactlog ignore list.

### reactlog ignore remove (Hybrid Command)
 - Usage: `[p]reactlog ignore remove <channel> `
 - Slash Usage: `/reactlog ignore remove <channel> `

Remove a channel from reactlog ignore list.

### reactlog ignore add (Hybrid Command)
 - Usage: `[p]reactlog ignore add <channel> `
 - Slash Usage: `/reactlog ignore add <channel> `

Add a channel to reactlog ignore list.

## reactlog reactdel (Hybrid Command)
 - Usage: `[p]reactlog reactdel [toggle=None] `
 - Slash Usage: `/reactlog reactdel [toggle=None] `

Enable/disable logging when reactions removed.

## reactlog channel (Hybrid Command)
 - Usage: `[p]reactlog channel [channel=None] `
 - Slash Usage: `/reactlog channel [channel=None] `

Set the reactions logging channel.

## reactlog reactadd (Hybrid Command)
 - Usage: `[p]reactlog reactadd [toggle=None] `
 - Slash Usage: `/reactlog reactadd [toggle=None] `

Enable/disable logging when reactions added.

## reactlog logall (Hybrid Command)
 - Usage: `[p]reactlog logall [toggle=None] `
 - Slash Usage: `/reactlog logall [toggle=None] `

Set whether to log all reactions or not.<br/><br/>If enabled, all reactions will be logged.<br/>If disabled, only first added or last removed reactions will be logged.<br/><br/>Just a gentle reminder, it would be spammy if enabled.

