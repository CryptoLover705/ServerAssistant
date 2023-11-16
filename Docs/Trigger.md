# Trigger Help

# trigger
 - Usage: `[p]trigger `
 - Checks: `server_only`

Group command for triggers.

## trigger toggle
 - Usage: `[p]trigger toggle <trigger_name> `

Toggle a trigger.

## trigger list
 - Usage: `[p]trigger list `

List all triggers.

## trigger edit
 - Usage: `[p]trigger edit `

Edit a trigger.

### trigger edit cooldown
 - Usage: `[p]trigger edit cooldown <trigger_name> <seconds> `

Set the cooldown for a trigger.

### trigger edit embeds
 - Usage: `[p]trigger edit embeds <trigger_name> <toggle> `
 - Aliases: `embedsearch`

Toggle searching within embeds for the trigger.

### trigger edit trigger
 - Usage: `[p]trigger edit trigger <trigger_name> <triggered_by> `

Edit the trigger.

### trigger edit case
 - Usage: `[p]trigger edit case <trigger_name> <case_sensitive> `
 - Aliases: `casesensitive`

Toggle case sensitivity for a trigger.

### trigger edit boundary
 - Usage: `[p]trigger edit boundary <trigger_name> <toggle> `
 - Aliases: `wordboundary`

Toggle word boundaries for a trigger.

### trigger edit responses
 - Usage: `[p]trigger edit responses <trigger_name> `

Edit the responses for a trigger.

## trigger delete
 - Usage: `[p]trigger delete <trigger_name> `

Delete a trigger.

## trigger create
 - Usage: `[p]trigger create <trigger_name> <triggered_by> `

Create a trigger.<br/><br/>Variables can be used within the responses.<br/>user: The user that triggered the trigger.<br/>channel: The channel the trigger was triggered in.<br/>message: The message that triggered the trigger.<br/>server: The server the trigger was triggered in.<br/>uses: The number of times the trigger has been used.<br/>trigger: The name of the trigger that was triggered.<br/><br/>Example: `{user} has triggered the trigger {trigger} in {channel} {uses} times.`

