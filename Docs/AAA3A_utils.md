# AAA3A_utils Help

Commands to manage all the cogs in AAA3A-cogs repo!

## aaa3a_utils flags (Hybrid Command)
 - Usage: `[p]aaa3a_utils flags <content> `
 - Slash Usage: `/aaa3a_utils flags <content> `
 - Restricted to: `BOT_OWNER`

Use any command with flags.

## aaa3a_utils senderrorwithsentry (Hybrid Command)
 - Usage: `[p]aaa3a_utils senderrorwithsentry <error> `
 - Slash Usage: `/aaa3a_utils senderrorwithsentry <error> `
 - Restricted to: `BOT_OWNER`

Send a recent error to the developer of AAA3A's cogs with Sentry (use the code given when the error has been triggered).<br/><br/>More details: https://aaa3a-cogs.readthedocs.io/en/latest/repo_telemetry.html

## aaa3a_utils getallfor (Hybrid Command)
 - Usage: `[p]aaa3a_utils getallfor [all=None] [page=None] [repo=None] [check_updates=False] [cog=None] [command=None] `
 - Slash Usage: `/aaa3a_utils getallfor [all=None] [page=None] [repo=None] [check_updates=False] [cog=None] [command=None] `
 - Restricted to: `BOT_OWNER`

Get all the necessary information to get support on a bot/repo/cog/command.<br/>With a html file.

## aaa3a_utils getlogs (Hybrid Command)
 - Usage: `[p]aaa3a_utils getlogs <cog> [level=all] `
 - Slash Usage: `/aaa3a_utils getlogs <cog> [level=all] `
 - Restricted to: `BOT_OWNER`

Get logs for a cog from AAA3A-cogs

## aaa3a_utils resetconfig (Hybrid Command)
 - Usage: `[p]aaa3a_utils resetconfig <cog> [confirmation=False] `
 - Slash Usage: `/aaa3a_utils resetconfig <cog> [confirmation=False] `
 - Restricted to: `BOT_OWNER`
 - Aliases: `clearconfig`

Reset Config for a cog from AAA3A-cogs.

## aaa3a_utils getdebugloopsstatus (Hybrid Command)
 - Usage: `[p]aaa3a_utils getdebugloopsstatus <cog> `
 - Slash Usage: `/aaa3a_utils getdebugloopsstatus <cog> `
 - Restricted to: `BOT_OWNER`

Get debug loops status for a cog from AAA3A-cogs.

## aaa3a_utils replacementvarpaths (Hybrid Command)
 - Usage: `[p]aaa3a_utils replacementvarpaths <state> `
 - Slash Usage: `/aaa3a_utils replacementvarpaths <state> `
 - Restricted to: `BOT_OWNER`

Replace various var paths in texts sent by cog from AAA3A-cogs.<br/><br/>Defaults is `True`.

## aaa3a_utils displaysentrymanualcommand (Hybrid Command)
 - Usage: `[p]aaa3a_utils displaysentrymanualcommand <state> `
 - Slash Usage: `/aaa3a_utils displaysentrymanualcommand <state> `
 - Restricted to: `BOT_OWNER`

Enable or disable displaying the command `[p]AAA3A_utils senderrorwithsentry` in commands errors.<br/><br/>Defaults is `True`.

