# ChessGame Help

Cog to Play chess!

# chess
 - Usage: `[p]chess `

manage chess games

## chess launch
 - Usage: `[p]chess launch <player> <other_player> [game_name=None] [game_type=None] `
 - Restricted to: `BOT_OWNER`

start a new game<br/><br/>_Standard is the default when no game type is given_<br/>__**1**__: Standard, Chess, Classical, Normal, Illegal, From Position<br/>__**2**__: Suicide, Suicide chess<br/>__**3**__: Giveaway, Giveaway chess, Give away, Give away chess<br/>__**4**__: Antichess, Anti chess, Anti<br/>__**5**__: Atomic, Atom, Atomic chess<br/>__**6**__: King of the Hill, KOTH, kingOfTheHill<br/>__**7**__: Racing Kings, Racing, Race, racingkings<br/>__**8**__: Horde, Horde chess<br/>__**9**__: Three-check, Three check, Threecheck, Three check chess, 3-check, 3 check, 3check<br/>__**10**__: Crazyhouse, Crazy House, House, ZH

## chess move
 - Usage: `[p]chess move <game_name> <move> `

move the next game piece, using Standard Algebraic Notation

## chess draw
 - Usage: `[p]chess draw `

draw related commands

### chess draw byagreement
 - Usage: `[p]chess draw byagreement <game_name> `

Offer draw by agreement

### chess draw claim
 - Usage: `[p]chess draw claim <game_name> <claim_type> `

if valid claim made to draw the game will end with no victor

## chess list
 - Usage: `[p]chess list `

list all available games

## chess close
 - Usage: `[p]chess close <game_name> [channel=None] [no_confirmation=False] `
 - Restricted to: `BOT_OWNER`

sub command to close a game

## chess start
 - Usage: `[p]chess start <other_player> [game_name=None] [game_type=None] `

start a new game<br/><br/>_Standard is the default when no game type is given_<br/>__**1**__: Standard, Chess, Classical, Normal, Illegal, From Position<br/>__**2**__: Suicide, Suicide chess<br/>__**3**__: Giveaway, Giveaway chess, Give away, Give away chess<br/>__**4**__: Antichess, Anti chess, Anti<br/>__**5**__: Atomic, Atom, Atomic chess<br/>__**6**__: King of the Hill, KOTH, kingOfTheHill<br/>__**7**__: Racing Kings, Racing, Race, racingkings<br/>__**8**__: Horde, Horde chess<br/>__**9**__: Three-check, Three check, Threecheck, Three check chess, 3-check, 3 check, 3check<br/>__**10**__: Crazyhouse, Crazy House, House, ZH

## chess scoreboard
 - Usage: `[p]chess scoreboard `

scoreboard related commands

### chess scoreboard increment
 - Usage: `[p]chess scoreboard increment <player> <elo> <wins> <losses> <ties> `
 - Restricted to: `BOT_OWNER`

allows bot owner to increment (decrement if negative value passed) a player's score

### chess scoreboard find
 - Usage: `[p]chess scoreboard find [player=None] `

find a player's score. If none is provided this will look for the requester's score

### chess scoreboard clear
 - Usage: `[p]chess scoreboard clear `
 - Restricted to: `BOT_OWNER`

allows bot owner clear the scoreboard

#### chess scoreboard clear player
 - Usage: `[p]chess scoreboard clear player <player> `
 - Restricted to: `BOT_OWNER`

removes a particular player (or nonexistant id) from the scoreboard

#### chess scoreboard clear all
 - Usage: `[p]chess scoreboard clear all `
 - Restricted to: `BOT_OWNER`

remove **ALL** scores from the scoreboard

### chess scoreboard list
 - Usage: `[p]chess scoreboard list [sort_by=wins] `

list users scoreboard from highest to lowest<br/><br/>Scoreboard can be sorted by elo, wins, losses, or ties.<br/>Scoreboard is sorted by wins by default.

## chess show
 - Usage: `[p]chess show <game_name> `

reposts the last gameboard state

