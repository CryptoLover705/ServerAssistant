# EconomyTrickle Help

Trickle credits into your Economy<br/><br/>More detailed docs: <https://cogs.yamikaitou.dev/economytrickle.html>

# economytrickle
 - Usage: `[p]economytrickle `
 - Restricted to: `ADMIN`
 - Aliases: `trickleset`
 - Checks: `is_owner_if_bank_global`

Configure various settings

## economytrickle settings
 - Usage: `[p]economytrickle settings `
 - Restricted to: `ADMIN`
 - Aliases: `info and showsettings`
 - Checks: `is_owner_if_bank_global`

Show the current settings

## economytrickle voice
 - Usage: `[p]economytrickle voice <number> `
 - Restricted to: `ADMIN`
 - Checks: `is_owner_if_bank_global`

Set the number of credits to grant every minute<br/><br/>Set the number to 0 to disable<br/>Max value is 1000

## economytrickle messages
 - Usage: `[p]economytrickle messages <number> `
 - Restricted to: `ADMIN`
 - Checks: `is_owner_if_bank_global`

Set the number of messages required to gain credits<br/><br/>Set the number to 0 to disable<br/>Max value is 100

## economytrickle blocklist
 - Usage: `[p]economytrickle blocklist [channel=None] `
 - Restricted to: `ADMIN`
 - Aliases: `blacklist`
 - Checks: `server_only`

Add/Remove the current channel (or a specific channel) to the blocklist<br/><br/>Not passing a channel will add/remove the channel you ran the command in to the blocklist

## economytrickle credits
 - Usage: `[p]economytrickle credits <number> `
 - Restricted to: `ADMIN`
 - Checks: `is_owner_if_bank_global`

Set the number of credits to grant<br/><br/>Set the number to 0 to disable<br/>Max value is 1000

## economytrickle showblocks
 - Usage: `[p]economytrickle showblocks `
 - Restricted to: `ADMIN`
 - Aliases: `showblock`
 - Checks: `server_only`

Provide a list of channels that are on the blocklist for this server

