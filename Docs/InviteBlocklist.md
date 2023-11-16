# InviteBlocklist Help

# inviteblock
 - Usage: `[p]inviteblock `
 - Restricted to: `MOD`
 - Aliases: `ibl and inviteblocklist`

Settings for managing invite link blocking

## inviteblock immunity
 - Usage: `[p]inviteblock immunity `
 - Aliases: `immune`

Commands for fine tuning allowed channels, users, or roles

### inviteblock immunity add
 - Usage: `[p]inviteblock immunity add <channel_user_role> `

Add a server ID to the allowlist, providing an invite link will also work<br/><br/>`[channel_user_role...]` is the channel, user or role to whitelist<br/>(You can supply more than one of any at a time)

### inviteblock immunity info
 - Usage: `[p]inviteblock immunity info `

Show what channels, users, and roles are in the invite link allowlist

### inviteblock immunity remove
 - Usage: `[p]inviteblock immunity remove <channel_user_role> `
 - Aliases: `del and rem`

Add a server ID to the allowlist, providing an invite link will also work<br/><br/>`[channel_user_role...]` is the channel, user or role to remove from the whitelist<br/>(You can supply more than one of any at a time)

## inviteblock blockall
 - Usage: `[p]inviteblock blockall <set_to> `
 - Restricted to: `MOD`

Automatically remove all invites regardless of their destination

## inviteblock blocklist
 - Usage: `[p]inviteblock blocklist `
 - Aliases: `blacklist and bl`

Commands for setting the blocklist

### inviteblock blocklist add
 - Usage: `[p]inviteblock blocklist add <invite_or_server_id> `

Add a server ID to the blocklist, providing an invite link will also work<br/><br/>`[invite_or_server_id]` The server ID or invite to the server you want to have<br/>invite links blocked from.

### inviteblock blocklist remove
 - Usage: `[p]inviteblock blocklist remove <thing_to_block> `
 - Aliases: `del and rem`

Add a server ID to the blocklist, providing an invite link will also work<br/><br/>`[invite_or_server_id]` The server ID or invite to the server you not longer want to have<br/>invite links blocked from.

### inviteblock blocklist info
 - Usage: `[p]inviteblock blocklist info `

Show what server ID's are in the invite link blocklist

## inviteblock allowlist
 - Usage: `[p]inviteblock allowlist `
 - Aliases: `whitelist, wl, and al`

Commands for setting the blocklist

### inviteblock allowlist add
 - Usage: `[p]inviteblock allowlist add <invite_or_server_id> `

Add a server ID to the allowlist, providing an invite link will also work<br/><br/>`[invite_or_server_id]` The server ID or invite to the server you want to have<br/>invites allowed from.

### inviteblock allowlist info
 - Usage: `[p]inviteblock allowlist info `

Show what server ID's are in the invite link allowlist

### inviteblock allowlist remove
 - Usage: `[p]inviteblock allowlist remove <invite_or_server_id> `
 - Aliases: `del and rem`

Add a server ID to the allowlist, providing an invite link will also work<br/><br/>`[invite_or_server_id]` The server ID or invite to the server you not longer want to have<br/>invites allowed from.

