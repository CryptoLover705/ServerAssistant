# Reminders Help

Don't forget anything anymore! Reminders in DMs, channels, FIFO commands scheduler, say scheduler... With 'Me Too', snooze and buttons.

# remindme (Hybrid Command)
 - Usage: `[p]remindme <time> [message_or_text] `
 - Slash Usage: `/remindme <time> [message_or_text] `

Create a reminder with optional reminder text or message.<br/><br/>The specified time can be fuzzy parsed or use the kwargs `in`, `on` and `every` to find a repeat rule and your text.<br/>You don't have to put quotes around the time argument. For more precise parsing, you can place quotation marks around the text. Put quotation marks around the time too, if it contains spaces.<br/>Use `[p]reminder timetips` to display tips for time parsing.<br/><br/>**Examples:**<br/>- `[p]remindme in 8min45sec to do that thing`<br/>- `[p]remindme to water my plants in 2 hours`<br/>- `[p]remindme in 3 days`<br/>- `[p]remindme 8h`<br/>- `[p]remindme every 1 week to take out the trash`<br/>- `[p]remindme in 1 hour <message_link>`<br/>- `[p]remindme at 10h to add some feature to my codes`

# remind (Hybrid Command)
 - Usage: `[p]remind <destination> <targets> <time> [message_or_text] `
 - Slash Usage: `/remind <destination> <targets> <time> [message_or_text] `
 - Checks: `server_only`

Create a reminder with optional reminder text or message, in a channel with an user/role ping.<br/><br/>The specified time can be fuzzy parsed or use the kwargs `in`, `on` and `every` to find a repeat rule and your text.<br/>You don't have to put quotes around the time argument. For more precise parsing, you can place quotation marks around the text. Put quotation marks around the time too, if it contains spaces.<br/>Use `[p]reminder timetips` to display tips for time parsing.<br/><br/>Examples:<br/>- `[p]remind #destination @user1 @user2 @user2 in 2 hours to buy a gift`

# reminder (Hybrid Command)
 - Usage: `[p]reminder `
 - Slash Usage: `/reminder `
 - Aliases: `reminders`

List, edit and delete existing reminders, or create FIFO/commands or Say reminders.

## reminder list (Hybrid Command)
 - Usage: `[p]reminder list [card=False] [content_type=None] [sort=expire] `
 - Slash Usage: `/reminder list [card=False] [content_type=None] [sort=expire] `

List your existing reminders.<br/><br/>Sort options:<br/>- `expire`: Display them in order of next triggering.<br/>- `created`: Display them in order of creating.<br/>- `id`: Display them in order of their ID.

## reminder clear (Hybrid Command)
 - Usage: `[p]reminder clear [confirmation=False] `
 - Slash Usage: `/reminder clear [confirmation=False] `

Clear all your existing reminders.

## reminder edit (Hybrid Command)
 - Usage: `[p]reminder edit <reminder> `
 - Slash Usage: `/reminder edit <reminder> `
 - Aliases: `info`

Edit an existing Reminder from its ID.<br/><br/>- Use `last` to edit your last created reminder.<br/>- Use `next` to edit your next triggered reminder.

## reminder timetips (Hybrid Command)
 - Usage: `[p]reminder timetips `
 - Slash Usage: `/reminder timetips `
 - Aliases: `parsingtips`

Show time parsing tips.

## reminder remove (Hybrid Command)
 - Usage: `[p]reminder remove <reminders> `
 - Slash Usage: `/reminder remove <reminders> `
 - Aliases: `delete and -`

Remove existing Reminder(s) from their IDs.<br/><br/>- Use `last` to remove your last created reminder.<br/>- Use `next` to remove your next triggered reminder.

## reminder say (Hybrid Command)
 - Usage: `[p]reminder say <destination> <time> <text> `
 - Slash Usage: `/reminder say <destination> <time> <text> `
 - Restricted to: `GUILD_OWNER`
 - Checks: `server_only`

Create a reminder who will say/send text.<br/><br/>The specified time can be fuzzy parsed or use the kwargs `in`, `on` and `every` to find a repeat rule and your text.<br/>You don't have to put quotes around the time argument. For more precise parsing, you can place quotation marks around the text. Put quotation marks around the time too, if it contains spaces.<br/>Use `[p]reminder timetips` to display tips for time parsing.<br/><br/>Examples:<br/>- `[p]reminder say #destination "at 9h every day" Hello everyone!

## reminder text (Hybrid Command)
 - Usage: `[p]reminder text <reminder> <text> `
 - Slash Usage: `/reminder text <reminder> <text> `

Edit the text of an existing Reminder from its ID.<br/><br/>- Use `last` to edit your last created reminder.<br/>- Use `next` to edit your next triggered reminder.

## reminder expires (Hybrid Command)
 - Usage: `[p]reminder expires <reminder> <time> `
 - Slash Usage: `/reminder expires <reminder> <time> `
 - Aliases: `expiresat`

Edit the expires time of an existing Reminder from its ID.<br/><br/>- Use `last` to edit your last created reminder.<br/>- Use `next` to edit your next triggered reminder.<br/>It's the same converter as for creation, but without the option of repetition.

## reminder repeat (Hybrid Command)
 - Usage: `[p]reminder repeat <reminder> <repeat> `
 - Slash Usage: `/reminder repeat <reminder> <repeat> `

Edit the repeat of an existing Reminder from its ID.<br/><br/>- Use `last` to edit your last created reminder.<br/>- Use `next` to edit your next triggered reminder.<br/><br/>Allowed **intervals** are:<br/>• `years`/`year`/`y`<br/>• `months`/`month`/`mo`<br/>• `weeks`/`week`/`w`<br/>• `days`/`day`/`d`<br/>• `hours`/`hour`/`hrs`/`hr`/`h`<br/>• `minutes`/`minute`/`mins`/`min`/`m`<br/><br/>You can combine **relative intervals** like this:<br/>• `1y 1mo 2 days -5h`

## reminder fifo (Hybrid Command)
 - Usage: `[p]reminder fifo <destination> <time> <command> `
 - Slash Usage: `/reminder fifo <destination> <time> <command> `
 - Restricted to: `ADMIN`
 - Aliases: `command`
 - Checks: `server_only`

Create a FIFO/command reminder. The chosen command will be executed with you as invoker. Don't provide the prefix.<br/><br/>The specified time can be fuzzy parsed or use the kwargs `in`, `on` and `every` to find a repeat rule and your text.<br/>You don't have to put quotes around the time argument. For more precise parsing, you can place quotation marks around the text. Put quotation marks around the time too, if it contains spaces.<br/>Use `[p]reminder timetips` to display tips for time parsing.<br/><br/>Examples:<br/>- `[p]reminder fifo #destination "at 10h every day" ping

## reminder timezone (Hybrid Command)
 - Usage: `[p]reminder timezone <timezone> `
 - Slash Usage: `/reminder timezone <timezone> `

Set your timezone for the time converter.<br/><br/>Timezone should be specified in the format: `Continent/City`.<br/>Example: `Europe/Paris`, `America/New_York`...<br/>You can find a list of valid timezones at: https://timezonedb.com/time-zones.

# setreminders (Hybrid Command)
 - Usage: `[p]setreminders `
 - Slash Usage: `/setreminders `
 - Restricted to: `BOT_OWNER`

Configure Reminders.

## setreminders minimumrepeat (Hybrid Command)
 - Usage: `[p]setreminders minimumrepeat <value> `
 - Slash Usage: `/setreminders minimumrepeat <value> `

Change the minimum minutes number for a repeat time.<br/><br/>Default value: 60<br/>Dev: Range[int, 10, None]

## setreminders showsettings (Hybrid Command)
 - Usage: `[p]setreminders showsettings [with_dev=False] `
 - Slash Usage: `/setreminders showsettings [with_dev=False] `

Show all settings for the cog with defaults and values.

## setreminders maximumuserreminders (Hybrid Command)
 - Usage: `[p]setreminders maximumuserreminders <value> `
 - Slash Usage: `/setreminders maximumuserreminders <value> `
 - Aliases: `maxuserreminders`

Change the reminders limit for each user (except bot owners).<br/><br/>Default value: 20<br/>Dev: Range[int, 1, 125]

## setreminders fifoallowed (Hybrid Command)
 - Usage: `[p]setreminders fifoallowed <value> `
 - Slash Usage: `/setreminders fifoallowed <value> `

Allow or deny commands reminders for users (except bot owners).<br/><br/>Default value: False<br/>Dev: <class 'bool'>

## setreminders modalconfig (Hybrid Command)
 - Usage: `[p]setreminders modalconfig [confirmation=False] `
 - Slash Usage: `/setreminders modalconfig [confirmation=False] `
 - Aliases: `configmodal`

Set all settings for the cog with a Discord Modal.

## setreminders repeatallowed (Hybrid Command)
 - Usage: `[p]setreminders repeatallowed <value> `
 - Slash Usage: `/setreminders repeatallowed <value> `

Enable or disabled repeat option for users (except bot owners).<br/><br/>Default value: True<br/>Dev: <class 'bool'>

## setreminders creationview (Hybrid Command)
 - Usage: `[p]setreminders creationview <value> `
 - Slash Usage: `/setreminders creationview <value> `

Send Creation view/buttons when reminders creation.<br/><br/>Default value: True<br/>Dev: <class 'bool'>

## setreminders migratefromfifo (Hybrid Command)
 - Usage: `[p]setreminders migratefromfifo `
 - Slash Usage: `/setreminders migratefromfifo `
 - Aliases: `migratefromfox`

Migrate Reminders from FIFO by Fox.

## setreminders clearuserreminders (Hybrid Command)
 - Usage: `[p]setreminders clearuserreminders <user> [confirmation=False] `
 - Slash Usage: `/setreminders clearuserreminders <user> [confirmation=False] `

Clear all existing reminders for a user.

## setreminders migratefromremindme (Hybrid Command)
 - Usage: `[p]setreminders migratefromremindme `
 - Slash Usage: `/setreminders migratefromremindme `
 - Aliases: `migratefrompcx`

Migrate Reminders from RemindMe by PhasecoreX.

## setreminders resetsetting (Hybrid Command)
 - Usage: `[p]setreminders resetsetting <setting> `
 - Slash Usage: `/setreminders resetsetting <setting> `

Reset a setting.

## setreminders metoo (Hybrid Command)
 - Usage: `[p]setreminders metoo <value> `
 - Slash Usage: `/setreminders metoo <value> `

Show a `Me too` button in reminders.<br/><br/>Default value: True<br/>Dev: <class 'bool'>

## setreminders snoozeview (Hybrid Command)
 - Usage: `[p]setreminders snoozeview <value> `
 - Slash Usage: `/setreminders snoozeview <value> `

Send Snooze view/buttons when reminders sending.<br/><br/>Default value: True<br/>Dev: <class 'bool'>

