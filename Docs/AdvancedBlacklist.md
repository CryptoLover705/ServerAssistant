# AdvancedBlacklist Help

An advanced blacklist cog for more control over your blacklist

# whitelist
 - Usage: `[p]whitelist `
 - Restricted to: `BOT_OWNER`
 - Aliases: `allowlist`

Manage [botname]'s whitelist

## whitelist list
 - Usage: `[p]whitelist list `

List the users on [botname]'s whitelist

## whitelist reason
 - Usage: `[p]whitelist reason <user> <reason> `

Edit the reason for a whitelisted user.

## whitelist add
 - Usage: `[p]whitelist add <users> [reason] `

Add a user to the whitelist. These users cannot be bots.<br/><br/>**Arguments**<br/>    - `users` The users to add to the whitelist.<br/>    - `reason` The reason for adding these users to the whitelist. This argument is optional.

## whitelist remove
 - Usage: `[p]whitelist remove <users> `
 - Aliases: `del, delete, and rm`

Remove users from the whitelist.<br/><br/>**Arguments**<br/>    - `users` The users to remove from the whitelist.

## whitelist clear
 - Usage: `[p]whitelist clear [confirm=False] `

Clear the whitelist

# localwhitelist
 - Usage: `[p]localwhitelist `
 - Restricted to: `ADMIN`
 - Aliases: `localallowlist`
 - Checks: `server_only`

Manage the local whitelist for your server.

## localwhitelist reason
 - Usage: `[p]localwhitelist reason <member_or_role> <reason> `

Edit the reason for a locally whitelisted member/role<br/><br/>**Arguments**<br/>    - `member_or_role` The member/role to edit the reason of. Members cannot be a bot.<br/>    - `reason` The new reason for locally whitelisting the member/role.

## localwhitelist clear
 - Usage: `[p]localwhitelist clear [confirm=False] `

Clear the local whitelist

## localwhitelist remove
 - Usage: `[p]localwhitelist remove <member_or_roles> `
 - Aliases: `del and delete`

Remove members/roles from the local whitelist<br/><br/>**Arguments**<br/>    - `members` The members/roles to remove from the local whitelist.

## localwhitelist add
 - Usage: `[p]localwhitelist add <members_or_roles> [reason] `

Add members and roles to the local whitelist.<br/><br/>This will disallow anyone not in the local whitelist or not in a role in the local whitelist from using [botname].<br/><br/>Note, if you are an admin you must add yourself to the localwhitelist as to not lock yourself out of [botname].<br/><br/>**Arguments**<br/>    - `members_or_roles` The members/roles to add to the whitelist. Members cannot be bots.<br/>    - `reason` The reason for adding these members/roles to the whitelist. This argument is optional.

## localwhitelist list
 - Usage: `[p]localwhitelist list `

List the locally whitelisted members/roles

# blacklist
 - Usage: `[p]blacklist `
 - Restricted to: `BOT_OWNER`
 - Aliases: `blocklist`

Manage [botname]'s blacklist

## blacklist log
 - Usage: `[p]blacklist log `

Manage the log settings for AdvancedBlacklist.

### blacklist log remove
 - Usage: `[p]blacklist log remove `

Remove the channel for logging black/whitelistings

### blacklist log set
 - Usage: `[p]blacklist log set <channel> `

Set the channel for logging black/whitelistings<br/><br/>**Arguments**<br/>    - `channel` The channel or thread to use for logging.

## blacklist list
 - Usage: `[p]blacklist list `

List the users in the blacklist.

## blacklist clear
 - Usage: `[p]blacklist clear [confirm=False] `

Clear the blacklist

## blacklist add
 - Usage: `[p]blacklist add <users> [reason] `

Add users to the blacklist.<br/><br/>**Arguments**<br/>    - `users` The users to add to the blacklist. These cannot be bots.<br/>    - `reason` The reason for adding these users to the blacklist. This is optional.

## blacklist reason
 - Usage: `[p]blacklist reason <user> <reason> `

Edit the reason for a user in the blacklist.<br/><br/>**Arguments**<br/>    - `user` The user to edit the reason of.<br/>    - `reason` The new reason for blacklisting this user.

## blacklist remove
 - Usage: `[p]blacklist remove <users> `
 - Aliases: `del, delete, and rm`

Remove users from the blacklist.<br/><br/>**Arguments**<br/>    - `users` The users to remove from the blacklist.

# localblacklist
 - Usage: `[p]localblacklist `
 - Restricted to: `ADMIN`
 - Aliases: `localblocklist`
 - Checks: `server_only`

Manage the local blacklist for your server.

## localblacklist add
 - Usage: `[p]localblacklist add <members_or_roles> [reason] `

Add users to the local blacklist<br/><br/>**Arguments**<br/>    - `members_or_roles` The members or roles to add to the local blacklist. Members cannot be bots<br/>    - `reason` The reason for adding these members/roles to the blacklist. This is optional

## localblacklist list
 - Usage: `[p]localblacklist list `

List the members and roles in the local blacklist.

## localblacklist reason
 - Usage: `[p]localblacklist reason <member_or_role> <reason> `

Edit the reason for a member or role in the local blacklist.<br/><br/>**Arguments**<br/>    - `member_or_role` The member/role to edit the reason of. Members cannot be a bot.<br/>    - `reason` The new reason for blacklisting the member/role.

## localblacklist clear
 - Usage: `[p]localblacklist clear [confirm=False] `

Clear the local blacklist

## localblacklist remove
 - Usage: `[p]localblacklist remove <users> `
 - Aliases: `del, delete, and rm`

Remove users from the local blacklist.<br/><br/>**Arguments**<br/>    - `users` The users to remove from the local blacklist.

