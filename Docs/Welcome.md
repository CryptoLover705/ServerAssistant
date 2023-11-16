# Welcome Help

Welcomes new members and goodbye those who leave to the guild<br/>in the default channel rewritten for V3 from<br/>https://github.com/irdumbs/Dumb-Cogs/blob/master/welcome/welcome.py

# welcomeset
 - Usage: `[p]welcomeset `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Sets welcome module settings

## welcomeset settings
 - Usage: `[p]welcomeset settings `

Show the servers welcome settings

## welcomeset embed
 - Usage: `[p]welcomeset embed `

Set various embed options.

### welcomeset embed icon
 - Usage: `[p]welcomeset embed icon [link=None] `

Set the embed icon image.<br/><br/>`[link]` must be a valid image link.<br/>You may also specify:<br/>- `member`, `user` or `avatar` to use the members avatar.<br/>- `server` or `server` to use the servers icon.<br/>- `splash` to use the servers splash image if available.<br/>if nothing is provided the defaults are used.

### welcomeset embed mention
 - Usage: `[p]welcomeset embed mention `

Toggle mentioning the user when they join.<br/><br/>This will add a mention outside the embed so they actually get the mention.

### welcomeset embed thumbnail
 - Usage: `[p]welcomeset embed thumbnail [link=None] `

Set the embed thumbnail image.<br/><br/>`[link]` must be a valid image link.<br/>You may also specify:<br/>- `member`, `user` or `avatar` to use the members avatar.<br/>- `server` or `server` to use the servers icon.<br/>- `splash` to use the servers splash image if available.<br/>if nothing is provided the defaults are used.

### welcomeset embed colour
 - Usage: `[p]welcomeset embed colour <colour> `
 - Aliases: `color`

Set the embed colour.<br/><br/>This accepts hex codes and integer value colours.

### welcomeset embed timestamp
 - Usage: `[p]welcomeset embed timestamp `

Toggle the timestamp in embeds.

### welcomeset embed author
 - Usage: `[p]welcomeset embed author `

Toggle the author field being filled in the embed.<br/><br/>Note: This will override the icon image if it is set.

### welcomeset embed toggle
 - Usage: `[p]welcomeset embed toggle `

Toggle embed messages.

### welcomeset embed image
 - Usage: `[p]welcomeset embed image `

Set embed image options.

#### welcomeset embed image greeting
 - Usage: `[p]welcomeset embed image greeting [link=None] `

Set the embed image link for greetings.<br/><br/>`[link]` must be a valid image link.<br/>You may also specify:<br/>- `member`, `user` or `avatar` to use the members avatar.<br/>- `server` or `server` to use the servers icon.<br/>- `splash` to use the servers splash image if available.<br/>if nothing is provided the defaults are used.

#### welcomeset embed image goodbye
 - Usage: `[p]welcomeset embed image goodbye [link=None] `

Set the embed image link for goodbyes.<br/><br/>`[link]` must be a valid image link.<br/>You may also specify:<br/>- `member`, `user` or `avatar` to use the members avatar.<br/>- `server` or `server` to use the servers icon.<br/>- `splash` to use the servers splash image if available.<br/>if nothing is provided the defaults are used.

### welcomeset embed title
 - Usage: `[p]welcomeset embed title [title] `

Set the embed title.<br/><br/>{0} is member.<br/>{1} is server.<br/>{count} can be used to display number of users who have joined today.<br/>[Available attributes for member](https://discordpy.readthedocs.io/en/latest/api.html#member)<br/>[Available attributes for server](https://discordpy.readthedocs.io/en/latest/api.html#server)

### welcomeset embed footer
 - Usage: `[p]welcomeset embed footer [footer] `

Set the embed footer.<br/><br/>{0} is member.<br/>{1} is server.<br/>{count} can be used to display number of users who have joined today.<br/>[Available attributes for member](https://discordpy.readthedocs.io/en/latest/api.html#member)<br/>[Available attributes for server](https://discordpy.readthedocs.io/en/latest/api.html#server)

## welcomeset bot
 - Usage: `[p]welcomeset bot `

Special greeting for bots.

### welcomeset bot role
 - Usage: `[p]welcomeset bot role [role] `

Set the role to put bots in when they join.<br/><br/>Leave blank to not give them a role.

### welcomeset bot msg
 - Usage: `[p]welcomeset bot msg [format_msg] `

Set the greeting msg for bots.<br/><br/>Leave blank to reset to regular user greeting

### welcomeset bot test
 - Usage: `[p]welcomeset bot test `

Test the bot joining message

### welcomeset bot goodbyemsg
 - Usage: `[p]welcomeset bot goodbyemsg [format_msg] `
 - Aliases: `goodbyemessage`

Set the goodbye msg for bots.<br/><br/>Leave blank to reset to regular user goodbye

## welcomeset greeting
 - Usage: `[p]welcomeset greeting `
 - Aliases: `welcome`

Manage welcome messages

### welcomeset greeting deleteprevious
 - Usage: `[p]welcomeset greeting deleteprevious `

Turns on/off deleting the previous greeting message when a user joins.

### welcomeset greeting channel
 - Usage: `[p]welcomeset greeting channel <channel> `

Sets the channel to send the greeting message.<br/><br/>If channel isn"t specified, the server's default channel will be used

### welcomeset greeting test
 - Usage: `[p]welcomeset greeting test `

Test the greeting message deleted after 60 seconds.

### welcomeset greeting grouped
 - Usage: `[p]welcomeset greeting grouped <grouped> `

Set whether to group greeting messages<br/><br/>This is useful if you have a high frequency of member joins.

### welcomeset greeting allowedmentions
 - Usage: `[p]welcomeset greeting allowedmentions <set_to> <allowed> `
 - Restricted to: `MOD`

Determine the bots allowed mentions for greetings<br/><br/>`<set_to>` What to set the allowed mentions to either `True` or `False`.<br/>`[allowed...]` must be either `everyone`, `users`, or `roles` and can include more than one.<br/><br/>Note: This will only function on Red 3.4.0 or higher.

### welcomeset greeting toggle
 - Usage: `[p]welcomeset greeting toggle `

Turns on/off welcoming new users to the server.

### welcomeset greeting deleteafter
 - Usage: `[p]welcomeset greeting deleteafter [delete_after=None] `

Set the time after which a greeting message is deleted in seconds.<br/><br/>Providing no input will set the bot to not delete after any time.

### welcomeset greeting add
 - Usage: `[p]welcomeset greeting add <format_msg> `

Adds a greeting message format for the server to be chosen at random<br/><br/>{0} is member<br/>{1} is server<br/>{count} can be used to display number of users who have joined today.<br/>Default is set to:<br/>    Welcome {0.name} to {1.name}!<br/><br/>Example formats:<br/>    {0.mention}.. What are you doing here?<br/>    {1.name} has a new member! {0.name} - {0.id}<br/>    Someone new joined! Who is it?! D: IS HE HERE TO HURT US?!<br/>[Available attributes for member](https://discordpy.readthedocs.io/en/latest/api.html#member)<br/>[Available attributes for server](https://discordpy.readthedocs.io/en/latest/api.html#server)

### welcomeset greeting list
 - Usage: `[p]welcomeset greeting list [raw=False] `
 - Aliases: `edit, delete, and del`

Lists the greeting messages of this server and allows editing the settings.<br/><br/>- `[raw=False]` Whether to show the raw text. This can be toggled afterwards.

### welcomeset greeting count
 - Usage: `[p]welcomeset greeting count `

Turns on/off showing how many users join each day.<br/><br/>This resets 24 hours after the cog was loaded.

### welcomeset greeting filter
 - Usage: `[p]welcomeset greeting filter [replacement=None] `

Set what to do when a username matches the bots filter.<br/><br/>- `[replacement]` replaces usernames that are found by cores filter with this word.<br/><br/>If left blank this will replace bad words with [Redacted] on grouped messages.

### welcomeset greeting minimumage
 - Usage: `[p]welcomeset greeting minimumage <days> `
 - Aliases: `age`

Set the minimum number of days a user account must be to show up in the greeting message.<br/><br/>- `<days>` number of days old the account must be, set to 0 to not require this.

## welcomeset whisper
 - Usage: `[p]welcomeset whisper [choice=None] `

Sets whether or not a DM is sent to the new user<br/><br/>Options:<br/>    off - turns off DMs to users<br/>    only - only send a DM to the user, don"t send a greeting to the channel<br/>    both - send a message to both the user and the channel<br/><br/>If Option isn't specified, toggles between "off" and "only"<br/>DMs will not be sent to bots

## welcomeset goodbye
 - Usage: `[p]welcomeset goodbye `
 - Aliases: `leave`

Manage goodbye messages.

### welcomeset goodbye deleteprevious
 - Usage: `[p]welcomeset goodbye deleteprevious `

Turns on/off deleting the previous greeting message when a user joins.

### welcomeset goodbye allowedmentions
 - Usage: `[p]welcomeset goodbye allowedmentions <set_to> <allowed> `
 - Restricted to: `MOD`

Determine the bots allowed mentions for greetings<br/><br/>`<set_to>` What to set the allowed mentions to either `True` or `False`.<br/>`[allowed...]` must be either `everyone`, `users`, or `roles` and can include more than one.<br/><br/>Note: This will only function on Red 3.4.0 or higher.

### welcomeset goodbye deleteafter
 - Usage: `[p]welcomeset goodbye deleteafter [delete_after=None] `

Set the time after which a greeting message is deleted in seconds.<br/><br/>Providing no input will set the bot to not delete after any time.

### welcomeset goodbye add
 - Usage: `[p]welcomeset goodbye add <format_msg> `

Adds a goodbye message format for the server to be chosen at random<br/><br/>{0} is member<br/>{1} is server<br/>Default is set to:<br/>    See you later {0.name}!<br/><br/>Example formats:<br/>    {0.mention}.. well, bye.<br/>    {1.name} has lost a member. {0.name} - {0.id}<br/>    Someone has quit the server! Who is it?! D:<br/>[Available attributes for member](https://discordpy.readthedocs.io/en/latest/api.html#member)<br/>[Available attributes for server](https://discordpy.readthedocs.io/en/latest/api.html#server)

### welcomeset goodbye list
 - Usage: `[p]welcomeset goodbye list [raw=False] `
 - Aliases: `edit, delete, and del`

Lists the goodbye messages of this server and allows editing the settings.<br/><br/>- `[raw=False]` Whether to show the raw text. This can be toggled afterwards.

### welcomeset goodbye toggle
 - Usage: `[p]welcomeset goodbye toggle `

Turns on/off sending goodbye messages to users who leave to the server.

### welcomeset goodbye test
 - Usage: `[p]welcomeset goodbye test `

Test the goodbye message deleted after 60 seconds

### welcomeset goodbye channel
 - Usage: `[p]welcomeset goodbye channel <channel> `

Sets the channel to send the goodbye message.

