# Birthday Help

Birthdays<br/><br/>Set yours and get a message and role on your birthday!

## birthdaydebug upcoming
 - Usage: `[p]birthdaydebug upcoming `



# bdset
 - Usage: `[p]bdset `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Birthday management commands for admins.<br/><br/>Looking to set your own birthday? Use `[p]birthday set` or `[p]bday set`.

## bdset forceremove
 - Usage: `[p]bdset forceremove <user> `

Force-remove a user's birthday.

## bdset rolemention
 - Usage: `[p]bdset rolemention <value> `

Choose whether or not to allow role mentions in birthday messages.<br/><br/>By default role mentions are suppressed.<br/><br/>To allow role mentions in the birthday message, run `[p]bdset rolemention true`.<br/>Disable them with `[p]bdset rolemention true`

## bdset role
 - Usage: `[p]bdset role <role> `

Set the role that will be given to the user on their birthday.<br/><br/>You can give the exact name or a mention.<br/><br/>**Example:**<br/>- `[p]bdset role @Birthday` - set the role to @Birthday<br/>- `[p]bdset role Birthday` - set the role to @Birthday without a mention<br/>- `[p]bdset role 418058139913063657` - set the role with an ID

## bdset forceset
 - Usage: `[p]bdset forceset <user> <birthday> `

Force-set a specific user's birthday.<br/><br/>You can @ mention any user or type out their exact name. If you're typing out a name with<br/>spaces, make sure to put quotes around it (`"`).<br/><br/>**Examples:**<br/>- `[p]bdset set @User 1-1-2000` - set the birthday of `@User` to 1/1/2000<br/>- `[p]bdset set User 1/1` - set the birthday of `@User` to 1/1/2000<br/>- `[p]bdset set "User with spaces" 1-1` - set the birthday of `@User with spaces`<br/>    to 1/1<br/>- `[p]bdset set 354125157387344896 1/1/2000` - set the birthday of `354125157387344896`<br/>    to 1/1/2000

## bdset time
 - Usage: `[p]bdset time <time> `

Set the time of day for the birthday message.<br/><br/>Minutes are ignored.<br/><br/>**Examples:**<br/>- `[p]bdset time 7:00` - set the time to 7:45AM UTC<br/>- `[p]bdset time 12AM` - set the time to midnight UTC<br/>- `[p]bdset time 3PM` - set the time to 3:00PM UTC

## bdset stop
 - Usage: `[p]bdset stop `

Stop the cog from sending birthday messages and giving roles in the server.

## bdset msgwithyear
 - Usage: `[p]bdset msgwithyear <message> `

Set the message to send when the user did provide a year.<br/><br/>If you would like to mention a role, you will need to run `[p]bdset rolemention true`<br/><br/>**Placeholders:**<br/>- `{name}` - the user's name<br/>- `{mention}` - an @ mention of the user<br/>- `{new_age}` - the user's new age<br/><br/>    All the placeholders are optional.<br/><br/>**Examples:**<br/>- `[p]bdset msgwithyear {mention} has turned {new_age}, happy birthday!`<br/>- `[p]bdset msgwithyear {name} is {new_age} today! Happy birthday {mention}!`

## bdset interactive
 - Usage: `[p]bdset interactive `

Start interactive setup

## bdset zemigrate
 - Usage: `[p]bdset zemigrate `
 - Restricted to: `BOT_OWNER`

Import data from ZeCogs'/flare's fork of Birthdays cog

## bdset settings
 - Usage: `[p]bdset settings `

View your current settings

## bdset channel
 - Usage: `[p]bdset channel <channel> `

Set the channel where the birthday message will be sent.<br/><br/>**Example:**<br/>- `[p]bdset channel #birthdays` - set the channel to #birthdays

## bdset msgwithoutyear
 - Usage: `[p]bdset msgwithoutyear <message> `

Set the message to send when the user did not provide a year.<br/><br/>If you would like to mention a role, you will need to run `[p]bdset rolemention true`.<br/><br/>**Placeholders:**<br/>- `{name}` - the user's name<br/>- `{mention}` - an @ mention of the user<br/><br/>    All the placeholders are optional.<br/><br/>**Examples:**<br/>- `[p]bdset msgwithoutyear Happy birthday {mention}!`<br/>- `[p]bdset msgwithoutyear {mention}'s birthday is today! Happy birthday {name}.`

# birthday (Hybrid Command)
 - Usage: `[p]birthday `
 - Slash Usage: `/birthday `
 - Aliases: `bday`
 - Checks: `server_only`

Set and manage your birthday.

## birthday remove (Hybrid Command)
 - Usage: `[p]birthday remove `
 - Slash Usage: `/birthday remove `
 - Aliases: `delete and del`

Remove your birthday.

## birthday set (Hybrid Command)
 - Usage: `[p]birthday set <birthday> `
 - Slash Usage: `/birthday set <birthday> `
 - Aliases: `add`

Set your birthday.<br/><br/>You can optionally add in the year, if you are happy to share this.<br/><br/>If you use a date in the format xx/xx/xx or xx-xx-xx MM-DD-YYYY is assumed.<br/><br/>**Examples:**<br/>- `[p]bday set 24th September`<br/>- `[p]bday set 24th Sept 2002`<br/>- `[p]bday set 9/24/2002`<br/>- `[p]bday set 9-24-2002`<br/>- `[p]bday set 9-24`

## birthday upcoming (Hybrid Command)
 - Usage: `[p]birthday upcoming [days=7] `
 - Slash Usage: `/birthday upcoming [days=7] `

View upcoming birthdays, defaults to 7 days.<br/><br/>**Examples:**<br/>- `[p]birthday upcoming` - default of 7 days<br/>- `[p]birthday upcoming 14` - 14 days

