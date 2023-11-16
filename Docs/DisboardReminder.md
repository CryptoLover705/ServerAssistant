# DisboardReminder Help

Set a reminder to bump on Disboard.

# bumpreminder
 - Usage: `[p]bumpreminder `
 - Restricted to: `ADMIN`
 - Aliases: `bprm`
 - Checks: `server_only`

Set a reminder to bump on Disboard.<br/><br/>This sends a reminder to bump in a specified channel 2 hours after someone successfully bumps, thus making it more accurate than a repeating schedule.

## bumpreminder clean
 - Usage: `[p]bumpreminder clean [true_or_false=None] `

Toggle whether [botname] should keep the bump channel "clean."<br/><br/>[botname] will remove all failed invoke messages by Disboard.

## bumpreminder message
 - Usage: `[p]bumpreminder message [message] `

Change the message used for reminders. Providing no message will reset to the default message.

## bumpreminder pingrole
 - Usage: `[p]bumpreminder pingrole [role=None] `

Set a role to ping for bump reminders.<br/><br/>If no role is provided, it will clear the current role.

## bumpreminder settings
 - Usage: `[p]bumpreminder settings `

Show your Bump Reminder settings.

## bumpreminder thankyou
 - Usage: `[p]bumpreminder thankyou [message] `
 - Aliases: `ty`

Change the message used for 'Thank You' messages. Providing no message will reset to the default message.<br/><br/>The thank you message supports TagScript blocks which can customize the message and even add an embed!<br/>[View the TagScript documentation here.](https://phen-cogs.readthedocs.io/en/latest/index.html)<br/><br/>Variables:<br/>`{member}` - [The user who bumped](https://phen-cogs.readthedocs.io/en/latest/tags/default_variables.html#author-block)<br/>`{server}` - [This server](https://phen-cogs.readthedocs.io/en/latest/tags/default_variables.html#server-block)<br/><br/>Blocks:<br/>`embed` - [Embed to be sent in the thank you message](https://phen-cogs.readthedocs.io/en/latest/tags/parsing_blocks.html#embed-block)<br/><br/>**Examples:**<br/>> `[p]bprm ty Thanks {member} for bumping! You earned 10 brownie points from phen!`<br/>> `[p]bprm ty {embed(description):{member(mention)}, thank you for bumping! Make sure to vote for **{server}** on [our voting page](https://disboard.org/server/{server(id)}).}`

## bumpreminder channel
 - Usage: `[p]bumpreminder channel [channel=None] `

Set the channel to send bump reminders to.<br/><br/>This also works as a toggle, so if no channel is provided, it will disable reminders for this server.

## bumpreminder lock
 - Usage: `[p]bumpreminder lock [true_or_false=None] `

Toggle whether the bot should automatically lock/unlock the bump channel.

