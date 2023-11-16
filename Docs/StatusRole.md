# StatusRole Help

Roles for Certain Custom Statuses.<br/><br/>Assign roles to users for the duration in which they have certain custom statuses.

# statusrole
 - Usage: `[p]statusrole `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

StatusRole Settings

## statusrole add
 - Usage: `[p]statusrole add <pair_name> <role> <statuses_to_match> `

Add a role to be assigned to users with any of the input status(es) (list of words separated by spaces).

## statusrole edit
 - Usage: `[p]statusrole edit `

Edit a StatusRole

### statusrole edit emoji
 - Usage: `[p]statusrole edit emoji <pair_name> [emoji=None] `

Edit a StatusRole's required emoji (you can also enter True for any emoji in this server, or leave blank to remove).

### statusrole edit toggle
 - Usage: `[p]statusrole edit toggle <pair_name> <true_or_false> `

Toggle a StatusRole assignment temporarily.

### statusrole edit role
 - Usage: `[p]statusrole edit role <pair_name> <role> `

Edit a StatusRole's role to be assigned.

### statusrole edit status
 - Usage: `[p]statusrole edit status <pair_name> <statuses_to_match> `

Edit a StatusRole's status(es) to be matched (list of words separated by spaces, leave blank to remove text status matching).

## statusrole forcecheck
 - Usage: `[p]statusrole forcecheck <statusroles> `

Force a manual check of every user on this server for the provided StatusRoles.

## statusrole remove
 - Usage: `[p]statusrole remove <pair_name> <enter_true_to_confirm> `
 - Aliases: `delete`

Remove a StatusRole from being assigned.

## statusrole logchannel
 - Usage: `[p]statusrole logchannel [channel=None] `

Set the StatusRole log channel (leave blank to disable logs).

## statusrole view
 - Usage: `[p]statusrole view `
 - Aliases: `list`

View the StatusRole settings for this server.

## statusrole blacklist
 - Usage: `[p]statusrole blacklist `
 - Restricted to: `ADMIN`
 - Aliases: `blocklist`
 - Checks: `server_only`

Manage statusrole blacklist.

### statusrole blacklist list
 - Usage: `[p]statusrole blacklist list `
 - Aliases: `view`

Check the blacklisted users list.

### statusrole blacklist add
 - Usage: `[p]statusrole blacklist add <user> `
 - Aliases: `+ and create`

Add a user to the status role blacklist.

### statusrole blacklist remove
 - Usage: `[p]statusrole blacklist remove <user> `
 - Aliases: `- and delete`

Remove a user from the status role blacklist.

