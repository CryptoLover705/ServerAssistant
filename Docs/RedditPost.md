# RedditPost Help

A reddit auto posting cog.

# redditpost (Hybrid Command)
 - Usage: `[p]redditpost `
 - Slash Usage: `/redditpost `
 - Restricted to: `ADMIN`
 - Aliases: `redditfeed`
 - Checks: `server_only`

Reddit auto-feed posting.

## redditpost imageonly (Hybrid Command)
 - Usage: `[p]redditpost imageonly <subreddit> <on_or_off> [channel=None] `
 - Slash Usage: `/redditpost imageonly <subreddit> <on_or_off> [channel=None] `

Whether to only post posts that contain an image.

## redditpost source (Hybrid Command)
 - Usage: `[p]redditpost source <subreddit> <on_or_off> [channel=None] `
 - Slash Usage: `/redditpost source <subreddit> <on_or_off> [channel=None] `

Whether to include a Source button..

## redditpost delay (Hybrid Command)
 - Usage: `[p]redditpost delay <time> `
 - Slash Usage: `/redditpost delay <time> `
 - Restricted to: `BOT_OWNER`

Set the delay used to check for new content.

## redditpost add (Hybrid Command)
 - Usage: `[p]redditpost add <subreddit> [channel=None] `
 - Slash Usage: `/redditpost add <subreddit> [channel=None] `

Add a subreddit to post new content from.

## redditpost setup (Hybrid Command)
 - Usage: `[p]redditpost setup `
 - Slash Usage: `/redditpost setup `
 - Restricted to: `BOT_OWNER`

Details on setting up RedditPost

## redditpost publish (Hybrid Command)
 - Usage: `[p]redditpost publish <subreddit> <on_or_off> [channel=None] `
 - Slash Usage: `/redditpost publish <subreddit> <on_or_off> [channel=None] `

Whether to publish posts - must be a news channel.

## redditpost webhook (Hybrid Command)
 - Usage: `[p]redditpost webhook <subreddit> <webhook> [channel=None] `
 - Slash Usage: `/redditpost webhook <subreddit> <webhook> [channel=None] `
 - Aliases: `webhooks`

Whether to send the post as a webhook or message from the bot.

## redditpost remove (Hybrid Command)
 - Usage: `[p]redditpost remove <subreddit> [channel=None] `
 - Slash Usage: `/redditpost remove <subreddit> [channel=None] `

Removes a subreddit from the current channel, or a provided one.

## redditpost list (Hybrid Command)
 - Usage: `[p]redditpost list [channel=None] `
 - Slash Usage: `/redditpost list [channel=None] `

Lists the current subreddits for the current channel, or a provided one.

## redditpost latest (Hybrid Command)
 - Usage: `[p]redditpost latest <subreddit> <latest> [channel=None] `
 - Slash Usage: `/redditpost latest <subreddit> <latest> [channel=None] `

Whether to fetch all posts or just the latest post.

## redditpost force (Hybrid Command)
 - Usage: `[p]redditpost force <subreddit> [channel=None] `
 - Slash Usage: `/redditpost force <subreddit> [channel=None] `

Force the latest post.

