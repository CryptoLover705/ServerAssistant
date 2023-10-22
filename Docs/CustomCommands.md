# CustomCommands Help

This cog contains commands for creating and managing custom commands that display text.<br/><br/>These are useful for storing information members might need, like FAQ answers or invite links.<br/>Custom commands can be used by anyone by default, so be careful with pings.<br/>Commands can only be lowercase, and will not respond to any uppercase letters.

# customcom
 - Usage: `[p]customcom `
 - Aliases: `cc`
 - Checks: `server_only`

Base command for Custom Commands management.

## customcom list
 - Usage: `[p]customcom list `
 - Checks: `bot_can_react`

List all available custom commands.<br/><br/>The list displays a preview of each command's response, with<br/>markdown escaped and newlines replaced with spaces.

## customcom cooldown
 - Usage: `[p]customcom cooldown <command> [cooldown=None] [per] `
 - Restricted to: `MOD`

Set, edit, or view the cooldown for a custom command.<br/><br/>You may set cooldowns per member, channel, or server. Multiple<br/>cooldowns may be set. All cooldowns must be cooled to call the<br/>custom command.<br/><br/>Examples:<br/>- `[p]customcom cooldown pingrole`<br/>- `[p]customcom cooldown yourcommand 30`<br/>- `[p]cc cooldown mycommand 30 server`<br/><br/>**Arguments:**<br/><br/>- `<command>` The custom command to check or set the cooldown.<br/>- `[cooldown]` The number of seconds to wait before allowing the command to be invoked again. If omitted, will instead return the current cooldown settings.<br/>- `[per]` The group to apply the cooldown on. Defaults to per member. Valid choices are server / server, user / member, and channel.

## customcom edit
 - Usage: `[p]customcom edit <command> [text] `
 - Restricted to: `MOD`

Edit a custom command.<br/><br/>Example:<br/>- `[p]customcom edit yourcommand Text you want`<br/><br/>**Arguments:**<br/><br/>- `<command>` The custom command to edit.<br/>- `<text>` The new text to return when executing the command.

## customcom create
 - Usage: `[p]customcom create <command> <text> `
 - Restricted to: `MOD`
 - Aliases: `add`

Create custom commands.<br/><br/>If a type is not specified, a simple CC will be created.<br/>CCs can be enhanced with arguments, see the guide<br/>[here](https://docs.discord.red/en/stable/cog_customcom.html).

### customcom create random
 - Usage: `[p]customcom create random <command> `
 - Restricted to: `MOD`

Create a CC where it will randomly choose a response!<br/><br/>Note: This command is interactive.<br/><br/>**Arguments:**<br/><br/>- `<command>` The command executed to return the text. Cast to lowercase.

### customcom create simple
 - Usage: `[p]customcom create simple <command> <text> `
 - Restricted to: `MOD`

Add a simple custom command.<br/><br/>Example:<br/>- `[p]customcom create simple yourcommand Text you want`<br/><br/>**Arguments:**<br/><br/>- `<command>` The command executed to return the text. Cast to lowercase.<br/>- `<text>` The text to return when executing the command. See guide for enhanced usage.

## customcom delete
 - Usage: `[p]customcom delete <command> `
 - Restricted to: `MOD`
 - Aliases: `del and remove`

Delete a custom command.<br/><br/>Example:<br/>- `[p]customcom delete yourcommand`<br/><br/>**Arguments:**<br/><br/>- `<command>` The custom command to delete.

## customcom search
 - Usage: `[p]customcom search <query> `
 - Checks: `server_only`

Searches through custom commands, according to the query.<br/><br/>Uses fuzzy searching to find close matches.<br/><br/>**Arguments:**<br/><br/>- `<query>` The query to search for. Can be multiple words.

## customcom show
 - Usage: `[p]customcom show <command_name> `

Shows a custom command's responses and its settings.<br/><br/>**Arguments:**<br/><br/>- `<command_name>` The custom command to show.

## customcom raw
 - Usage: `[p]customcom raw <command> `

Get the raw response of a custom command, to get the proper markdown.<br/><br/>This is helpful for copy and pasting.<br/><br/>**Arguments:**<br/><br/>- `<command>` The custom command to get the raw response of.

