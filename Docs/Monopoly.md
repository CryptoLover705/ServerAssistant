# Monopoly Help

Play monopoly with 2-8 people.

# monopoly
 - Usage: `[p]monopoly [savefile=None] `
 - Checks: `server_only`

Play monopoly with 2-8 people.<br/><br/>Use the optional parameter "savefile" to load a saved game.

## monopoly delete
 - Usage: `[p]monopoly delete <savefiles> `
 - Restricted to: `GUILD_OWNER`

Delete one or more save files.<br/><br/>This cannot be undone.

## monopoly list
 - Usage: `[p]monopoly list `

List available save files.

## monopolyconvert list
 - Usage: `[p]monopolyconvert list `

List save files that can be converted.

# monopolystop
 - Usage: `[p]monopolystop `
 - Restricted to: `GUILD_OWNER`
 - Checks: `server_only`

Stop the game of monopoly in this channel.

# monopolyset
 - Usage: `[p]monopolyset `
 - Restricted to: `GUILD_OWNER`
 - Checks: `server_only`

Config options for monopoly.

## monopolyset doublego
 - Usage: `[p]monopolyset doublego [value=None] `

Set if landing on go should double the amount of money given.<br/><br/>Defaults to False.<br/>This value is server specific.

## monopolyset minraise
 - Usage: `[p]monopolyset minraise [value=None] `

Set the minimum raise in auctions.<br/><br/>Defaults to 1.<br/>This value is server specific.

## monopolyset darkmode
 - Usage: `[p]monopolyset darkmode [value=None] `

Set if the board should be a darker varient.<br/><br/>Defaults to False.<br/>This value is server specific.

## monopolyset auction
 - Usage: `[p]monopolyset auction [value=None] `

Set if properties should be auctioned when passed on.<br/><br/>Defaults to False.<br/>This value is server specific.

## monopolyset mention
 - Usage: `[p]monopolyset mention [value=None] `

Set if players should be mentioned when their turn begins.<br/><br/>Defaults to False.<br/>This value is server specific.

## monopolyset maxjailrolls
 - Usage: `[p]monopolyset maxjailrolls [value=None] `

Set the maximum number of rolls in jail before bail has to be paid.<br/><br/>Defaults to 3.<br/>This value is server specific.

## monopolyset startingcash
 - Usage: `[p]monopolyset startingcash [value=None] `

Set how much money players should start the game with.<br/><br/>Defaults to 1500.<br/>This value is server specific.

## monopolyset bail
 - Usage: `[p]monopolyset bail [value=None] `

Set how much bail should cost.<br/><br/>Defaults to 50.<br/>This value is server specific.

## monopolyset luxury
 - Usage: `[p]monopolyset luxury [value=None] `

Set how much Luxury Tax should cost.<br/><br/>Defaults to 100.<br/>This value is server specific.

## monopolyset hotellimit
 - Usage: `[p]monopolyset hotellimit [value=None] `

Set a limit on the number of hotels that can be bought.<br/><br/>Use -1 to disable the limit.<br/>Defaults to 12.<br/>This value is server specific.

## monopolyset houselimit
 - Usage: `[p]monopolyset houselimit [value=None] `

Set a limit on the number of houses that can be bought.<br/><br/>Use -1 to disable the limit.<br/>Defaults to 32.<br/>This value is server specific.

## monopolyset income
 - Usage: `[p]monopolyset income [value=None] `

Set how much Income Tax should cost.<br/><br/>Defaults to 200.<br/>This value is server specific.

## monopolyset timeout
 - Usage: `[p]monopolyset timeout [value=None] `

Set the amount of time before the game times out.<br/><br/>Value is in seconds.<br/>Use -1 to disable the timeout.<br/>Defaults to 60.<br/>This value is server specific.

## monopolyset thread
 - Usage: `[p]monopolyset thread [value=None] `

Set if a thread should be created per-game to contain game messages.<br/><br/>Defaults to False.<br/>This value is server specific.

## monopolyset go
 - Usage: `[p]monopolyset go [value=None] `

Set the base value of passing go.<br/><br/>Defaults to 200.<br/>This value is server specific.

## monopolyset freeparking
 - Usage: `[p]monopolyset freeparking [value=None] `

Set the reward for landing on free parking.<br/><br/>Use an integer to set a static reward.<br/>Use "none" for no reward.<br/>Use "tax" to use the sum of taxes and fees as the reward.<br/>Defaults to none.<br/>This value is server specific.

