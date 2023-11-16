# TicketTool Help

A cog to manage a tickets system!

# settickettool (Hybrid Command)
 - Usage: `[p]settickettool `
 - Slash Usage: `/settickettool `
 - Restricted to: `ADMIN`
 - Aliases: `tickettoolset`
 - Checks: `server_only`

Configure TicketTool for your server.

## settickettool categoryopen (Hybrid Command)
 - Usage: `[p]settickettool categoryopen <profile> <value> `
 - Slash Usage: `/settickettool categoryopen <profile> <value> `
 - Checks: `server_only`

Set the category where the opened tickets will be.<br/><br/>Default value: None<br/>Dev: <class 'discord.channel.CategoryChannel'>

## settickettool modlog (Hybrid Command)
 - Usage: `[p]settickettool modlog <profile> <value> `
 - Slash Usage: `/settickettool modlog <profile> <value> `
 - Checks: `server_only`

Does the bot create an action in the bot modlog when a ticket is created?<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## settickettool profileremove (Hybrid Command)
 - Usage: `[p]settickettool profileremove <profile> [confirmation=False] `
 - Slash Usage: `/settickettool profileremove <profile> [confirmation=False] `
 - Aliases: `removeprofile`
 - Checks: `server_only`

Remove an existing profile.

## settickettool closeconfirmation (Hybrid Command)
 - Usage: `[p]settickettool closeconfirmation <profile> <value> `
 - Slash Usage: `/settickettool closeconfirmation <profile> <value> `
 - Checks: `server_only`

Should the bot ask for confirmation before closing the ticket (deletion will necessarily have a confirmation)?<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## settickettool modalconfig (Hybrid Command)
 - Usage: `[p]settickettool modalconfig <profile> [confirmation=False] `
 - Slash Usage: `/settickettool modalconfig <profile> [confirmation=False] `
 - Aliases: `configmodal`
 - Checks: `server_only`

Set all settings for the cog with a Discord Modal.

## settickettool enable (Hybrid Command)
 - Usage: `[p]settickettool enable <profile> <value> `
 - Slash Usage: `/settickettool enable <profile> <value> `
 - Checks: `server_only`

Enable the system.<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## settickettool deleteonclose (Hybrid Command)
 - Usage: `[p]settickettool deleteonclose <profile> <value> `
 - Slash Usage: `/settickettool deleteonclose <profile> <value> `
 - Checks: `server_only`

Does closing the ticket directly delete it (with confirmation)?<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## settickettool profileadd (Hybrid Command)
 - Usage: `[p]settickettool profileadd <profile> `
 - Slash Usage: `/settickettool profileadd <profile> `
 - Aliases: `addprofile`
 - Checks: `server_only`

Create a new profile with defaults settings.

## settickettool message (Hybrid Command)
 - Usage: `[p]settickettool message <profile> <channel> <message> <reason_options> [emoji=🎟️] [label=None] `
 - Slash Usage: `/settickettool message <profile> <channel> <message> <reason_options> [emoji=🎟️] [label=None] `
 - Checks: `server_only`

Send a message with a button to open a ticket or dropdown with possible reasons.<br/><br/>Examples:<br/>- `[p]settickettool message <profile> #general "🐛|Report a bug|If you find a bug, report it here.|bug" "⚠️|Report a user|If you find a malicious user, report it here.|user"`<br/>- `[p]settickettool <profile> 1234567890-0987654321`

## settickettool createonreact (Hybrid Command)
 - Usage: `[p]settickettool createonreact <profile> <value> `
 - Slash Usage: `/settickettool createonreact <profile> <value> `
 - Checks: `server_only`

Create a ticket when the reaction 🎟️ is set on any message on the server.<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## settickettool categoryclose (Hybrid Command)
 - Usage: `[p]settickettool categoryclose <profile> <value> `
 - Slash Usage: `/settickettool categoryclose <profile> <value> `
 - Checks: `server_only`

Set the category where the closed tickets will be.<br/><br/>Default value: None<br/>Dev: <class 'discord.channel.CategoryChannel'>

## settickettool usercanclose (Hybrid Command)
 - Usage: `[p]settickettool usercanclose <profile> <value> `
 - Slash Usage: `/settickettool usercanclose <profile> <value> `
 - Checks: `server_only`

Can the author of the ticket, if he/she does not have a role set up for the system, close the ticket himself?<br/><br/>Default value: True<br/>Dev: <class 'bool'>

## settickettool custommodal (Hybrid Command)
 - Usage: `[p]settickettool custommodal <profile> <value> `
 - Slash Usage: `/settickettool custommodal <profile> <value> `
 - Checks: `server_only`

Ask a maximum of 5 questions to the user who opens a ticket, with a Discord Modal.<br/><br/>**Example:**<br/>```<br/>[p]settickettool customodal <profile><br/>- label: What is the problem?<br/>  style: 2 #  short = 1, paragraph = 2<br/>  required: True<br/>  default: None<br/>  placeholder: None<br/>  min_length: None<br/>  max_length: None<br/>```<br/><br/>Default value: None<br/>Dev: <class 'tickettool.utils.CustomModalConverter'>

## settickettool auditlogs (Hybrid Command)
 - Usage: `[p]settickettool auditlogs <profile> <value> `
 - Slash Usage: `/settickettool auditlogs <profile> <value> `
 - Checks: `server_only`

On all requests to the Discord api regarding the ticket (channel modification), does the bot send the name and id of the user who requested the action as the reason?<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## settickettool profilerename (Hybrid Command)
 - Usage: `[p]settickettool profilerename <old_profile> <profile> `
 - Slash Usage: `/settickettool profilerename <old_profile> <profile> `
 - Aliases: `renameprofile`
 - Checks: `server_only`

Rename an existing profile.

## settickettool profileslist (Hybrid Command)
 - Usage: `[p]settickettool profileslist `
 - Slash Usage: `/settickettool profileslist `
 - Aliases: `listprofiles`
 - Checks: `server_only`

List the existing profiles.

## settickettool adminrole (Hybrid Command)
 - Usage: `[p]settickettool adminrole <profile> <value> `
 - Slash Usage: `/settickettool adminrole <profile> <value> `
 - Checks: `server_only`

Users with this role will have full permissions for tickets, but will not be able to set up the cog.<br/><br/>Default value: None<br/>Dev: <class 'discord.role.Role'>

## settickettool supportrole (Hybrid Command)
 - Usage: `[p]settickettool supportrole <profile> <value> `
 - Slash Usage: `/settickettool supportrole <profile> <value> `
 - Checks: `server_only`

Users with this role will be able to participate and claim the ticket.<br/><br/>Default value: None<br/>Dev: <class 'discord.role.Role'>

## settickettool viewrole (Hybrid Command)
 - Usage: `[p]settickettool viewrole <profile> <value> `
 - Slash Usage: `/settickettool viewrole <profile> <value> `
 - Checks: `server_only`

Users with this role will only be able to read messages from the ticket, but not send them.<br/><br/>Default value: None<br/>Dev: <class 'discord.role.Role'>

## settickettool closeonleave (Hybrid Command)
 - Usage: `[p]settickettool closeonleave <profile> <value> `
 - Slash Usage: `/settickettool closeonleave <profile> <value> `
 - Checks: `server_only`

If a user leaves the server, will all their open tickets be closed?<br/><br/>If the user then returns to the server, even if their ticket is still open, the bot will not automatically add them to the ticket.<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## settickettool pingrole (Hybrid Command)
 - Usage: `[p]settickettool pingrole <profile> <value> `
 - Slash Usage: `/settickettool pingrole <profile> <value> `
 - Checks: `server_only`

This role will be pinged automatically when the ticket is created, but does not give any additional permissions.<br/><br/>Default value: None<br/>Dev: <class 'discord.role.Role'>

## settickettool ticketrole (Hybrid Command)
 - Usage: `[p]settickettool ticketrole <profile> <value> `
 - Slash Usage: `/settickettool ticketrole <profile> <value> `
 - Checks: `server_only`

This role will be added automatically to open tickets owners.<br/><br/>Default value: None<br/>Dev: <class 'discord.role.Role'>

## settickettool renamechanneldropdown (Hybrid Command)
 - Usage: `[p]settickettool renamechanneldropdown <profile> <value> `
 - Slash Usage: `/settickettool renamechanneldropdown <profile> <value> `
 - Checks: `server_only`

With Dropdowns feature, rename the ticket channel with chosen reason.<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## settickettool showsettings (Hybrid Command)
 - Usage: `[p]settickettool showsettings <profile> [with_dev=False] `
 - Slash Usage: `/settickettool showsettings <profile> [with_dev=False] `
 - Checks: `server_only`

Show all settings for the cog with defaults and values.

## settickettool profileclone (Hybrid Command)
 - Usage: `[p]settickettool profileclone <old_profile> <profile> `
 - Slash Usage: `/settickettool profileclone <old_profile> <profile> `
 - Aliases: `cloneprofile`
 - Checks: `server_only`

Clone an existing profile with his settings.

## settickettool logschannel (Hybrid Command)
 - Usage: `[p]settickettool logschannel <profile> <value> `
 - Slash Usage: `/settickettool logschannel <profile> <value> `
 - Checks: `server_only`

Set the channel where the logs will be saved.<br/><br/>Default value: None<br/>Dev: <class 'discord.channel.TextChannel'>

## settickettool nbmax (Hybrid Command)
 - Usage: `[p]settickettool nbmax <profile> <value> `
 - Slash Usage: `/settickettool nbmax <profile> <value> `
 - Checks: `server_only`

Sets the maximum number of open tickets a user can have on the system at any one time (for a profile only).<br/><br/>Default value: 5<br/>Dev: Range[int, 1, None]

## settickettool resetsetting (Hybrid Command)
 - Usage: `[p]settickettool resetsetting <profile> <setting> `
 - Slash Usage: `/settickettool resetsetting <profile> <setting> `
 - Checks: `server_only`

Reset a setting.

## settickettool forumchannel (Hybrid Command)
 - Usage: `[p]settickettool forumchannel <profile> <value> `
 - Slash Usage: `/settickettool forumchannel <profile> <value> `
 - Checks: `server_only`

Set the forum channel where the opened tickets will be, or a text channel to use private threads. If it's set, `category_open` and `category_close` will be ignored (except for existing tickets).<br/><br/>Default value: None<br/>Dev: typing.Union[discord.channel.ForumChannel, discord.channel.TextChannel]

## settickettool dynamicchannelname (Hybrid Command)
 - Usage: `[p]settickettool dynamicchannelname <profile> <value> `
 - Slash Usage: `/settickettool dynamicchannelname <profile> <value> `
 - Checks: `server_only`

Set the template that will be used to name the channel when creating a ticket.<br/><br/>`{ticket_id}` - Ticket number<br/>`{owner_display_name}` - user's nick or name<br/>`{owner_name}` - user's name<br/>`{owner_id}` - user's id<br/>`{server_name}` - server's name<br/>`{server_id}` - server's id<br/>`{bot_display_name}` - bot's nick or name<br/>`{bot_name}` - bot's name<br/>`{bot_id}` - bot's id<br/>`{shortdate}` - mm-dd<br/>`{longdate}` - mm-dd-yyyy<br/>`{time}` - hh-mm AM/PM according to bot host system time<br/>`{emoji}` - The open/closed emoji.<br/><br/>Default value: {emoji}-ticket-{ticket_id}<br/>Dev: <class 'str'>

## settickettool custommessage (Hybrid Command)
 - Usage: `[p]settickettool custommessage <profile> <value> `
 - Slash Usage: `/settickettool custommessage <profile> <value> `
 - Checks: `server_only`

This message will be sent in the ticket channel when the ticket is opened.<br/><br/>`{ticket_id}` - Ticket number<br/>`{owner_display_name}` - user's nick or name<br/>`{owner_name}` - user's name<br/>`{owner_id}` - user's id<br/>`{server_name}` - server's name<br/>`{server_id}` - server's id<br/>`{bot_display_name}` - bot's nick or name<br/>`{bot_name}` - bot's name<br/>`{bot_id}` - bot's id<br/>`{shortdate}` - mm-dd<br/>`{longdate}` - mm-dd-yyyy<br/>`{time}` - hh-mm AM/PM according to bot host system time<br/>`{emoji}` - The open/closed emoji.<br/><br/>Default value: None<br/>Dev: <class 'str'>

# ticket (Hybrid Command)
 - Usage: `[p]ticket `
 - Slash Usage: `/ticket `
 - Checks: `server_only`

Commands for using the Tickets system.<br/><br/>Many commands to manage tickets appear when you run help in a ticket channel.

## ticket export (Hybrid Command)
 - Usage: `[p]ticket export `
 - Slash Usage: `/ticket export `
 - Checks: `TicketTool and server_only`

Export all the messages of an existing Ticket in html format.<br/>Please note: all attachments and user avatars are saved with the Discord link in this file.

## ticket open (Hybrid Command)
 - Usage: `[p]ticket open [reason] `
 - Slash Usage: `/ticket open [reason] `
 - Aliases: `reopen`
 - Checks: `TicketTool and server_only`

Open an existing Ticket.

## ticket delete (Hybrid Command)
 - Usage: `[p]ticket delete [confirmation=False] [reason] `
 - Slash Usage: `/ticket delete [confirmation=False] [reason] `
 - Checks: `TicketTool and server_only`

Delete an existing Ticket.<br/>If a log channel is defined, an html file containing all the messages of this ticket will be generated.<br/>(Attachments are not supported, as they are saved with their Discord link)

## ticket list (Hybrid Command)
 - Usage: `[p]ticket list <profile> <status> <owner> `
 - Slash Usage: `/ticket list <profile> <status> <owner> `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

List the existing Tickets for a profile. You can provide a status and/or a ticket owner.

## ticket rename (Hybrid Command)
 - Usage: `[p]ticket rename <new_name> [reason] `
 - Slash Usage: `/ticket rename <new_name> [reason] `
 - Checks: `TicketTool and server_only`

Rename an existing Ticket.

## ticket addmember (Hybrid Command)
 - Usage: `[p]ticket addmember <members> `
 - Slash Usage: `/ticket addmember <members> `
 - Aliases: `add`
 - Checks: `TicketTool and server_only`

Add a member to an existing Ticket.

## ticket create (Hybrid Command)
 - Usage: `[p]ticket create [profile=None] [reason] `
 - Slash Usage: `/ticket create [profile=None] [reason] `
 - Aliases: `+`
 - Checks: `server_only`

Create a Ticket.<br/><br/>If only one profile has been created on this server, you don't need to specify its name.

## ticket lock (Hybrid Command)
 - Usage: `[p]ticket lock [confirmation=None] [reason] `
 - Slash Usage: `/ticket lock [confirmation=None] [reason] `
 - Checks: `TicketTool and server_only`

Lock an existing Ticket.

## ticket unclaim (Hybrid Command)
 - Usage: `[p]ticket unclaim [reason] `
 - Slash Usage: `/ticket unclaim [reason] `
 - Checks: `TicketTool and server_only`

Unclaim an existing Ticket.

## ticket claim (Hybrid Command)
 - Usage: `[p]ticket claim [member=None] [reason] `
 - Slash Usage: `/ticket claim [member=None] [reason] `
 - Checks: `TicketTool and server_only`

Claim an existing Ticket.

## ticket owner (Hybrid Command)
 - Usage: `[p]ticket owner <new_owner> [reason] `
 - Slash Usage: `/ticket owner <new_owner> [reason] `
 - Checks: `TicketTool and server_only`

Change the owner of an existing Ticket.

## ticket removemember (Hybrid Command)
 - Usage: `[p]ticket removemember <members> `
 - Slash Usage: `/ticket removemember <members> `
 - Aliases: `remove`
 - Checks: `TicketTool and server_only`

Remove a member to an existing Ticket.

## ticket close (Hybrid Command)
 - Usage: `[p]ticket close [confirmation=None] [reason] `
 - Slash Usage: `/ticket close [confirmation=None] [reason] `
 - Checks: `TicketTool and server_only`

Close an existing Ticket.

## ticket unlock (Hybrid Command)
 - Usage: `[p]ticket unlock [reason] `
 - Slash Usage: `/ticket unlock [reason] `
 - Checks: `TicketTool and server_only`

Unlock an existing locked Ticket.

