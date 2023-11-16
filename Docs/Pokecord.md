# Pokecord Help

Pokecord adapted to use on Server Assistant.

# poke
 - Usage: `[p]poke `

Pokecord commands

## poke nick
 - Usage: `[p]poke nick <id> <nickname> `

Set a pokémons nickname.<br/><br/>ID refers to the position within your pokémon listing.<br/>This is found at the bottom of the pokemon on `[p]list`

## poke release
 - Usage: `[p]poke release <id> `
 - Aliases: `free`

Release a pokémon.

## poke set
 - Usage: `[p]poke set `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Manage pokecord settings

### poke set toggle
 - Usage: `[p]poke set toggle [_type=None] `
 - Restricted to: `ADMIN`

Toggle pokecord on or off.

### poke set channel
 - Usage: `[p]poke set channel <channel> `
 - Restricted to: `ADMIN`

Set the channel(s) that pokemon are to spawn in.

### poke set levelup
 - Usage: `[p]poke set levelup [_type=None] `
 - Restricted to: `ADMIN`

Toggle levelup messages on or off.<br/><br/>If active channels are set, level up messages will only be sent in said channels. Otherwise it is ignored.<br/>If no active channels are set then level up messages will send as normal.

### poke set settings
 - Usage: `[p]poke set settings `
 - Restricted to: `ADMIN`

Overview of pokécord settings.

### poke set spawnloop
 - Usage: `[p]poke set spawnloop <state> `
 - Restricted to: `BOT_OWNER`

Turn the bot loop on or off.

### poke set blacklist
 - Usage: `[p]poke set blacklist <channel> `
 - Restricted to: `ADMIN`

Blacklist channels from contributing to pokémon spawning.

### poke set spawnchance
 - Usage: `[p]poke set spawnchance <_min> <_max> `
 - Restricted to: `BOT_OWNER`

Change the range of messages required for a spawn.

### poke set whitelist
 - Usage: `[p]poke set whitelist <channel> `
 - Restricted to: `ADMIN`

Whitelist channels that will contribute to pokémon spawning.

## poke trade
 - Usage: `[p]poke trade <user> <id> `

Pokecord Trading<br/><br/>Currently a work in progress.

### poke dev level
 - Usage: `[p]poke dev level <user> <pokeid> <lvl> `

Manually set a pokemons level

### poke dev reveal
 - Usage: `[p]poke dev reveal <user> <pokeid> `

Shows raw info for an owned pokemon

### poke dev stats
 - Usage: `[p]poke dev stats <user> <pokeid> <hp> <attack> <defence> <spatk> <spdef> <speed> `

Manually set a pokemons stats

### poke dev strip
 - Usage: `[p]poke dev strip <user> <id> `

Forcably removes a pokemone from user

### poke dev spawn
 - Usage: `[p]poke dev spawn <pokemon> `

Spawn a pokemon by name or random

### poke dev ivs
 - Usage: `[p]poke dev ivs <user> <pokeid> <hp> <attack> <defence> <spatk> <spdef> <speed> `

Manually set a pokemons IVs

## poke locale
 - Usage: `[p]poke locale <locale> `
 - Checks: `server_only`

Set the Pokecord locale to use for yourself.

## poke silence
 - Usage: `[p]poke silence [_type=None] `
 - Checks: `server_only`

Toggle pokecord levelling messages on or off.

# list
 - Usage: `[p]list [user=None] `
 - Aliases: `pokemon`

List a trainers or your own pokémon!

# select
 - Usage: `[p]select <_id> `
 - Checks: `server_only`

Select your default pokémon.

# pokedex
 - Usage: `[p]pokedex `

Check your caught pokémon!

# psearch
 - Usage: `[p]psearch <args> `

Search your pokemon.<br/><br/>Arguements must have `--` before them.<br/>    `--name` | `--n` - Search pokemon by name.<br/>    `--level`| `--l` - Search pokemon by level.<br/>    `--id`   | `--i` - Search pokemon by ID.<br/>    `--variant`   | `--v` - Search pokemon by variant.<br/>    `--type`   | `--t` - Search pokemon by type.<br/>    `--gender` | `--g` - Search by gender.<br/>    `--iv` | - Search by total IV.

# current
 - Usage: `[p]current `

Show your current selected pokemon

# starter
 - Usage: `[p]starter [pokemon=None] `

Choose your starter pokémon!

# hint
 - Usage: `[p]hint `
 - Cooldown: `1 per 30.0 seconds`

Get a hint on the pokémon!

# catch
 - Usage: `[p]catch <pokemon> `

Catch a pokemon!

