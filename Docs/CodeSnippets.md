# CodeSnippets Help

A cog to send code content from a GitHub/Gist/GitLab/BitBucket/Pastebin/Hastebin URL!

# codesnippets (Hybrid Command)
 - Usage: `[p]codesnippets [limit=3] <urls> `
 - Slash Usage: `/codesnippets [limit=3] <urls> `
 - Aliases: `codesnippet`

Send code content from a GitHub/Gist/GitLab/BitBucket/Pastebin/Hastebin URL.

# setcodesnippets (Hybrid Command)
 - Usage: `[p]setcodesnippets `
 - Slash Usage: `/setcodesnippets `
 - Restricted to: `ADMIN`
 - Checks: `server_only`

Configure CodeSnippets.

## setcodesnippets removechannel (Hybrid Command)
 - Usage: `[p]setcodesnippets removechannel <channel> `
 - Slash Usage: `/setcodesnippets removechannel <channel> `
 - Checks: `server_only`

Remove a channel where the cog have to send automatically code snippets from URLs.

## setcodesnippets addchannel (Hybrid Command)
 - Usage: `[p]setcodesnippets addchannel <channel> `
 - Slash Usage: `/setcodesnippets addchannel <channel> `
 - Checks: `server_only`

Add a channel where the cog have to send automatically code snippets from URLs.

## setcodesnippets showsettings (Hybrid Command)
 - Usage: `[p]setcodesnippets showsettings [with_dev=False] `
 - Slash Usage: `/setcodesnippets showsettings [with_dev=False] `
 - Checks: `server_only`

Show all settings for the cog with defaults and values.

