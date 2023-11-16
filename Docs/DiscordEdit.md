# DiscordEdit Help

A cog to edit Discord default objects, like guilds, roles, text channels, voice channels, threads and AutoMod!

# editvoicechannel (Hybrid Command)
 - Usage: `[p]editvoicechannel `
 - Slash Usage: `/editvoicechannel `
 - Restricted to: `ADMIN`
 - Aliases: `editvoiceroom`
 - Checks: `server_only`

Commands for edit a voice channel.

## editvoicechannel slowmodedelay (Hybrid Command)
 - Usage: `[p]editvoicechannel slowmodedelay <channel> <slowmode_delay> `
 - Slash Usage: `/editvoicechannel slowmodedelay <channel> <slowmode_delay> `
 - Aliases: `slowmode_delay`
 - Checks: `server_only`

Edit voice channel slowmode delay.<br/><br/>Specifies the slowmode rate limit for user in this channel. A value of 0s disables slowmode. The maximum value possible is 21600s.

## editvoicechannel create (Hybrid Command)
 - Usage: `[p]editvoicechannel create [category=None] <name> `
 - Slash Usage: `/editvoicechannel create [category=None] <name> `
 - Aliases: `new and +`
 - Checks: `server_only`

Create a voice channel.

## editvoicechannel clone (Hybrid Command)
 - Usage: `[p]editvoicechannel clone <channel> <name> `
 - Slash Usage: `/editvoicechannel clone <channel> <name> `
 - Checks: `server_only`

Clone a voice channel.

## editvoicechannel videoqualitymode (Hybrid Command)
 - Usage: `[p]editvoicechannel videoqualitymode <channel> <video_quality_mode> `
 - Slash Usage: `/editvoicechannel videoqualitymode <channel> <video_quality_mode> `
 - Aliases: `video_quality_mode`
 - Checks: `server_only`

Edit voice channel video quality mode.<br/><br/>auto = 1<br/>full = 2

## editvoicechannel overwrites (Hybrid Command)
 - Usage: `[p]editvoicechannel overwrites <channel> <roles_or_users> <true_or_false> <permissions> `
 - Slash Usage: `/editvoicechannel overwrites <channel> <roles_or_users> <true_or_false> <permissions> `
 - Aliases: `permissions and perms`
 - Checks: `server_only`

Edit voice channel overwrites/permissions.<br/><br/>You may not specify `True` or `False` to reset the overwrite(s).<br/>You must possess the permissions you wish to modify.<br/><br/>• `create_instant_invite`<br/>• `manage_channels`<br/>• `add_reactions`<br/>• `priority_speaker`<br/>• `stream`<br/>• `read_messages`<br/>• `send_messages`<br/>• `send_tts_messages`<br/>• `manage_messages`<br/>• `embed_links`<br/>• `attach_files`<br/>• `read_message_history`<br/>• `mention_everyone`<br/>• `external_emojis`<br/>• `connect`<br/>• `speak`<br/>• `mute_members`<br/>• `deafen_members`<br/>• `move_members`<br/>• `use_voice_activation`<br/>• `manage_roles`<br/>• `manage_webhooks`<br/>• `use_application_commands`<br/>• `request_to_speak`<br/>• `manage_threads`<br/>• `create_public_threads`<br/>• `create_private_threads`<br/>• `external_stickers`<br/>• `send_messages_in_threads`

## editvoicechannel userlimit (Hybrid Command)
 - Usage: `[p]editvoicechannel userlimit <channel> <user_limit> `
 - Slash Usage: `/editvoicechannel userlimit <channel> <user_limit> `
 - Aliases: `user_limit`
 - Checks: `server_only`

Edit voice channel user limit.<br/><br/>It must be a number between 0 and 99.

## editvoicechannel category (Hybrid Command)
 - Usage: `[p]editvoicechannel category <channel> <category> `
 - Slash Usage: `/editvoicechannel category <channel> <category> `
 - Checks: `server_only`

Edit voice channel category.

## editvoicechannel delete (Hybrid Command)
 - Usage: `[p]editvoicechannel delete <channel> [confirmation=False] `
 - Slash Usage: `/editvoicechannel delete <channel> [confirmation=False] `
 - Checks: `server_only`

Delete voice channel.

## editvoicechannel list (Hybrid Command)
 - Usage: `[p]editvoicechannel list `
 - Slash Usage: `/editvoicechannel list `
 - Checks: `server_only`

List all voice channels in the current server.

## editvoicechannel bitrate (Hybrid Command)
 - Usage: `[p]editvoicechannel bitrate <channel> <bitrate> `
 - Slash Usage: `/editvoicechannel bitrate <channel> <bitrate> `
 - Checks: `server_only`

Edit voice channel bitrate.<br/><br/>It must be a number between 8000 and<br/>Level 1: 128000<br/>Level 2: 256000<br/>Level 3: 384000

## editvoicechannel position (Hybrid Command)
 - Usage: `[p]editvoicechannel position <channel> <position> `
 - Slash Usage: `/editvoicechannel position <channel> <position> `
 - Checks: `server_only`

Edit voice channel position.<br/><br/>Warning: Only voice channels are taken into account. Channel 1 is the highest positioned voice channel.<br/>Channels cannot be moved to a position that takes them out of their current category.

## editvoicechannel syncpermissions (Hybrid Command)
 - Usage: `[p]editvoicechannel syncpermissions <channel> [sync_permissions=None] `
 - Slash Usage: `/editvoicechannel syncpermissions <channel> [sync_permissions=None] `
 - Aliases: `sync_permissions`
 - Checks: `server_only`

Edit voice channel sync permissions.

## editvoicechannel view (Hybrid Command)
 - Usage: `[p]editvoicechannel view <channel> `
 - Slash Usage: `/editvoicechannel view <channel> `
 - Aliases: `-`
 - Checks: `server_only`

View and edit voice channel.

## editvoicechannel invite (Hybrid Command)
 - Usage: `[p]editvoicechannel invite <channel> [max_age=None] [max_uses=None] [temporary=False] [unique=True] `
 - Slash Usage: `/editvoicechannel invite <channel> [max_age=None] [max_uses=None] [temporary=False] [unique=True] `
 - Checks: `server_only`

Create an invite for a voice channel.<br/><br/>`max_age`: How long the invite should last in days. If it's 0 then the invite doesn't expire.<br/>`max_uses`: How many uses the invite could be used for. If it's 0 then there are unlimited uses.<br/>`temporary`: Denotes that the invite grants temporary membership (i.e. they get kicked after they disconnect).<br/>`unique`: Indicates if a unique invite URL should be created. Defaults to True. If this is set to False then it will return a previously created invite.

## editvoicechannel nsfw (Hybrid Command)
 - Usage: `[p]editvoicechannel nsfw <channel> [nsfw=None] `
 - Slash Usage: `/editvoicechannel nsfw <channel> [nsfw=None] `
 - Checks: `server_only`

Edit voice channel nsfw.

## editvoicechannel name (Hybrid Command)
 - Usage: `[p]editvoicechannel name <channel> <name> `
 - Slash Usage: `/editvoicechannel name <channel> <name> `
 - Checks: `server_only`

Edit voice channel name.

# editthread (Hybrid Command)
 - Usage: `[p]editthread `
 - Slash Usage: `/editthread `
 - Checks: `server_only`

Commands for edit a text channel.

## editthread invitable (Hybrid Command)
 - Usage: `[p]editthread invitable <thread> [invitable=None] `
 - Slash Usage: `/editthread invitable <thread> [invitable=None] `
 - Checks: `server_only`

Edit thread invitable.

## editthread appliedtags (Hybrid Command)
 - Usage: `[p]editthread appliedtags <thread> <applied_tags> `
 - Slash Usage: `/editthread appliedtags <thread> <applied_tags> `
 - Aliases: `applied_tags`
 - Checks: `server_only`

Edit thread applied tags.<br/><br/>```<br/>[p]editthread appliedtags "<name>|<emoji>|[moderated]"<br/>[p]editthread appliedtags "Reporting|⚠️|True" "Bug|🐛"<br/>```

## editthread archived (Hybrid Command)
 - Usage: `[p]editthread archived <thread> [archived=None] `
 - Slash Usage: `/editthread archived <thread> [archived=None] `
 - Checks: `server_only`

Edit thread archived.

## editthread pinned (Hybrid Command)
 - Usage: `[p]editthread pinned <thread> <pinned> `
 - Slash Usage: `/editthread pinned <thread> <pinned> `
 - Checks: `server_only`

Edit thread pinned.

## editthread slowmodedelay (Hybrid Command)
 - Usage: `[p]editthread slowmodedelay <thread> <slowmode_delay> `
 - Slash Usage: `/editthread slowmodedelay <thread> <slowmode_delay> `
 - Aliases: `slowmode_delay`
 - Checks: `server_only`

Edit thread slowmode delay.

## editthread adduser (Hybrid Command)
 - Usage: `[p]editthread adduser <thread> <member> `
 - Slash Usage: `/editthread adduser <thread> <member> `
 - Aliases: `addmember, add_user, and add_member`
 - Checks: `server_only`

Add member to thread.

## editthread autoarchiveduration (Hybrid Command)
 - Usage: `[p]editthread autoarchiveduration <thread> <auto_archive_duration> `
 - Slash Usage: `/editthread autoarchiveduration <thread> <auto_archive_duration> `
 - Aliases: `auto_archive_duration`
 - Checks: `server_only`

Edit thread auto archive duration.

## editthread removeuser (Hybrid Command)
 - Usage: `[p]editthread removeuser <thread> <member> `
 - Slash Usage: `/editthread removeuser <thread> <member> `
 - Aliases: `removemember, remove_user, and remove_member`
 - Checks: `server_only`

Remove member from thread.

## editthread view (Hybrid Command)
 - Usage: `[p]editthread view [thread=None] `
 - Slash Usage: `/editthread view [thread=None] `
 - Aliases: `-`
 - Checks: `server_only`

View and edit thread.

## editthread locked (Hybrid Command)
 - Usage: `[p]editthread locked <thread> [locked=None] `
 - Slash Usage: `/editthread locked <thread> [locked=None] `
 - Checks: `server_only`

Edit thread locked.

## editthread delete (Hybrid Command)
 - Usage: `[p]editthread delete <thread> [confirmation=False] `
 - Slash Usage: `/editthread delete <thread> [confirmation=False] `
 - Checks: `server_only`

Delete a thread.

## editthread create (Hybrid Command)
 - Usage: `[p]editthread create [channel=None] [message=None] <name> `
 - Slash Usage: `/editthread create [channel=None] [message=None] <name> `
 - Restricted to: `ADMIN`
 - Aliases: `new and +`
 - Checks: `server_only`

Create a thread.<br/><br/>You'll join it automatically.

## editthread name (Hybrid Command)
 - Usage: `[p]editthread name <thread> <name> `
 - Slash Usage: `/editthread name <thread> <name> `
 - Checks: `server_only`

Edit thread name.

## editthread list (Hybrid Command)
 - Usage: `[p]editthread list `
 - Slash Usage: `/editthread list `
 - Checks: `server_only`

List all threads in the current server.

# edittextchannel (Hybrid Command)
 - Usage: `[p]edittextchannel `
 - Slash Usage: `/edittextchannel `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Commands for edit a text channel.

## edittextchannel position (Hybrid Command)
 - Usage: `[p]edittextchannel position <channel> <position> `
 - Slash Usage: `/edittextchannel position <channel> <position> `
 - Checks: `server_only`

Edit text channel position.<br/><br/>Warning: Only text channels are taken into account. Channel 1 is the highest positioned text channel.<br/>Channels cannot be moved to a position that takes them out of their current category.

## edittextchannel slowmodedelay (Hybrid Command)
 - Usage: `[p]edittextchannel slowmodedelay <channel> <slowmode_delay> `
 - Slash Usage: `/edittextchannel slowmodedelay <channel> <slowmode_delay> `
 - Aliases: `slowmode_delay`
 - Checks: `server_only`

Edit text channel slowmode delay.<br/><br/>Specifies the slowmode rate limit for user in this channel. A value of 0s disables slowmode. The maximum value possible is 21600s.

## edittextchannel create (Hybrid Command)
 - Usage: `[p]edittextchannel create [category=None] <name> `
 - Slash Usage: `/edittextchannel create [category=None] <name> `
 - Aliases: `new and +`
 - Checks: `server_only`

Create a text channel.

## edittextchannel list (Hybrid Command)
 - Usage: `[p]edittextchannel list `
 - Slash Usage: `/edittextchannel list `
 - Checks: `server_only`

List all text channels in the current server.

## edittextchannel syncpermissions (Hybrid Command)
 - Usage: `[p]edittextchannel syncpermissions <channel> [sync_permissions=None] `
 - Slash Usage: `/edittextchannel syncpermissions <channel> [sync_permissions=None] `
 - Aliases: `sync_permissions`
 - Checks: `server_only`

Edit text channel syncpermissions with category.

## edittextchannel category (Hybrid Command)
 - Usage: `[p]edittextchannel category <channel> <category> `
 - Slash Usage: `/edittextchannel category <channel> <category> `
 - Checks: `server_only`

Edit text channel category.

## edittextchannel defaultautoarchiveduration (Hybrid Command)
 - Usage: `[p]edittextchannel defaultautoarchiveduration <channel> <default_auto_archive_duration> `
 - Slash Usage: `/edittextchannel defaultautoarchiveduration <channel> <default_auto_archive_duration> `
 - Aliases: `default_auto_archive_duration`
 - Checks: `server_only`

Edit text channel default auto archive duration.<br/><br/>The new default auto archive duration in minutes for threads created in this channel. Must be one of `60`, `1440`, `4320`, or `10080`.

## edittextchannel delete (Hybrid Command)
 - Usage: `[p]edittextchannel delete <channel> [confirmation=False] `
 - Slash Usage: `/edittextchannel delete <channel> [confirmation=False] `
 - Aliases: `-`
 - Checks: `server_only`

Delete a text channel.

## edittextchannel invite (Hybrid Command)
 - Usage: `[p]edittextchannel invite <channel> [max_age=None] [max_uses=None] [temporary=False] [unique=True] `
 - Slash Usage: `/edittextchannel invite <channel> [max_age=None] [max_uses=None] [temporary=False] [unique=True] `
 - Checks: `server_only`

Create an invite for a text channel.<br/><br/>`max_age`: How long the invite should last in days. If it's 0 then the invite doesn't expire.<br/>`max_uses`: How many uses the invite could be used for. If it's 0 then there are unlimited uses.<br/>`temporary`: Denotes that the invite grants temporary membership (i.e. they get kicked after they disconnect).<br/>`unique`: Indicates if a unique invite URL should be created. Defaults to True. If this is set to False then it will return a previously created invite.

## edittextchannel topic (Hybrid Command)
 - Usage: `[p]edittextchannel topic <channel> <topic> `
 - Slash Usage: `/edittextchannel topic <channel> <topic> `
 - Checks: `server_only`

Edit text channel topic.

## edittextchannel type (Hybrid Command)
 - Usage: `[p]edittextchannel type <channel> <_type> `
 - Slash Usage: `/edittextchannel type <channel> <_type> `
 - Checks: `server_only`

Edit text channel type.<br/><br/>`text`: 0<br/>`news`: 5<br/>Currently, only conversion between ChannelType.text and ChannelType.news is supported. This is only available to servers that contain NEWS in Guild.features.

## edittextchannel defaultthreadslowmodedelay (Hybrid Command)
 - Usage: `[p]edittextchannel defaultthreadslowmodedelay <channel> <default_thread_slowmode_delay> `
 - Slash Usage: `/edittextchannel defaultthreadslowmodedelay <channel> <default_thread_slowmode_delay> `
 - Aliases: `default_thread_slowmode_delay`
 - Checks: `server_only`

Edit text channel default thread slowmode delay.<br/><br/>The new default thread slowmode delay in seconds for threads created in this channel. Must be between 0 and 21600 (6 hours) seconds.

## edittextchannel overwrites (Hybrid Command)
 - Usage: `[p]edittextchannel overwrites <channel> <roles_or_users> <true_or_false> <permissions> `
 - Slash Usage: `/edittextchannel overwrites <channel> <roles_or_users> <true_or_false> <permissions> `
 - Aliases: `permissions and perms`
 - Checks: `server_only`

Edit text channel overwrites/permissions.<br/><br/>You may not specify `True` or `False` to reset the permission(s).<br/>You must possess the permissions you wish to modify.<br/><br/>• `create_instant_invite`<br/>• `manage_channels`<br/>• `add_reactions`<br/>• `priority_speaker`<br/>• `stream`<br/>• `read_messages`<br/>• `send_messages`<br/>• `send_tts_messages`<br/>• `manage_messages`<br/>• `embed_links`<br/>• `attach_files`<br/>• `read_message_history`<br/>• `mention_everyone`<br/>• `external_emojis`<br/>• `connect`<br/>• `speak`<br/>• `mute_members`<br/>• `deafen_members`<br/>• `move_members`<br/>• `use_voice_activation`<br/>• `manage_roles`<br/>• `manage_webhooks`<br/>• `use_application_commands`<br/>• `request_to_speak`<br/>• `manage_threads`<br/>• `create_public_threads`<br/>• `create_private_threads`<br/>• `external_stickers`<br/>• `send_messages_in_threads`

## edittextchannel view (Hybrid Command)
 - Usage: `[p]edittextchannel view [channel=None] `
 - Slash Usage: `/edittextchannel view [channel=None] `
 - Checks: `server_only`

View and edit text channel.

## edittextchannel clone (Hybrid Command)
 - Usage: `[p]edittextchannel clone <channel> <name> `
 - Slash Usage: `/edittextchannel clone <channel> <name> `
 - Checks: `server_only`

Clone a text channel.

## edittextchannel nsfw (Hybrid Command)
 - Usage: `[p]edittextchannel nsfw <channel> [nsfw=None] `
 - Slash Usage: `/edittextchannel nsfw <channel> [nsfw=None] `
 - Checks: `server_only`

Edit text channel nsfw.

## edittextchannel name (Hybrid Command)
 - Usage: `[p]edittextchannel name <channel> <name> `
 - Slash Usage: `/edittextchannel name <channel> <name> `
 - Checks: `server_only`

Edit text channel name.

# editrole (Hybrid Command)
 - Usage: `[p]editrole `
 - Slash Usage: `/editrole `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Commands for edit a role.

## editrole view (Hybrid Command)
 - Usage: `[p]editrole view <role> `
 - Slash Usage: `/editrole view <role> `
 - Checks: `server_only`

View and edit role.

## editrole permissions (Hybrid Command)
 - Usage: `[p]editrole permissions <role> <true_or_false> <permissions> `
 - Slash Usage: `/editrole permissions <role> <true_or_false> <permissions> `
 - Checks: `server_only`

Edit role permissions.<br/><br/>You must possess the permissions you wish to modify.<br/><br/>• `create_instant_invite`<br/>• `manage_channels`<br/>• `add_reactions`<br/>• `priority_speaker`<br/>• `stream`<br/>• `read_messages`<br/>• `send_messages`<br/>• `send_tts_messages`<br/>• `manage_messages`<br/>• `embed_links`<br/>• `attach_files`<br/>• `read_message_history`<br/>• `mention_everyone`<br/>• `external_emojis`<br/>• `connect`<br/>• `speak`<br/>• `mute_members`<br/>• `deafen_members`<br/>• `move_members`<br/>• `use_voice_activation`<br/>• `manage_roles`<br/>• `manage_webhooks`<br/>• `use_application_commands`<br/>• `request_to_speak`<br/>• `manage_threads`<br/>• `create_public_threads`<br/>• `create_private_threads`<br/>• `external_stickers`<br/>• `send_messages_in_threads`

## editrole name (Hybrid Command)
 - Usage: `[p]editrole name <role> <name> `
 - Slash Usage: `/editrole name <role> <name> `
 - Checks: `server_only`

Edit role name.

## editrole position (Hybrid Command)
 - Usage: `[p]editrole position <role> <position> `
 - Slash Usage: `/editrole position <role> <position> `
 - Checks: `server_only`

Edit role position.<br/><br/>Warning: The role with a position 1 is the highest role in the Discord hierarchy.

## editrole delete (Hybrid Command)
 - Usage: `[p]editrole delete <role> [confirmation=False] `
 - Slash Usage: `/editrole delete <role> [confirmation=False] `
 - Aliases: `-`
 - Checks: `server_only`

Delete a role.

## editrole mentionable (Hybrid Command)
 - Usage: `[p]editrole mentionable <role> [mentionable=None] `
 - Slash Usage: `/editrole mentionable <role> [mentionable=None] `
 - Checks: `server_only`

Edit role mentionable.

## editrole displayicon (Hybrid Command)
 - Usage: `[p]editrole displayicon <role> [display_icon=None] `
 - Slash Usage: `/editrole displayicon <role> [display_icon=None] `
 - Aliases: `icon and display_icon`
 - Checks: `server_only`

Edit role display icon.<br/><br/>`display_icon` can be an Unicode emoji, a custom emoji or an url. You can also upload an attachment.

## editrole color (Hybrid Command)
 - Usage: `[p]editrole color <role> <color> `
 - Slash Usage: `/editrole color <role> <color> `
 - Aliases: `colour`
 - Checks: `server_only`

Edit role color.

## editrole list (Hybrid Command)
 - Usage: `[p]editrole list `
 - Slash Usage: `/editrole list `
 - Checks: `server_only`

List all roles in the current server.

## editrole create (Hybrid Command)
 - Usage: `[p]editrole create [color=None] <name> `
 - Slash Usage: `/editrole create [color=None] <name> `
 - Aliases: `new and +`
 - Checks: `server_only`

Create a role.

## editrole hoist (Hybrid Command)
 - Usage: `[p]editrole hoist <role> [hoist=None] `
 - Slash Usage: `/editrole hoist <role> [hoist=None] `
 - Checks: `server_only`

Edit role hoist.

# editserver (Hybrid Command)
 - Usage: `[p]editserver `
 - Slash Usage: `/editserver `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Commands for edit a server.

## editserver vanitycode (Hybrid Command)
 - Usage: `[p]editserver vanitycode <vanity_code> `
 - Slash Usage: `/editserver vanitycode <vanity_code> `
 - Aliases: `vanity_code`
 - Checks: `server_only`

Edit server vanity code.

## editserver defaultnotifications (Hybrid Command)
 - Usage: `[p]editserver defaultnotifications <default_notifications> `
 - Slash Usage: `/editserver defaultnotifications <default_notifications> `
 - Aliases: `notificationslevel and default_notifications`
 - Checks: `server_only`

Edit server notification level.

## editserver ruleschannel (Hybrid Command)
 - Usage: `[p]editserver ruleschannel [rules_channel=None] `
 - Slash Usage: `/editserver ruleschannel [rules_channel=None] `
 - Aliases: `rules_channel`
 - Checks: `server_only`

Edit server rules channel.

## editserver invitesdisabled (Hybrid Command)
 - Usage: `[p]editserver invitesdisabled <invites_disabled> `
 - Slash Usage: `/editserver invitesdisabled <invites_disabled> `
 - Aliases: `invites_disabled`
 - Checks: `server_only`

Edit server invites disabled state.

## editserver view (Hybrid Command)
 - Usage: `[p]editserver view `
 - Slash Usage: `/editserver view `
 - Checks: `server_only`

View and edit server.

## editserver banner (Hybrid Command)
 - Usage: `[p]editserver banner [banner=None] `
 - Slash Usage: `/editserver banner [banner=None] `
 - Checks: `server_only`

Edit server banner.<br/><br/>You can use an URL or upload an attachment.

## editserver preferredlocale (Hybrid Command)
 - Usage: `[p]editserver preferredlocale <preferred_locale> `
 - Slash Usage: `/editserver preferredlocale <preferred_locale> `
 - Aliases: `preferred_locale`
 - Checks: `server_only`

Edit server preferred locale.<br/><br/>american_english = 'en-US'<br/>british_english = 'en-GB'<br/>bulgarian = 'bg'<br/>chinese = 'zh-CN'<br/>taiwan_chinese = 'zh-TW'<br/>croatian = 'hr'<br/>czech = 'cs'<br/>danish = 'da'<br/>dutch = 'nl'<br/>finnish = 'fi'<br/>french = 'fr'<br/>german = 'de'<br/>greek = 'el'<br/>hindi = 'hi'<br/>hungarian = 'hu'<br/>italian = 'it'<br/>japanese = 'ja'<br/>korean = 'ko'<br/>lithuanian = 'lt'<br/>norwegian = 'no'<br/>polish = 'pl'<br/>brazil_portuguese = 'pt-BR'<br/>romanian = 'ro'<br/>russian = 'ru'<br/>spain_spanish = 'es-ES'<br/>swedish = 'sv-SE'<br/>thai = 'th'<br/>turkish = 'tr'<br/>ukrainian = 'uk'<br/>vietnamese = 'vi'

## editserver discoverable (Hybrid Command)
 - Usage: `[p]editserver discoverable <discoverable> `
 - Slash Usage: `/editserver discoverable <discoverable> `
 - Checks: `server_only`

Edit server discoverable state.

## editserver raidalertsdisabled (Hybrid Command)
 - Usage: `[p]editserver raidalertsdisabled <raid_alerts_disabled> `
 - Slash Usage: `/editserver raidalertsdisabled <raid_alerts_disabled> `
 - Aliases: `raid_alerts_disabled`
 - Checks: `server_only`

Edit server invites raid alerts disabled state.

## editserver delete (Hybrid Command)
 - Usage: `[p]editserver delete [confirmation=False] `
 - Slash Usage: `/editserver delete [confirmation=False] `
 - Restricted to: `BOT_OWNER`
 - Aliases: `-`
 - Checks: `server_only`

Delete server (if the bot is owner).

## editserver owner (Hybrid Command)
 - Usage: `[p]editserver owner <owner> [confirmation=False] `
 - Slash Usage: `/editserver owner <owner> [confirmation=False] `
 - Restricted to: `BOT_OWNER`
 - Checks: `server_only`

Edit server owner (if the bot is bot owner).

## editserver verificationlevel (Hybrid Command)
 - Usage: `[p]editserver verificationlevel <verification_level> `
 - Slash Usage: `/editserver verificationlevel <verification_level> `
 - Aliases: `verification_level`
 - Checks: `server_only`

Edit server verification level.

## editserver premiumprogressbarenabled (Hybrid Command)
 - Usage: `[p]editserver premiumprogressbarenabled [premium_progress_bar_enabled=None] `
 - Slash Usage: `/editserver premiumprogressbarenabled [premium_progress_bar_enabled=None] `
 - Aliases: `premium_progress_bar_enabled`
 - Checks: `server_only`

Edit server premium progress bar enabled.

## editserver widgetchannel (Hybrid Command)
 - Usage: `[p]editserver widgetchannel [widget_channel=None] `
 - Slash Usage: `/editserver widgetchannel [widget_channel=None] `
 - Aliases: `widget_channel`
 - Checks: `server_only`

Edit server invites widget channel.

## editserver clone (Hybrid Command)
 - Usage: `[p]editserver clone <name> `
 - Slash Usage: `/editserver clone <name> `
 - Restricted to: `BOT_OWNER`
 - Checks: `server_only`

Clone a server.

## editserver afktimeout (Hybrid Command)
 - Usage: `[p]editserver afktimeout <afk_timeout> `
 - Slash Usage: `/editserver afktimeout <afk_timeout> `
 - Aliases: `afk_timeout`
 - Checks: `server_only`

Edit server afk timeout.

## editserver systemchannel (Hybrid Command)
 - Usage: `[p]editserver systemchannel [system_channel=None] `
 - Slash Usage: `/editserver systemchannel [system_channel=None] `
 - Aliases: `system_channel`
 - Checks: `server_only`

Edit server system channel.

## editserver discoverysplash (Hybrid Command)
 - Usage: `[p]editserver discoverysplash [discovery_splash=None] `
 - Slash Usage: `/editserver discoverysplash [discovery_splash=None] `
 - Aliases: `discovery_splash`
 - Checks: `server_only`

Edit server discovery splash.<br/><br/>You can use an URL or upload an attachment.

## editserver publicupdateschannel (Hybrid Command)
 - Usage: `[p]editserver publicupdateschannel [public_updates_channel=None] `
 - Slash Usage: `/editserver publicupdateschannel [public_updates_channel=None] `
 - Aliases: `public_updates_channel`
 - Checks: `server_only`

Edit server public updates channel.

## editserver widgetenabled (Hybrid Command)
 - Usage: `[p]editserver widgetenabled <widget_enabled> `
 - Slash Usage: `/editserver widgetenabled <widget_enabled> `
 - Aliases: `widget_enabled`
 - Checks: `server_only`

Edit server invites widget enabled state.

## editserver splash (Hybrid Command)
 - Usage: `[p]editserver splash [splash=None] `
 - Slash Usage: `/editserver splash [splash=None] `
 - Aliases: `invite_splash`
 - Checks: `server_only`

Edit server splash.<br/><br/>You can use an URL or upload an attachment.

## editserver afkchannel (Hybrid Command)
 - Usage: `[p]editserver afkchannel [afk_channel] `
 - Slash Usage: `/editserver afkchannel [afk_channel] `
 - Aliases: `afk_channel`
 - Checks: `server_only`

Edit server afkchannel.

## editserver explicitcontentfilter (Hybrid Command)
 - Usage: `[p]editserver explicitcontentfilter <explicit_content_filter> `
 - Slash Usage: `/editserver explicitcontentfilter <explicit_content_filter> `
 - Aliases: `explicit_content_filter`
 - Checks: `server_only`

Edit server explicit content filter.

## editserver description (Hybrid Command)
 - Usage: `[p]editserver description [description] `
 - Slash Usage: `/editserver description [description] `
 - Checks: `server_only`

Edit server description.

## editserver create (Hybrid Command)
 - Usage: `[p]editserver create <name> [template_code=None] `
 - Slash Usage: `/editserver create <name> [template_code=None] `
 - Restricted to: `BOT_OWNER`
 - Aliases: `new and +`
 - Checks: `server_only`

Create a server with the bot as owner.

## editserver community (Hybrid Command)
 - Usage: `[p]editserver community <community> `
 - Slash Usage: `/editserver community <community> `
 - Checks: `server_only`

Edit server community state.

## editserver systemchannelflags (Hybrid Command)
 - Usage: `[p]editserver systemchannelflags <system_channel_flags> `
 - Slash Usage: `/editserver systemchannelflags <system_channel_flags> `
 - Aliases: `system_channel_flags`
 - Checks: `server_only`

Edit server system channel flags.

## editserver safetyalertschannel (Hybrid Command)
 - Usage: `[p]editserver safetyalertschannel [safety_alerts_channel=None] `
 - Slash Usage: `/editserver safetyalertschannel [safety_alerts_channel=None] `
 - Aliases: `safety_alerts_channel`
 - Checks: `server_only`

Edit server invites safety alerts channel.

## editserver icon (Hybrid Command)
 - Usage: `[p]editserver icon [icon=None] `
 - Slash Usage: `/editserver icon [icon=None] `
 - Checks: `server_only`

Edit server icon.<br/><br/>You can use an URL or upload an attachment.

## editserver name (Hybrid Command)
 - Usage: `[p]editserver name <name> `
 - Slash Usage: `/editserver name <name> `
 - Checks: `server_only`

Edit server name.

