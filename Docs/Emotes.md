# Emotes Help

Custom emote solution for non-nitro users

# setemotes
 - Usage: `[p]setemotes `
 - Aliases: `se, setemote, and setemotesheet`

Change the configurations for Emotes Cog<br/><br/>Setting global values to `False` will override server settings and disable it across the whole bot.

## setemotes serverall
 - Usage: `[p]setemotes serverall <TrueOrFalse> `
 - Restricted to: `GUILD_OWNER`

The power switch for Cherry Emotes in this server

## setemotes all
 - Usage: `[p]setemotes all <TrueOrFalse> `
 - Restricted to: `BOT_OWNER`

The power switch for all of Cherry Emotes

## setemotes server
 - Usage: `[p]setemotes server <TrueOrFalse> `
 - Restricted to: `BOT_OWNER`
 - Aliases: `animated`

Enable the use of server animated emotes

## setemotes serverrecentsmax
 - Usage: `[p]setemotes serverrecentsmax <count> `
 - Restricted to: `GUILD_OWNER`

Determines how many messages back to search for emotes in this server<br/><br/>Not recommended to set higher than 20, for performance reasons.

## setemotes recentsmax
 - Usage: `[p]setemotes recentsmax <count> `
 - Restricted to: `BOT_OWNER`

Determines how many messages back to search for emotes<br/><br/>Not recommended to set higher than 20, for performance reasons.

## setemotes sheet
 - Usage: `[p]setemotes sheet `
 - Restricted to: `BOT_OWNER`

Set up Emote Sheets<br/><br/>Allows users to pull from a Google Sheet of saved emotes.<br/><br/>For more information, see https://github.com/coffeebank/coffee-cogs/wiki/Emotes<br/><br/>To set Google Sheets API key, use the command **`[p]set api gsheets api_key,YOURKEYHERE`**

### setemotes sheet id
 - Usage: `[p]setemotes sheet id <sheetId> `

Set Emote Google Sheet's ID, where the emote data was entered into

### setemotes sheet false
 - Usage: `[p]setemotes sheet false `

Disable the use of Emote Sheets by the bot

### setemotes sheet true
 - Usage: `[p]setemotes sheet true `

Enable the use of Emote Sheets by the bot<br/><br/>Will automatically set to True when you set an Emote Sheet

### setemotes sheet update
 - Usage: `[p]setemotes sheet update `

Pull updates from Emote Google Sheet

## setemotes recents
 - Usage: `[p]setemotes recents <TrueOrFalse> `
 - Restricted to: `BOT_OWNER`

Enable the use of searching recent messages for emotes

# emotesearch
 - Usage: `[p]emotesearch <search> [page=1] `
 - Aliases: `esearch and ee`

Search for image-ized emote url

# emotesend
 - Usage: `[p]emotesend <search> `
 - Aliases: `esend and eee`

Send an emote from Emote Sheet, with first search result

# emoteinfo
 - Usage: `[p]emoteinfo [emote=None] `
 - Aliases: `ei`

Send info about an emote<br/><br/>If you don't have access to the emote (ie. no Nitro, or can't send the emote because it's from another server), you can reply to the message with the emote you want and the `[p]emoteinfo` command will pick up the emote.

# emotelist
 - Usage: `[p]emotelist [hist=False] `

List all emotes in message<br/><br/>Shows a list of names and urls for all emotes in a message, when you reply to a message with this command. Useful for Emote Spreadsheet.

# showemote
 - Usage: `[p]showemote <emoteUrl> `

Show an emote you have an URL for

