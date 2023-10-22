# AutoMod Help

Interact with and view discord's automod

# automod (Hybrid Command)
 - Usage: `[p]automod `
 - Slash Usage: `/automod `
 - Checks: `server_only`

Commnads for interacting with automod

## automod rules (Hybrid Command)
 - Usage: `[p]automod rules `
 - Slash Usage: `/automod rules `
 - Restricted to: `MOD`
 - Aliases: `list, rule, and view`

View the servers current automod rules

## automod create (Hybrid Command)
 - Usage: `[p]automod create `
 - Slash Usage: `/automod create `
 - Restricted to: `ADMIN`
 - Aliases: `c`

Create automod rules, triggers, and actions

### automod create rule (Hybrid Command)
 - Usage: `[p]automod create rule <name> <rule> `
 - Slash Usage: `/automod create rule <name> <rule> `

Create an automod rule in the server<br/><br/>Usage:<br/>- `trigger:` The name of a saved trigger.<br/>- `actions:` The name(s) of saved actions.<br/>- `enabled:` yes/true/t to enable this rule right away.<br/>- `roles:` The roles that are exempt from this rule.<br/>- `channels:` The channels that are exempt from this rule.<br/>- `reason:` An optional reason for creating this rule.<br/><br/>Example:<br/>    `[p]automod create rule trigger: mytrigger actions: timeoutuser notifymods enabled: true roles: @mods`<br/>    Will create an automod rule with the saved trigger `mytrigger` and<br/>    the saved actions `timeoutuser` and `notifymods`.

### automod create action (Hybrid Command)
 - Usage: `[p]automod create action <name> <action> `
 - Slash Usage: `/automod create action <name> <action> `
 - Aliases: `a`

Create a saved action for use in automod Rules.<br/><br/>- `<name>` The name of this action for reference later.<br/>Usage: `<action>`<br/>- `message:` The message to send to a user when triggered.<br/>- `channel:` The channel to send a notification to.<br/>- `duration:` How long to timeout the user for. Max 28 days.<br/>Only one of these options can be applied at a time.<br/>Examples:<br/>    `[p]automod create action grumpyuser message: You're being too grumpy`<br/>    `[p]automod create action notifymods channel: #modlog`<br/>    `[p]automod create action 2hrtimeout duration: 2 hours`

### automod create trigger (Hybrid Command)
 - Usage: `[p]automod create trigger <name> <trigger> `
 - Slash Usage: `/automod create trigger <name> <trigger> `

Create a saved trigger for use in automod Rules.<br/><br/>- `<name>` The name of this trigger for reference later.<br/>Usage: `<trigger>`<br/>- `allows:` A space separated list of words to allow.<br/>- `keywords:` A space separated list of words to filter.<br/>- `mentions:` The number of user/role mentions that would trigger this rule (0-50).<br/>- `presets:` Any combination of discord presets. e.g. `profanity`, `sexual_content`, or `slurs`.<br/>- `regex:` A space separated list of regex patterns to include.<br/>Note: If you want to use `mentions` you cannot also use `presets`, `keywords` or<br/>`regex` in the same trigger. Likewise if you use any `presets` you cannot<br/>use `keywords`, `regex`, or `mentions`.<br/>Examples:<br/>    `[p]automod create trigger mytrigger regex: ^b(a|@)dw(o|0)rd(s|5)$`

## automod triggers (Hybrid Command)
 - Usage: `[p]automod triggers `
 - Slash Usage: `/automod triggers `
 - Aliases: `trigger`

View the servers saved automod triggers

## automod actions (Hybrid Command)
 - Usage: `[p]automod actions `
 - Slash Usage: `/automod actions `
 - Aliases: `action`

View the servers saved automod actions

