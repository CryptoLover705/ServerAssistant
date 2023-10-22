# BetterUptime Help

Replaces the core `uptime` command to show the uptime<br/>percentage over the last 30 days.<br/><br/>The cog will need to run for a full 30 days for the full<br/>data to become available.

# uptime
 - Usage: `[p]uptime `

Get my uptime data

## uptime data (Slash Command)
 - Usage: `/uptime data [days] `
 - `days:` (Optional) Days of data to show, use 0 for all-time data. Default: 30

Get my uptime data in an embed

## uptime graph (Slash Command)
 - Usage: `/uptime graph [days] `
 - `days:` (Optional) Days of data to show, use 0 for all-time data. Default: 30

Get my uptime graph in an embed

## uptime downtime (Slash Command)
 - Usage: `/uptime downtime [days] `
 - `days:` (Optional) Days of data to show, use 0 for all-time data. Default: 30

Get my downtime data in an embed

# uptime
 - Usage: `[p]uptime [num_days=30] `

Get [botname]'s uptime percent over the last 30 days, and when I was last restarted.<br/><br/>The default value for `num_days` is `30`. You can put `0` days for all-time data.<br/>Otherwise, it needs to be `5` or more.<br/><br/>Note: embeds must be enabled for this rich data to show<br/><br/>**Examples:**<br/>- `[p]uptime`<br/>- `[p]uptime 0` (for all-time data)<br/>- `[p]uptime 7`

# downtime
 - Usage: `[p]downtime [num_days=30] `

Check [botname] downtime over the last 30 days.<br/><br/>The default value for `num_days` is `30`. You can put `0` days for all-time data.<br/>Otherwise, it needs to be `5` or more.<br/><br/>**Examples:**<br/>- `[p]uptime`<br/>- `[p]uptime 0` (for all-time data)<br/>- `[p]uptime 7`

# uptimegraph
 - Usage: `[p]uptimegraph [num_days=30] `

Check [botname] uptime with a graph over the last 30 days.<br/><br/>The default value for `num_days` is `30`. You can put `0` days for all-time data.<br/>Otherwise, it needs to be `5` or more.<br/><br/>**Examples:**<br/>- `[p]uptime` - for the default of 30 days<br/>- `[p]uptime 0` - for all-time data<br/>-]uptime 7` - 7 days

# uptimeexport
 - Usage: `[p]uptimeexport `
 - Restricted to: `BOT_OWNER`

Export my uptime data to CSV<br/><br/>The numbers represent uptime, so 86400 means 100% for that day (86400 seconds in 1 day).<br/><br/>Everything is in UTC.<br/><br/>Connected is the bot being connected to Discord.<br/><br/>Cog loaded is the cog being loaded but not necessarily connected to Discord.<br/><br/>Therefore, connected should always be equal to or lower than cog loaded.

# resetbu
 - Usage: `[p]resetbu [confirm=False] `
 - Restricted to: `BOT_OWNER`

Reset the cog's data.

