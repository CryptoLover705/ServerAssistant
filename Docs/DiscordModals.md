# DiscordModals Help

A cog to use Discord Modals, forms with graphic interface!

# discordmodals (Hybrid Command)
 - Usage: `[p]discordmodals `
 - Slash Usage: `/discordmodals `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Group of commands to use DiscordModals.

## discordmodals add (Hybrid Command)
 - Usage: `[p]discordmodals add <message> <argument> `
 - Slash Usage: `/discordmodals add <message> <argument> `
 - Aliases: `+`
 - Checks: `server_only`

Add a Modal for a message.<br/><br/>Use YAML syntax to set up everything.<br/><br/>**Example:**<br/>```<br/>[p]discordmodals add <message><br/>title: Report a bug<br/>button:<br/>  label: Report<br/>  emoji: ⚠️<br/>  style: 4 # blurple = 1, grey = 2, green = 3, red = 4<br/>modal:<br/>  - label: What is the problem?<br/>    style: 2 # short = 1, paragraph = 2<br/>    required: True<br/>    default: None<br/>    placeholder: None<br/>    min_length: None<br/>    max_length: None<br/>channel: general # id, mention, name<br/>anonymous: False<br/>messages:<br/>  error: Error!<br/>  submit: Form submitted.<br/>pings: user1, user2, role1, role2<br/>whitelist_roles: role1, role2<br/>blacklist_roles: role3, role4<br/>```<br/>The `emoji`, `style`, `required`, `default`, `placeholder`, `min_length`, `max_length`, `channel`, `anonymous`, `messages`, `pings`, `whitelist_roles` and `blacklist_roles` are not required.

## discordmodals remove (Hybrid Command)
 - Usage: `[p]discordmodals remove <message> `
 - Slash Usage: `/discordmodals remove <message> `
 - Aliases: `-`
 - Checks: `server_only`

Remove a Modal for a message.

