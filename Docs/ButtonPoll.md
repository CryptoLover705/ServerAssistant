# ButtonPoll Help

Create polls with buttons, and get a pie chart afterwards!

# poll (Slash Command)
 - Usage: `/poll <question> <duration> <choice1> <choice2> [channel] [description] [choice3] [choice4] [choice5] `
 - `question:` (Required) Question to ask.
 - `duration:` (Required) Duration of the poll. Examples: 1 day, 1 minute, 4 hours
 - `choice1:` (Required) First choice.
 - `choice2:` (Required) Second choice.
 - `channel:` (Optional) Channel to start the poll in.
 - `description:` (Optional) An optional description.
 - `choice3:` (Optional) Optional third choice.
 - `choice4:` (Optional) Optional fourth choice.
 - `choice5:` (Optional) Optional fifth choice.

Start a button-based poll.

# buttonpoll
 - Usage: `[p]buttonpoll [chan=None] `
 - Restricted to: `MOD`
 - Aliases: `poll and bpoll`
 - Checks: `server_only`

Start a button-based poll<br/><br/>This is an interactive setup. By default the current channel will be used,<br/>but if you want to start a poll remotely you can send the channel name<br/>along with the buttonpoll command.<br/><br/>**Examples:**<br/>- `[p]buttonpoll` - start a poll in the current channel<br/>- `[p]buttonpoll #polls` start a poll somewhere else

# getvoters
 - Usage: `[p]getvoters <message_id> `
 - Restricted to: `MOD`
 - Aliases: `voters`
 - Checks: `server_only`

Fetch the current voters for a running poll<br/><br/>**Arguments**<br/>- `message_id`: (integer) The ID of the poll message

# endpoll
 - Usage: `[p]endpoll <message_id> `
 - Restricted to: `MOD`
 - Aliases: `endp`
 - Checks: `server_only`

End a currently running poll<br/><br/>**Arguments**<br/>- `message_id`: (integer) The ID of the poll message

# listpolls
 - Usage: `[p]listpolls `
 - Restricted to: `MOD`
 - Checks: `server_only`

List all currently running polls

