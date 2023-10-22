# ConsoleLogs Help

A cog to display the console logs, with buttons and filter options, and to send commands errors in configured channels!

# consolelogs (Hybrid Command)
 - Usage: `[p]consolelogs [lines_break=2] [level=None] [ids=None] [logger_name=None] `
 - Slash Usage: `/consolelogs [lines_break=2] [level=None] [ids=None] [logger_name=None] `
 - Restricted to: `BOT_OWNER`
 - Aliases: `clogs`

View a console log, for a provided level/logger name.

## consolelogs addchannel (Hybrid Command)
 - Usage: `[p]consolelogs addchannel <channel> [global_errors=True] [prefixed_commands_errors=True] [slash_commands_errors=True] [dpy_ignored_exceptions=False] [full_console=False] [server_invite=True] [ignored_cogs] `
 - Slash Usage: `/consolelogs addchannel <channel> [global_errors=True] [prefixed_commands_errors=True] [slash_commands_errors=True] [dpy_ignored_exceptions=False] [full_console=False] [server_invite=True] [ignored_cogs] `
 - Aliases: `+`

Enable errors logging in a channel.<br/><br/>**Parameters:**<br/>- `channel`: The channel where the commands errors will be sent.<br/>- `global_errors`: Log errors for the entire bot, not just the channel server.<br/>- `prefixed_commands_errors`: Log prefixed commands errors.<br/>- `slash_commands_errors`: Log slash commands errors.<br/>- `dpy_ignored_exceptions`: Log dpy ignored exceptions (events listeners and Views errors).<br/>- `full_console`: Log all the console logs.<br/>- `server_invite`: Add a button "Guild Invite" in commands errors logs, only for community servers.<br/>- `ignored_cogs`: Ignore some cogs for `prefixed_commands_errors` and `slash_commands_errors`. You have to use the cog qualified_name like `ConsoleLogs` for this cog.

## consolelogs scroll (Hybrid Command)
 - Usage: `[p]consolelogs scroll [lines_break=2] [level=None] [ids=None] [logger_name=None] `
 - Slash Usage: `/consolelogs scroll [lines_break=2] [level=None] [ids=None] [logger_name=None] `

Scroll the console logs, for all levels/loggers or provided level/logger name.

## consolelogs removechannel (Hybrid Command)
 - Usage: `[p]consolelogs removechannel <channel> `
 - Slash Usage: `/consolelogs removechannel <channel> `
 - Aliases: `-`

Disable errors logging in a channel.

## consolelogs view (Hybrid Command)
 - Usage: `[p]consolelogs view [index=-1] [level=None] [ids=None] [logger_name=None] `
 - Slash Usage: `/consolelogs view [index=-1] [level=None] [ids=None] [logger_name=None] `

View the console logs one by one, for all levels/loggers or provided level/logger name.

## consolelogs stats (Hybrid Command)
 - Usage: `[p]consolelogs stats `
 - Slash Usage: `/consolelogs stats `
 - Aliases: `listloggers`

Display the stats for the bot logs since the bot start.

