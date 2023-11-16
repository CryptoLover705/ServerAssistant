# AutoGist Help

Auto-upload files with configured extension sent by users to gist.github.com.

# autogistset
 - Usage: `[p]autogistset `
 - Restricted to: `ADMIN`

AutoGist settings.

## autogistset listoverridden
 - Usage: `[p]autogistset listoverridden `
 - Checks: `server_only`

List server channels that don't use the default setting.

## autogistset token
 - Usage: `[p]autogistset token `
 - Restricted to: `BOT_OWNER`

Instructions to set the GitHub API token.

## autogistset extensions
 - Usage: `[p]autogistset extensions `
 - Aliases: `ext and exts`
 - Checks: `server_only`

Settings for file extensions<br/>that are required for AutoGist to upload file to Gist.<br/><br/>By default AutoGist will look for files with `.txt` and `.log` extensions.

### autogistset extensions remove
 - Usage: `[p]autogistset extensions remove <extensions> `
 - Aliases: `delete`

Remove file extensions from the list.<br/><br/>Example:<br/>`[p]autogist extensions remove txt .log` - removes `.txt` and `.log` extensions.

### autogistset extensions add
 - Usage: `[p]autogistset extensions add <extensions> `

Add file extensions to the list.<br/><br/>Example:<br/>`[p]autogist extensions add txt .log` - adds `.txt` and `.log` extensions.

### autogistset extensions list
 - Usage: `[p]autogistset extensions list `

List file extensions that are required for AutoGist to upload file to Gist.

## autogistset listentohumans
 - Usage: `[p]autogistset listentohumans [state=None] `
 - Checks: `server_only`

Make AutoGist listen to messages from humans in this server.

## autogistset listentoself
 - Usage: `[p]autogistset listentoself [state=None] `
 - Checks: `server_only`

Make the bot listen to messages from itself in this server.<br/><br/>See also: `[p]autogistset listentobots` command,<br/>that makes the bot listen to other bots.

## autogistset channeldefault
 - Usage: `[p]autogistset channeldefault [allow=None] `
 - Checks: `server_only`

Set whether AutoGist should by default listen to channels.<br/><br/>If default is set to True, bot will only listen to channels it was explicitly<br/>allowed to listen to with `[p]autogistset allowchannels` command.<br/><br/>If default is set to False, bot will listen to all channels except the ones<br/>it was explicitly blocked from listening to<br/>with `[p]autogistset denychannels` command.<br/><br/>By default, servers will not listen to any channel.<br/>Use `[p]autogist channeldefault` without a setting to see current mode.

## autogistset blockchannels
 - Usage: `[p]autogistset blockchannels <channels> `
 - Aliases: `blockchannel`
 - Checks: `server_only`

Block the bot from listening to the given channels.

## autogistset listentobots
 - Usage: `[p]autogistset listentobots [state=None] `
 - Checks: `server_only`

Make AutoGist listen to messages from other bots in this server.<br/><br/>NOTE: To make bot listen to messages from itself,<br/>you need to use `[p]autogistset listentoself` command.

## autogistset allowchannels
 - Usage: `[p]autogistset allowchannels <channels> `
 - Aliases: `allowchannel`
 - Checks: `server_only`

Allow the bot to listen to the given channels.

