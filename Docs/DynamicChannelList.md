# DynamicChannelList Help

Create dynamically updating channel lists.

# dynamicchannellist
 - Usage: `[p]dynamicchannellist `
 - Restricted to: `MOD`
 - Aliases: `dcl`

Group command for DynamicChannelList.

## dynamicchannellist channelblacklist
 - Usage: `[p]dynamicchannellist channelblacklist [chan=None] `
 - Aliases: `channelignore`

Toggle if a channel is blacklisted from appearing on channel lists.<br/><br/>If no channel is provided, the currently blacklisted categories will be listed.

## dynamicchannellist createauto
 - Usage: `[p]dynamicchannellist createauto [channel=None] [ignoreBlacklist=False] [role=None] `

Create an automatically updating channel list.

## dynamicchannellist removeauto
 - Usage: `[p]dynamicchannellist removeauto <message> `

Remove an automatically updating channel list.<br/><br/>This will not delete the message, only stop it from updating.<br/>`message` should be a link to the message.

## dynamicchannellist header
 - Usage: `[p]dynamicchannellist header [text] `

Set the header for all embed messages.

## dynamicchannellist generate
 - Usage: `[p]dynamicchannellist generate [channel=None] [ignoreBlacklist=False] [role=None] `

Generate a one-time channel list.

## dynamicchannellist reloadauto
 - Usage: `[p]dynamicchannellist reloadauto `

Reload all automatically updating channel lists.

## dynamicchannellist color
 - Usage: `[p]dynamicchannellist color <color> `

Set the color to use for embeds.

## dynamicchannellist categoryblacklist
 - Usage: `[p]dynamicchannellist categoryblacklist [cat=None] `
 - Aliases: `categoryignore`

Toggle if a category is blacklisted from appearing on channel lists.<br/><br/>If no category is provided, the currently blacklisted categories will be listed.

