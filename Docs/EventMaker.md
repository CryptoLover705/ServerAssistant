# EventMaker Help

A tool for creating events inside of Discord. Anyone can<br/>create an event by default. If a specific role has been<br/>specified, users must have that role or any role above it in<br/>the hierarchy or be the server owner to create events.

# event
 - Usage: `[p]event `
 - Checks: `server_only`

Base command for events

## event join
 - Usage: `[p]event join <event_id> `

Join an event

## event leave
 - Usage: `[p]event leave <event_id> `

Leave the specified event

## event cancel
 - Usage: `[p]event cancel <event_id> `

Cancels the specified event

## event who
 - Usage: `[p]event who <event_id> `

List all participants for the event

## event list
 - Usage: `[p]event list [started=False] `

List events for this server that have not started yet<br/><br/>If `started` is True, include events that have already started

## event create
 - Usage: `[p]event create `
 - Checks: `allowed_to_create`

Wizard-style event creation tool.<br/><br/>The event will only be created if all information is provided properly.<br/>If a minimum required role has been set, users must have that role or<br/>higher, be in the mod/admin role, or be the server owner in order to use this command

# eventset
 - Usage: `[p]eventset `
 - Checks: `server_only`

Event maker settings

## eventset toggledms
 - Usage: `[p]eventset toggledms [user=None] `
 - Checks: `server_only`

Toggles event start announcement DMs for the specified user<br/><br/>By default, users will not receive event start announcements via DM<br/><br/>If `user` is not specified, toggle for the author.<br/><br/>Only admins and the server owner may toggle DMs for users other than themselves

## eventset role
 - Usage: `[p]eventset role [role] `
 - Restricted to: `ADMIN`

Set the minimum role required to create events.<br/><br/>Default is for everyone to be able to create events

## eventset resetevents
 - Usage: `[p]eventset resetevents [confirm=None] `
 - Restricted to: `GUILD_OWNER`

Resets the events list for this server

## eventset channel
 - Usage: `[p]eventset channel <channel> `
 - Restricted to: `ADMIN`

Sets the channel where event start announcements will be sent<br/><br/>If this is not set, the channel will default to the channel used<br/>for new member messages (Server Settings > Overview > New Member<br/>Messages Channel on desktop). If that is set to `No new member messages`,<br/>the event start announcement will not be sent to a channel in the server<br/>and will only be sent directly to the participants via DM

