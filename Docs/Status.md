# Status Help

Automatically check for status updates.<br/><br/>When there is one, it will send the update to all channels that<br/>have registered to recieve updates from that service.<br/><br/>There's also the `status` command which anyone can use to check<br/>updates wherever they want.<br/><br/>If there's a service that you want added, contact @vexingvexed or<br/>make an issue on the GitHub repo (or even better a PR!).

# statusset
 - Usage: `[p]statusset `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Get automatic status updates in a channel, eg Discord.<br/><br/>Get started with `[p]statusset preview` to see what they look like,<br/>then `[p]statusset add` to set up automatic updates.

## statusset preview
 - Usage: `[p]statusset preview <service> <mode> <webhook> `

Preview what status updates will look like.<br/><br/>You can also see this at https://go.vexcodes.com/c/statusref<br/><br/>**<service>**<br/><br/>    The service you want to preview. There's a list of available services in the<br/>    `[p]help statusset` command.<br/><br/>**<mode>**<br/><br/>    **all**: Every time the service posts an update on an incident, I will send<br/>    a new message containing the previous updates as well as the new update. Best<br/>    used in a fast-moving channel with other users.<br/><br/>    **latest**: Every time the service posts an update on an incident, I will send<br/>    a new message containing only the latest update. Best used in a dedicated status<br/>    channel.<br/><br/>    **edit**: Naturally, edit mode can't have a preview so won't work with this command.<br/>    The message content is the same as the `all` mode.<br/>    When a new incident is created, I will sent a new message. When this<br/>    incident is updated, I will then add the update to the original message. Best<br/>    used in a dedicated status channel.<br/><br/>**<webhook>**<br/><br/>    Using a webhook means that the status updates will be sent with the avatar<br/>    as the service's logo and the name will be `[service] Status Update`, instead<br/>    of my avatar and name.<br/><br/>**Examples:**<br/>- `[p]statusset preview discord all true`<br/>- `[p]statusset preview discord latest false`

## statusset edit
 - Usage: `[p]statusset edit `

Edit services you've already set up.

### statusset edit webhook
 - Usage: `[p]statusset edit webhook <chan> <service> <webhook> `

Set whether or not to use webhooks for status updates.<br/><br/>Using a webhook means that the status updates will be sent with the avatar as the service's<br/>logo and the name will be `[service] Status Update`, instead of my avatar and name.<br/><br/>If you don't specify a channel, I will use the current channel.<br/><br/>**Examples:**<br/>- `[p]statusset edit webhook #testing discord true`<br/>- `[p]statusset edit webhook discord false` (for current channel)

### statusset edit mode
 - Usage: `[p]statusset edit mode <chan> <service> <mode> `

Change what mode to use for status updates.<br/><br/>**All**: Every time the service posts an update on an incident, I will send a new message<br/>containing the previous updates as well as the new update. Best used in a fast-moving<br/>channel with other users.<br/><br/>**Latest**: Every time the service posts an update on an incident, I will send a new<br/>message containing only the latest update. Best used in a dedicated status channel.<br/><br/>**Edit**: When a new incident is created, I will sent a new message. When this incident is<br/>updated, I will then add the update to the original message. Best used in a dedicated<br/>status channel.<br/><br/>If you don't specify a channel, I will use the current channel.<br/><br/>**Examples:**<br/>- `[p]statusset edit mode #testing discord latest`<br/>- `[p]statusset edit mode discord edit` (for current channel)

### statusset edit restrict
 - Usage: `[p]statusset edit restrict <chan> <service> <restrict> `

Restrict access to the service in the `status` command.<br/><br/>Enabling this will reduce spam. Instead of sending the whole update<br/>(if there's an incident) members will instead be redirected to channels<br/>that automatically receive the status updates, that they have permission to to view.<br/><br/>**Examples:**<br/>- `[p]statusset edit restrict #testing discord true`<br/>- `[p]statusset edit restrict discord false` (for current channel)

## statusset list
 - Usage: `[p]statusset list <service> `
 - Aliases: `show and settings`

List that available services and ones are used in this server.<br/><br/>Optionally add a service at the end of the command to view detailed settings for that<br/>service.<br/><br/>**Examples:**<br/>- `[p]statusset list discord`<br/>- `[p]statusset list`

## statusset remove
 - Usage: `[p]statusset remove <service> [chan=None] `
 - Aliases: `del and delete`

Stop status updates for a specific service in this server.<br/><br/>If you don't specify a channel, I will use the current channel.<br/><br/>**Examples:**<br/>- `[p]statusset remove discord #testing`<br/>- `[p]statusset remove discord` (for using current channel)

## statusset add
 - Usage: `[p]statusset add <service> <chan> `

Start getting status updates for the chosen service!<br/><br/>There is a list of services you can use in the `[p]statusset list` command.<br/><br/>This is an interactive command. It will ask what mode you want to use and if you<br/>want to use a webhook. You can use the `[p]statusset preview` command to see how<br/>different options look or take a look at<br/>https://go.vexcodes.com/c/statusref<br/><br/>If you don't specify a specific channel, I will use the current channel.

## statusset clear
 - Usage: `[p]statusset clear <chan> `
 - Aliases: `erase`

Remove all feeds from a channel.<br/><br/>If you don't specify a channel, I will use the current channel<br/><br/>**Examples:**<br/>- `[p]statusset clear #testing`<br/>- `[p]statusset clear` (for using current channel)

# status
 - Usage: `[p]status <service> `
 - Cooldown: `2 per 10.0 seconds`
 - Checks: `server_only`

Check for the status of a variety of services, eg Discord.<br/><br/>**Example:**<br/>- `[p]status discord`

