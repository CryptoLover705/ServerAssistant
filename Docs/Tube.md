# Tube Help

A YouTube subscription cog<br/><br/>Thanks to mikeshardmind(Sinbad) for the RSS cog as reference

# tube
 - Usage: `[p]tube `

Post when new videos are added to a YouTube channel

## tube subscribe
 - Usage: `[p]tube subscribe <channelYouTube> [channelDiscord=None] [publish=False] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Subscribe a Discord channel to a YouTube channel<br/><br/>If no discord channel is specified, the current channel will be subscribed<br/><br/>Adding channels by name is not supported at this time. The YouTube channel ID for this can be found in channel links on videos.<br/><br/>For example, to subscribe to the channel Ctrl Shift Face, you would search YouTube for the name, then on one of the videos in the results copy the channel link. It should look like this:<br/>https://www.youtube.com/channel/UCKpH0CKltc73e4wh0_pgL3g<br/><br/>Now take the last part of the link as the channel ID:<br/>`[p]tube subscribe UCKpH0CKltc73e4wh0_pgL3g`<br/><br/>Setting the `publish` flag will cause new videos to be published to the specified channel. Using this on non-announcement channels may result in errors.

## tube demo
 - Usage: `[p]tube demo `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Post the latest video from all subscriptions

## tube rolemention
 - Usage: `[p]tube rolemention <channelYouTube> <rolemention> `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Adds a role mention in front of the message

## tube list
 - Usage: `[p]tube list `
 - Checks: `server_only`

List current subscriptions

## tube update
 - Usage: `[p]tube update `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Update feeds and post new videos

## tube customize
 - Usage: `[p]tube customize <channelYouTube> [customMessage=False] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Add a custom message to videos from a YouTube channel<br/><br/>You can use any keys available in the RSS object in your custom message<br/>by surrounding the key in perecent signs, e.g.:<br/>[p]tube customize UCKpH0CKltc73e4wh0_pgL3g "It's ya boi %author% wish a fresh vid: %title%\nWatch, like, subscribe, give monies, etc.<br/><br/>You can also remove customization by not specifying any message.

## tube unsubscribe
 - Usage: `[p]tube unsubscribe <channelYouTube> [channelDiscord=None] `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Unsubscribe a Discord channel from a YouTube channel<br/><br/>If no Discord channel is specified and the asAnnouncement flag not set to True, the subscription will be removed from all channels

