# Timeout Help

Manage Timeouts.

# timeout
 - Usage: `[p]timeout <member_or_role> [time=None] [reason] `
 - Restricted to: `ADMIN`
 - Aliases: `tt`
 - Cooldown: `1 per 1.0 second`
 - Checks: `server_only`

Timeout users.<br/><br/>`<member_or_role>` is the username/rolename, ID or mention. If provided a role,<br/>everyone with that role will be timedout.<br/>`[time]` is the time to mute for. Time is any valid time length such as `45 minutes`<br/>or `3 days`. If nothing is provided the timeout will be 60 seconds default.<br/>`[reason]` is the reason for the timeout. Defaults to `None` if nothing is provided.<br/><br/>Examples:<br/>`[p]timeout @member 5m talks too much`<br/>`[p]timeout @member 10m`

# untimeout
 - Usage: `[p]untimeout <member_or_role> [reason] `
 - Restricted to: `ADMIN`
 - Aliases: `utt`
 - Cooldown: `1 per 1.0 second`
 - Checks: `server_only`

Untimeout users.<br/><br/>`<member_or_role>` is the username/rolename, ID or mention. If<br/>provided a role, everyone with that role will be untimed.<br/>`[reason]` is the reason for the untimeout. Defaults to `None`<br/>if nothing is provided.

# timeoutset
 - Usage: `[p]timeoutset `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Manage timeout settings.

## timeoutset dm
 - Usage: `[p]timeoutset dm `

Change whether to DM the user when they are timed out.

## timeoutset showmoderator
 - Usage: `[p]timeoutset showmoderator `
 - Aliases: `showmod`

Change whether to show moderator on DM's or not.

## timeoutset role
 - Usage: `[p]timeoutset role `

Change whether to timeout role or not.

