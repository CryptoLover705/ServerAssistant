# Battleship Help

Play battleship with one other person.

# battleship
 - Usage: `[p]battleship `
 - Checks: `server_only`

Start a game of battleship.

# battleshipstop
 - Usage: `[p]battleshipstop `
 - Restricted to: `GUILD_OWNER`
 - Checks: `server_only`

Stop the game of battleship in this channel.

# battleshipboard
 - Usage: `[p]battleshipboard [channel=None] `

View your current board from an ongoing game in your DMs.<br/><br/>Specify the channel ID of the channel the game is in.

# battleshipset
 - Usage: `[p]battleshipset `
 - Restricted to: `GUILD_OWNER`
 - Checks: `server_only`

Config options for battleship.

## battleshipset mention
 - Usage: `[p]battleshipset mention [value=None] `

Set if players should be mentioned when their turn begins.<br/><br/>Defaults to False.<br/>This value is server specific.

## battleshipset thread
 - Usage: `[p]battleshipset thread [value=None] `

Set if a thread should be created per-game to contain game messages.<br/><br/>Defaults to False.<br/>This value is server specific.

## battleshipset extra
 - Usage: `[p]battleshipset extra [value=None] `

Set if an extra shot should be given after a hit.<br/><br/>Defaults to True.<br/>This value is server specific.

## battleshipset imgboard
 - Usage: `[p]battleshipset imgboard [value=None] `

Set if the board should be displayed using an image.<br/><br/>Defaults to True.<br/>This value is server specific.

