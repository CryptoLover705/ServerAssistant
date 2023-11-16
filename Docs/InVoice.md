# InVoice Help

# invoice
 - Usage: `[p]invoice `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Configure or view settings for automated voice-based permissions.

## invoice unset
 - Usage: `[p]invoice unset <scope> <settings> `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Unset various settings, causing them to fall back to the outer scope.<br/><br/>`scope` is the voice channel or category that you wish to change;<br/>leave it empty to manage server-wide settings.<br/>Unset server-wide settings tell the bot to take no action.<br/><br/>See `[p]help invoice set` for info on the various settings available.

## invoice set
 - Usage: `[p]invoice set <scope> <settings> `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Configure various settings.<br/><br/>`scope` is the voice channel or category that you wish to change;<br/>leave it empty to manage server-wide settings.<br/><br/>__Configurable Settings__<br/>**role**:       The role granted to users inside the scoped VCs.<br/>**channel**:    The text channel granted access to while inside the scoped VCs.<br/>**dynamic**:    true/false, create a new role and text channel when new VCs are created here.<br/>    The new role will inherit the permissions of higher-scoped roles.<br/>**dynamic_name**:       The name to apply to dynamically created roles and text channels.<br/>    `{vc}` will be replaced with the name of the new channel.<br/>**mute**:       true/false, mute the user in the text channel if they are server muted.<br/>**suppress**:   true/false, mute the user in the text channel if they don't have permission to speak.<br/>**deaf**:       true/false, remove the user from the text channel if they are server deafened.<br/>**self_deaf**:  true/false, remove the user from the text channel if they are self deafened.

### invoice set show
 - Usage: `[p]invoice set show [scope] `
 - Aliases: `showsettings`
 - Checks: `server_only`

Show the current settings for the specified scope.<br/><br/>See `[p]help invoice set` for explanations of the various settings.

