# BattleRoyale Help

Play Battle Royale with your friends!

# setbattleroyale
 - Usage: `[p]setbattleroyale `
 - Aliases: `battleset`

Configuration commands for BattleRoyale.

## setbattleroyale backgroundpath
 - Usage: `[p]setbattleroyale backgroundpath `
 - Restricted to: `BOT_OWNER`
 - Aliases: `path`

Get folder path for this cog's default backgrounds.

## setbattleroyale settings
 - Usage: `[p]setbattleroyale settings `
 - Restricted to: `BOT_OWNER`
 - Aliases: `view, ss, and showsettings`

View current settings.

## setbattleroyale wait
 - Usage: `[p]setbattleroyale wait <time> `
 - Restricted to: `BOT_OWNER`

Changes the wait time before battle starts.

## setbattleroyale addbackground
 - Usage: `[p]setbattleroyale addbackground [preferred_filename=None] `
 - Restricted to: `BOT_OWNER`
 - Aliases: `ab`

Add a custom background to the cog from discord. If several backgrounds are saved, the cog will select one at random.<br/><br/>**Parameters:**<br/>- `preferred_filaname`: Your preferred file name.<br/><br/>**Note:**<br/>- Do not include the file extension in the filaname, it'll be added automatically.

## setbattleroyale cooldown
 - Usage: `[p]setbattleroyale cooldown <per> `
 - Restricted to: `BOT_OWNER`

Set the coooldown amount.

## setbattleroyale removebackground
 - Usage: `[p]setbattleroyale removebackground <filename> `
 - Restricted to: `BOT_OWNER`
 - Aliases: `rb`

Remove a background from the cog's backgrounds folder.

## setbattleroyale emoji
 - Usage: `[p]setbattleroyale emoji [emoji=None] `
 - Restricted to: `BOT_OWNER`

Set an emoji to be used with Battle Royale.

## setbattleroyale prize
 - Usage: `[p]setbattleroyale prize <amount> `
 - Checks: `is_owner_if_bank_global`

Changes the prize amount.

## setbattleroyale listbackgrounds
 - Usage: `[p]setbattleroyale listbackgrounds `
 - Restricted to: `BOT_OWNER`

List your cog's custom backgrounds.

# battleroyale
 - Usage: `[p]battleroyale [delay=10] [skip=False] `
 - Aliases: `br`
 - Checks: `server_only`

Battle Royale with other members!<br/><br/>**Parameters:**<br/>- `delay`: min 10, max 20.<br/>- `skip`: will skip to results.

## battleroyale role
 - Usage: `[p]battleroyale role <role> [delay=10] [skip=False] `

Battle Royale with members from a specific role in your server.<br/><br/>Command author is automatically added to the player queue even if they don't have the role.<br/><br/>**Parameters**<br/>- `role`: which role to add to the player queue.<br/>- `delay`: min 10, max 20.<br/>- `skip`: will skip to results.

## battleroyale profile
 - Usage: `[p]battleroyale profile [user] `
 - Aliases: `stats`

Show your battle royale profile.

## battleroyale auto
 - Usage: `[p]battleroyale auto [players=30] [delay=10] [skip=False] `

Battle Royale with random players from your server.<br/><br/>Command author is automatically added to the player queue.<br/><br/>**Parameters**<br/>- `players`: how many players you want to join.<br/>- `delay`: min 10, max 20.<br/>- `skip`: will skip to results.

## battleroyale leaderboard
 - Usage: `[p]battleroyale leaderboard [sort_by=wins] `
 - Aliases: `lb`

Show the leaderboard.<br/><br/>**Parameters:**<br/>- `sort_by`: `wins`, `games` or `kills`.

