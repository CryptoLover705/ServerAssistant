# CommandsButtons Help

A cog to allow a user to execute a command by clicking on a button!

# commandsbuttons (Hybrid Command)
 - Usage: `[p]commandsbuttons `
 - Slash Usage: `/commandsbuttons `
 - Restricted to: `BOT_OWNER`
 - Checks: `server_only`

Group of commands to use CommandsButtons.

## commandsbuttons bulk (Hybrid Command)
 - Usage: `[p]commandsbuttons bulk <message> <commands_buttons> `
 - Slash Usage: `/commandsbuttons bulk <message> <commands_buttons> `
 - Checks: `server_only`

Add commands-buttons for a message.<br/><br/>```[p]commandsbuttons bulk <message> ":reaction1:|ping" ":reaction2:|ping" :reaction3:|ping"```

## commandsbuttons clear (Hybrid Command)
 - Usage: `[p]commandsbuttons clear <message> `
 - Slash Usage: `/commandsbuttons clear <message> `
 - Checks: `server_only`

Clear all commands-buttons for a message.

## commandsbuttons list (Hybrid Command)
 - Usage: `[p]commandsbuttons list [message=None] `
 - Slash Usage: `/commandsbuttons list [message=None] `
 - Checks: `server_only`

List all commands-buttons of this server or display the settings for a specific one.

## commandsbuttons remove (Hybrid Command)
 - Usage: `[p]commandsbuttons remove <message> <config_identifier> `
 - Slash Usage: `/commandsbuttons remove <message> <config_identifier> `
 - Aliases: `-`
 - Checks: `server_only`

Remove a command-button for a message.<br/><br/>Use `[p]commandsbuttons list <message>` to find the config identifier.

## commandsbuttons add (Hybrid Command)
 - Usage: `[p]commandsbuttons add <message> <command> <emoji> [style_button=2] [text_button] `
 - Slash Usage: `/commandsbuttons add <message> <command> <emoji> [style_button=2] [text_button] `
 - Aliases: `+`
 - Checks: `server_only`

Add a command-button for a message.<br/><br/>(Use the number for the color.)<br/>• `primary`: 1<br/>• `secondary`: 2<br/>• `success`: 3<br/>• `danger`: 4<br/># Aliases<br/>• `blurple`: 1<br/>• `grey`: 2<br/>• `gray`: 2<br/>• `green`: 3<br/>• `red`: 4

