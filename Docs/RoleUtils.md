# RoleUtils Help

Useful role commands.<br/><br/>Includes massroling, role targeting, and reaction roles.

# reactrole
 - Usage: `[p]reactrole `

Base command for Reaction Role management.

## reactrole list
 - Usage: `[p]reactrole list `

View the reaction roles on this server.

## reactrole create
 - Usage: `[p]reactrole create <emoji_role_groups> [channel=None] [color=None] [name] `

Create a reaction role.<br/><br/>Emoji and role groups should be seperated by a ';' and have no space.<br/><br/>Example:<br/>    - [p]reactrole create 🎃;@SpookyRole 🅱️;MemeRole #role_channel Red

## reactrole delete
 - Usage: `[p]reactrole delete <message> `
 - Aliases: `remove`

Delete an entire reaction role for a message.

### reactrole delete bind
 - Usage: `[p]reactrole delete bind <message> <emoji> `

Delete an emoji-role bind for a reaction role.

## reactrole bind
 - Usage: `[p]reactrole bind <message> <emoji> <role> `
 - Checks: `bot_has_server_permissions`

Bind a reaction role to an emoji on a message.

# role
 - Usage: `[p]role <member> <role> `
 - Checks: `server_only`

Base command for modifying roles.<br/><br/>Invoking this command will add or remove the given role from the member, depending on whether they already had it.

## role rall
 - Usage: `[p]role rall <role> `
 - Aliases: `removeall`

Remove a role from all members of the server.

## role addmulti
 - Usage: `[p]role addmulti <role> <members> `

Add a role to multiple members.

## role name
 - Usage: `[p]role name <role> <name> `

Change a role's name.

## role humans
 - Usage: `[p]role humans <role> `

Add a role to all humans (non-bots) in the server.

## role target
 - Usage: `[p]role target `
 - Checks: `targeter_cog`

Modify roles using 'targeting' args.<br/><br/>An explanation of Targeter and test commands to preview the members affected can be found with `[p]target`.

### role target remove
 - Usage: `[p]role target remove <role> <args> `

Remove a role from members using targeting args.<br/><br/>An explanation of Targeter and test commands to preview the members affected can be found with `[p]target`.

### role target add
 - Usage: `[p]role target add <role> <args> `

Add a role to members using targeting args.<br/><br/>An explanation of Targeter and test commands to preview the members affected can be found with `[p]target`.

## role info
 - Usage: `[p]role info <role> `

Get information about a role.

## role uniquemembers
 - Usage: `[p]role uniquemembers <roles> `
 - Aliases: `um`

View the total unique members between multiple roles.

## role color
 - Usage: `[p]role color <role> <color> `
 - Aliases: `colour`

Change a role's color.

## role removemulti
 - Usage: `[p]role removemulti <role> <members> `

Remove a role from multiple members.

## role bots
 - Usage: `[p]role bots <role> `

Add a role to all bots in the server.

## role hoist
 - Usage: `[p]role hoist <role> [hoisted=None] `

Toggle whether a role should appear seperate from other roles.

## role custom
 - Usage: `[p]role custom <users> <flags> `

Add/Remove roles to one or more users<br/><br/>You cannot add and remove the same Role<br/><br/>**Example:**<br/>- `[p]role custom inthedark.org --add role1 --remove role2`<br/>- `[p] role custom inthedark.org --add role1 "role to remove"`

## role rhumans
 - Usage: `[p]role rhumans <role> `

Remove a role from all humans (non-bots) in the server.

## role all
 - Usage: `[p]role all <role> `

Add a role to all members of the server.

## role rbots
 - Usage: `[p]role rbots <role> `

Remove a role from all bots in the server.

## role add
 - Usage: `[p]role add <member> <role> `

Add a role to a member.

## role in
 - Usage: `[p]role in <target_role> <add_role> `

Add a role to all members of a another role.

## role create
 - Usage: `[p]role create [color=#000000] [hoist=False] [name] `

Creates a role.<br/><br/>Color and whether it is hoisted can be specified.

## role members
 - Usage: `[p]role members <role> [formatting] `
 - Aliases: `dump`

Sends a list of members in a role.<br/><br/>You can supply a custom formatting tagscript for each member.<br/>The [member](https://seina-cogs.readthedocs.io/en/latest/tags/default_variables.html#author-block) block is available to use, found on the [TagScript documentation](https://seina-cogs.readthedocs.io/en/latest/index.html).<br/><br/>**Example:**<br/>`[p]role dump @admin <t:{member(timestamp)}> - {member(mention)}`

## role remove
 - Usage: `[p]role remove <member> <role> `

Remove a role from a member.

## role rin
 - Usage: `[p]role rin <target_role> <remove_role> `

Remove a role from all members of a another role.

## role colors
 - Usage: `[p]role colors `

Sends the server's roles, ordered by color.

# multirole
 - Usage: `[p]multirole <member> <roles> `

Add multiple roles to a member.

## multirole remove
 - Usage: `[p]multirole remove <member> <roles> `

Remove multiple roles from a member.

