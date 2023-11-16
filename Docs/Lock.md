# Lock Help

Advanced channel and server locking.

# lock
 - Usage: `[p]lock [channel=None] [roles_or_members=None] `
 - Restricted to: `ADMIN`

Lock a channel.<br/><br/>Provide a role or member if you would like to lock it for them.<br/>You can only lock a maximum of 10 things at once.<br/><br/>**Examples:**<br/>`[p]lock #general`<br/>`[p]lock 737958453905063977 @members`

## lock server
 - Usage: `[p]lock server <roles> `

Lock the server.<br/><br/>Provide a role if you would like to lock it for that role.<br/><br/>**Example:**<br/>`[p]lock server @members`


Set the given permissions for a role or member to True.

# viewlock
 - Usage: `[p]viewlock [channel=None] [roles_or_members=None] `
 - Restricted to: `ADMIN`

Prevent users from viewing a channel.<br/><br/>Provide a role or member if you would like to lock it for them.<br/>You can only lock a maximum of 10 things at once.<br/><br/>**Example:**<br/>`[p]viewlock #secret-channel`<br/>`[p]viewlock 7382395026348520 @nubs`

# unlock
 - Usage: `[p]unlock [channel=None] [state=None] [roles_or_members=None] `
 - Restricted to: `ADMIN`

Unlock a channel.<br/><br/>Provide a role or member if you would like to unlock it for them.<br/>If you would like to override-unlock for something, you can do so by pass `true` as the state argument.<br/>You can only unlock a maximum of 10 things at once.<br/><br/>**Examples:**<br/>`[p]unlock #general`<br/>`[p]unlock 739562845027353 true`

## unlock server
 - Usage: `[p]unlock server <roles> `

Unlock the server.<br/><br/>Provide a role if you would like to unlock it for that role.<br/><br/>**Examples:**<br/>`[p]unlock server @members`

# unviewlock
 - Usage: `[p]unviewlock [channel=None] [state=None] [roles_or_members=None] `
 - Restricted to: `ADMIN`

Allow users to view a channel.<br/><br/>Provide a role or member if you would like to unlock it for them.<br/>If you would like to override-unlock for something, you can do so by pass `true` as the state argument.<br/>You can only unlock a maximum of 10 things at once.<br/><br/>**Example:**<br/>`[p]unviewlock #hidden-channel true`<br/>`[p]unviewlock 746284923572835 @boosters`

