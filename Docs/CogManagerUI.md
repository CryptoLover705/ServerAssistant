# CogManagerUI Help

Commands to interface with Red's cog manager.

# paths
 - Usage: `[p]paths `
 - Restricted to: `BOT_OWNER`

Lists current cog paths in order of priority.

# addpath
 - Usage: `[p]addpath <path> `
 - Restricted to: `BOT_OWNER`

Add a path to the list of available cog paths.

# removepath
 - Usage: `[p]removepath <path_numbers> `
 - Restricted to: `BOT_OWNER`

Removes one or more paths from the available cog paths given the `path_numbers` from `[p]paths`.

# reorderpath
 - Usage: `[p]reorderpath <from_> <to> `
 - Restricted to: `BOT_OWNER`

Reorders paths internally to allow discovery of different cogs.

# installpath
 - Usage: `[p]installpath [path=None] `
 - Restricted to: `BOT_OWNER`

Returns the current install path or sets it if one is provided.<br/><br/>The provided path must be absolute or relative to the bot's<br/>directory and it must already exist.<br/><br/>No installed cogs will be transferred in the process.

# cogs
 - Usage: `[p]cogs `
 - Restricted to: `BOT_OWNER`

Lists all loaded and available cogs.

