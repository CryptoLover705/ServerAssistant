# RoleTools Help

Role related tools for moderation

# roletools
 - Usage: `[p]roletools `
 - Checks: `server_only`

Commands for creating custom role settings

## roletools required
 - Usage: `[p]roletools required `
 - Aliases: `requires, require, and req`

Set role requirements

### roletools required any
 - Usage: `[p]roletools required any <role> <require_any> `
 - Restricted to: `ADMIN`

Set the required roles to require any of the roles instead of all of them<br/><br/>`<role>` This is the role a user may acquire you want to set requirements for.<br/>`<require_any>` Either `True` or `False`. If `True` any of the required roles will allow<br/>the user to acquire the `<role>`.<br/><br/>Note: This will only work for roles assigned by this cog.

### roletools required remove
 - Usage: `[p]roletools required remove <role> <required> `
 - Restricted to: `ADMIN`

Remove role requirements<br/><br/>`<role>` This is the role a user may acquire you want to set requirements for.<br/>`<requires>` The role(s) you wish to have added when a user gains the `<role>`<br/><br/>Note: This will only work for roles assigned by this cog.

### roletools required add
 - Usage: `[p]roletools required add <role> <required> `
 - Restricted to: `ADMIN`

Add role requirements<br/><br/>`<role>` This is the role a user may acquire you want to set requirements for.<br/>`<requires>` The role(s) the user requires before being allowed to gain this role.<br/><br/>Note: This will only work for roles assigned by this cog.

## roletools viewroles
 - Usage: `[p]roletools viewroles [role] `
 - Aliases: `viewrole`

View current roletools setup for each role in the server<br/><br/>`[role]` The role you want to see settings for.

## roletools globalatomic
 - Usage: `[p]roletools globalatomic [true_or_false=None] `
 - Restricted to: `BOT_OWNER`

Set the atomicity of role assignment.<br/>What this means is that when this is `True` roles will be<br/>applied inidvidually and not cause any errors. When this<br/>is set to `False` roles will be grouped together into one call.<br/><br/>This can cause race conditions if you have other methods of applying<br/>roles setup when set to `False`.<br/><br/>`[true_or_false]` optional boolean of what to set the setting to.<br/>If not provided the current setting will be shown instead.

## roletools selfadd
 - Usage: `[p]roletools selfadd [true_or_false=None] <role> `
 - Restricted to: `ADMIN`

Set whether or not a user can apply the role to themselves.<br/><br/>`[true_or_false]` optional boolean of what to set the setting to.<br/>If not provided the current setting will be shown instead.<br/>`<role>` The role you want to set.

## roletools cost
 - Usage: `[p]roletools cost [cost=None] <role> `
 - Restricted to: `ADMIN`

Set the cost to acquire a role.<br/><br/>`[cost]` The price you want to set the role at in bot credits.<br/>Setting this to 0 or lower will remove the cost.<br/>If not provided the current setting will be shown instead.<br/>`<role>` The role you want to set.

## roletools selfrole
 - Usage: `[p]roletools selfrole `

Add or remove a defined selfrole

### roletools selfrole remove
 - Usage: `[p]roletools selfrole remove <role> `

Remove a role from yourself<br/><br/>`<role>` The role you want to remove.

### roletools selfrole add
 - Usage: `[p]roletools selfrole add <role> `

Give yourself a role<br/><br/>`<role>` The role you want to give yourself

## roletools giverole
 - Usage: `[p]roletools giverole <role> <who> `
 - Restricted to: `ADMIN`

Gives a role to designated members.<br/><br/>`<role>` The role you want to give.<br/>`[who...]` Who you want to give the role to. This can include any of the following:```diff<br/>+ Member<br/>    A specified member of the server.<br/>+ Role<br/>    People who already have a specified role.<br/>+ TextChannel<br/>    People who have access to see the channel provided.<br/>Or one of the following:<br/>+ everyone - everyone in the server.<br/>+ here     - everyone who appears online in the server.<br/>+ bots     - all the bots in the server.<br/>+ humans   - all the humans in the server.<br/>```<br/>**Note:** This runs through exclusive and inclusive role checks<br/>which may cause unintended roles to be removed/applied.<br/><br/>**This command is on a cooldown of 10 seconds per member who receives<br/>a role up to a maximum of 1 hour.**

## roletools selfrem
 - Usage: `[p]roletools selfrem [true_or_false=None] <role> `
 - Restricted to: `ADMIN`

Set whether or not a user can remove the role from themselves.<br/><br/>`[true_or_false]` optional boolean of what to set the setting to.<br/>If not provided the current setting will be shown instead.<br/>`<role>` The role you want to set.

## roletools forceroleremove
 - Usage: `[p]roletools forceroleremove <users> <role> `
 - Restricted to: `ADMIN`

Force remove sticky role on one or more users.<br/><br/>`<users>` The users you want to have a forced stickyrole applied to.<br/>`<roles>` The role you want to set.<br/><br/>Note: This is generally only useful for users who have left the server.

## roletools reaction
 - Usage: `[p]roletools reaction `
 - Aliases: `react and reactions`

Reaction role settings

### roletools reaction remove
 - Usage: `[p]roletools reaction remove <message> <role_or_emoji> `
 - Restricted to: `ADMIN`
 - Aliases: `rem`

Remove a reaction role<br/><br/>`<message>` can be the channel_id-message_id pair<br/>from copying message ID while holding SHIFT or a message link<br/>`<emoji>` The emoji you want people to react with to get the role.<br/>`<role>` The role you want people to receive for reacting.<br/><br/>Note: This will not remove the emoji reactions on the message.

### roletools reaction bulk
 - Usage: `[p]roletools reaction bulk <message> <role_emoji> `
 - Restricted to: `ADMIN`
 - Aliases: `bulkcreate and bulkmake`

Create multiple roles reactions for a single message<br/><br/>`<message>` can be the channel_id-message_id pair<br/>from copying message ID while holding SHIFT or a message link<br/>`[role_emoji...]` Must be a role-emoji pair separated by either `;`, `,`, `|`, or `-`.<br/><br/>Note: Any spaces will be considered a new set of role-emoji pairs, if you<br/>want to specify a role with a space in it without pinging it enclose<br/>the full role-emoji pair in quotes.<br/><br/>e.g. `[p]roletools bulkreact 461417772115558410-821105109097644052 @member-:smile:`<br/>`[p]roletools bulkreact 461417772115558410-821105109097644052 "Super Member-:frown:"`

### roletools reaction clearreact
 - Usage: `[p]roletools reaction clearreact <message> <emojis> `
 - Restricted to: `ADMIN`
 - Aliases: `clearreacts`

Clear the reactions for reaction roles. This will remove<br/>all reactions and then re-apply the bots reaction for you.<br/><br/>`<message>` The message you want to clear reactions on.<br/>`[emojis...]` Optional emojis you want to specifically remove.<br/>If no emojis are provided this will clear all the reaction role<br/>emojis the bot has for the message provided.<br/><br/>Note: This will only clear reactions which have a corresponding<br/>reaction role on it.

### roletools reaction create
 - Usage: `[p]roletools reaction create <message> <emoji> <role> `
 - Restricted to: `ADMIN`
 - Aliases: `make and setup`

Create a reaction role<br/><br/>`<message>` can be the channel_id-message_id pair<br/>from copying message ID while holding SHIFT or a message link<br/>`<emoji>` The emoji you want people to react with to get the role.<br/>`<role>` The role you want people to receive for reacting.

### roletools reaction reactroles
 - Usage: `[p]roletools reaction reactroles `
 - Restricted to: `ADMIN`
 - Aliases: `reactionroles and reactrole`

View current bound roles in the server

### roletools reaction cleanup
 - Usage: `[p]roletools reaction cleanup `
 - Restricted to: `ADMIN`

Cleanup old/missing reaction roles and settings.<br/><br/>Note: This will also clear out reaction roles if the bot is just<br/>missing permissions to see the reactions.

## roletools forcerole
 - Usage: `[p]roletools forcerole <users> <role> `
 - Restricted to: `ADMIN`

Force a sticky role on one or more users.<br/><br/>`<users>` The users you want to have a forced stickyrole applied to.<br/>`<roles>` The role you want to set.<br/><br/>Note: The only way to remove this would be to manually remove the role from<br/>the user.

## roletools exclude
 - Usage: `[p]roletools exclude `
 - Aliases: `exclusive`

Set role exclusions

### roletools exclude mutual
 - Usage: `[p]roletools exclude mutual <roles> `
 - Restricted to: `ADMIN`

Allow setting roles mutually exclusive to eachother<br/><br/>This is equivalent to individually setting each roles exclusive roles to another<br/>set of roles.<br/><br/>`[role...]` The roles you want to set as mutually exclusive.

### roletools exclude add
 - Usage: `[p]roletools exclude add <role> <exclude> `
 - Restricted to: `ADMIN`

Add role exclusion (This will remove if the designated role is acquired<br/>if the included roles are not selfremovable they will not be removed<br/>and the designated role will not be given)<br/><br/>`<role>` This is the role a user may acquire you want to set exclusions for.<br/>`<exclude>` The role(s) you wish to have removed when a user gains the `<role>`<br/><br/>Note: This will only work for roles assigned by this cog.

### roletools exclude remove
 - Usage: `[p]roletools exclude remove <role> <exclude> `
 - Restricted to: `ADMIN`

Remove role exclusion<br/><br/>`<role>` This is the role a user may acquire you want to set exclusions for.<br/>`<exclude>` The role(s) currently excluded you no longer wish to have excluded

## roletools removerole
 - Usage: `[p]roletools removerole <role> <who> `
 - Restricted to: `ADMIN`

Removes a role from the designated members.<br/><br/>`<role>` The role you want to give.<br/>`[who...]` Who you want to give the role to. This can include any of the following:```diff<br/>+ Member<br/>    A specified member of the server.<br/>+ Role<br/>    People who already have a specified role.<br/>+ TextChannel<br/>    People who have access to see the channel provided.<br/>Or one of the following:<br/>+ everyone - everyone in the server.<br/>+ here     - everyone who appears online in the server.<br/>+ bots     - all the bots in the server.<br/>+ humans   - all the humans in the server.<br/>```<br/>**Note:** This runs through exclusive and inclusive role checks<br/>which may cause unintended roles to be removed/applied.<br/><br/>**This command is on a cooldown of 10 seconds per member who receives<br/>a role up to a maximum of 1 hour.**

## roletools message
 - Usage: `[p]roletools message `

Commands for sending/editing messages for roletools

### roletools message send
 - Usage: `[p]roletools message send <channel> <buttons> <menus> <message> `

Send a select menu to a specified channel for role assignment<br/><br/>`<channel>` - the channel to send the button role buttons to.<br/>`[buttons]...` - The names of the buttons you want included in the<br/>`[menus]...` - The names of the select menus you want included in the<br/>message up to a maximum of 5.<br/>`<message>` - The message to be included with the select menu.<br/><br/>Note: There is a maximum of 25 slots available on one message. Each menu<br/>uses up 5 slots while each button uses up 1 slot.

### roletools message edit
 - Usage: `[p]roletools message edit <message> <buttons> <menus> `

Edit a bots message to include Role Buttons<br/><br/>`<message>` - The existing message to add role buttons to. Must be a bots message.<br/>`[buttons]...` - The names of the buttons you want to include up to a maximum of 25.<br/>`[menus]...` - The names of the select menus you want to include up to a maximum of 5.<br/><br/>Note: There is a maximum of 25 slots available on one message. Each menu<br/>uses up 5 slots while each button uses up 1 slot.

### roletools message sendselect
 - Usage: `[p]roletools message sendselect <channel> <menus> <message> `

Send a select menu to a specified channel for role assignment<br/><br/>`<channel>` - the channel to send the button role buttons to.<br/>`[menus]...` - The names of the select menus you want included in the<br/>message up to a maximum of 5.<br/>`<message>` - The message to be included with the select menu.

### roletools message editbutton
 - Usage: `[p]roletools message editbutton <message> <buttons> `

Edit a bots message to include Role Buttons<br/><br/>`<message>` - The existing message to add role buttons to. Must be a bots message.<br/>`[buttons]...` - The names of the buttons you want to include up to a maximum of 25.

### roletools message editselect
 - Usage: `[p]roletools message editselect <message> <menus> `

Edit a bots message to include Role Buttons<br/><br/>`<message>` - The existing message to add role buttons to. Must be a bots message.<br/>`[menus]...` - The names of the select menus you want to include up to a maximum of 5.

### roletools message sendbutton
 - Usage: `[p]roletools message sendbutton <channel> <buttons> <message> `

Send buttons to a specified channel with optional message.<br/><br/>`<channel>` - the channel to send the button role buttons to.<br/>`[buttons]...` - The names of the buttons you want included in the<br/>message up to a maximum of 25.<br/>`<message>` - The message to be included with the buttons.

## roletools select
 - Usage: `[p]roletools select `
 - Restricted to: `ADMIN`
 - Aliases: `selects`

Setup role select menus

### roletools select viewoptions
 - Usage: `[p]roletools select viewoptions `
 - Restricted to: `ADMIN`
 - Aliases: `listoptions, viewoption, and listoption`

View current select menus setup for role assign in this server.

### roletools select delete
 - Usage: `[p]roletools select delete <name> `
 - Aliases: `del and remove`

Delete a saved select menu.<br/><br/>`<name>` - the name of the select menu you want to delete.

### roletools select deleteoption
 - Usage: `[p]roletools select deleteoption <name> `
 - Aliases: `deloption, removeoption, and remoption`

Delete a saved option.<br/><br/>`<name>` - the name of the select option you want to delete.

### roletools select create
 - Usage: `[p]roletools select create <name> <options> <extras> `

Create a select menu<br/><br/>- `<name>` - The name for you to use when you send a message with this menu.<br/>- `[options]...` - The select menu options you designated previously.<br/>- `[extras]`<br/> - `min:` - The minimum number of items from this menu to be selected.<br/> - `max:` - The maximum number of items from this menu that can be selected.<br/> (If not provided this will default to the number of options provided.)<br/> - `placeholder:` - This is the default text on the menu when no option has been<br/>chosen yet.<br/>Example:<br/>    `[p]roletools select create myrolemenu role1 role2 role3 placeholder: Pick your role!`

### roletools select createoption
 - Usage: `[p]roletools select createoption <name> <role> <extras> `
 - Aliases: `addoption`

Create a select menu option<br/><br/>- `<name>` - The name of the select option for use later in setup.<br/>- `<role>` - The role this select option will assign or remove.<br/>- `[extras]`<br/> - `label:` - The optional label for the option, max of 25 characters.<br/> - `description:` - The description for the option, max of 50 characters.<br/> - `emoji:` - The optional emoji used in the select option.<br/><br/>Note: If no label and no emoji are provided the roles name will be used instead.<br/>This name will not update if the role name is changed.<br/><br/>Example:<br/>    `[p]roletools select createoption role1 @role label: Super Fun Role emoji: 😀`

### roletools select cleanup
 - Usage: `[p]roletools select cleanup `
 - Restricted to: `ADMIN`

Check each select menu that has registered a message still exists and remove buttons with<br/>missing messages.<br/><br/># Note: This will also potentially cause problems if the button exists in a thread<br/>it will not be found if the thread is archived and subsequently removed.

### roletools select view
 - Usage: `[p]roletools select view `
 - Restricted to: `ADMIN`
 - Aliases: `list`

View current select menus setup for role assign in this server.

## roletools buttons
 - Usage: `[p]roletools buttons `
 - Restricted to: `ADMIN`
 - Aliases: `button`

Setup role buttons

### roletools buttons delete
 - Usage: `[p]roletools buttons delete <name> `
 - Aliases: `del and remove`

Delete a saved button.<br/><br/>`<name>` - the name of the button you want to delete.

### roletools buttons cleanup
 - Usage: `[p]roletools buttons cleanup `
 - Restricted to: `ADMIN`

Check each button that has registered a message still exists and remove buttons with<br/>missing messages.<br/><br/># Note: This will also potentially cause problems if the button exists in a thread<br/>it will not be found if the thread is archived and subsequently removed.

### roletools buttons view
 - Usage: `[p]roletools buttons view `
 - Restricted to: `ADMIN`

View current buttons setup for role assign in this server.

### roletools buttons create
 - Usage: `[p]roletools buttons create <name> <role> <extras> `

Create a role button<br/><br/>- `<name>` - The name of the button for use later in setup.<br/>- `<role>` - The role this button will assign or remove.<br/>- `[extras]`<br/> - `label:` - The optional label for the button.<br/> - `emoji:` - The optional emoji used in the button.<br/> - `style:` - The background button style. Must be one of the following:<br/>   - `primary`<br/>   - `secondary`<br/>   - `success`<br/>   - `danger`<br/>   - `blurple`<br/>   - `grey`<br/>   - `green`<br/>   - `red`<br/><br/>Note: If no label and no emoji are provided the roles name will be used instead.<br/>This name will not update if the role name is changed.<br/><br/>Example:<br/>    `[p]roletools button create role1 @role label: Super fun role style: blurple emoji: 😀`

## roletools atomic
 - Usage: `[p]roletools atomic [true_or_false=None] `
 - Restricted to: `ADMIN`

Set the atomicity of role assignment.<br/>What this means is that when this is `True` roles will be<br/>applied inidvidually and not cause any errors. When this<br/>is set to `False` roles will be grouped together into one call.<br/><br/>This can cause race conditions if you have other methods of applying<br/>roles setup when set to `False`.<br/><br/>`[true_or_false]` optional boolean of what to set the setting to.<br/>To reset back to the default global rules use `clear`.<br/>If not provided the current setting will be shown instead.

## roletools autorole
 - Usage: `[p]roletools autorole [true_or_false=None] <role> `
 - Restricted to: `ADMIN`
 - Aliases: `auto`

Set a role to be automatically applied when a user joins the server.<br/><br/>`[true_or_false]` optional boolean of what to set the setting to.<br/>If not provided the current setting will be shown instead.<br/>`<role>` The role you want to set.

## roletools include
 - Usage: `[p]roletools include `
 - Aliases: `inclusive`

Set role inclusion

### roletools include mutual
 - Usage: `[p]roletools include mutual <roles> `
 - Restricted to: `ADMIN`

Allow setting roles mutually inclusive to eachother<br/><br/>This is equivalent to individually setting each roles inclusive roles to another<br/>set of roles.<br/><br/>`[role...]` The roles you want to set as mutually inclusive.

### roletools include remove
 - Usage: `[p]roletools include remove <role> <include> `
 - Restricted to: `ADMIN`

Remove role inclusion<br/><br/>`<role>` This is the role a user may acquire you want to set exclusions for.<br/>`<include>` The role(s) currently inclusive you no longer wish to have included

### roletools include add
 - Usage: `[p]roletools include add <role> <include> `
 - Restricted to: `ADMIN`

Add role inclusion (This will add roles if the designated role is acquired<br/>if the designated role is removed the included roles will also be removed<br/>if the included roles are set to selfremovable)<br/><br/>`<role>` This is the role a user may acquire you want to set exclusions for.<br/>`<include>` The role(s) you wish to have added when a user gains the `<role>`<br/><br/>Note: This will only work for roles assigned by this cog.

## roletools sticky
 - Usage: `[p]roletools sticky [true_or_false=None] <role> `
 - Restricted to: `ADMIN`

Set whether or not a role will be re-applied when a user leaves and rejoins the server.<br/><br/>`[true_or_false]` optional boolean of what to set the setting to.<br/>If not provided the current setting will be shown instead.<br/>`<role>` The role you want to set.

