# Bingo Help

# bingoset
 - Usage: `[p]bingoset `
 - Restricted to: `MOD`
 - Checks: `server_only`

Commands for setting bingo settings

## bingoset reset
 - Usage: `[p]bingoset reset [member=None] `

Reset a users bingo card or reset the whole servers bingo card.

## bingoset clear
 - Usage: `[p]bingoset clear `

Clear out the current bingo cards tiles.

## bingoset box
 - Usage: `[p]bingoset box <colour> `

Set the colour of the Bingo card boxes border.<br/><br/>`colour` - must be a hex colour code

## bingoset stamp
 - Usage: `[p]bingoset stamp <colour> `

Set the colour of the "stamp" that fills the box.<br/><br/>`colour` - must be a hex colour code

## bingoset seed
 - Usage: `[p]bingoset seed <seed> `

Set an additional seed to the randomness of players cards.<br/><br/>`seed` - A number that is added to the player ID used to<br/>seed their card.<br/><br/>Use this to shuffle everyone's card while keeping the exact<br/>same tiles for a game of bingo. Default is 0.

## bingoset text
 - Usage: `[p]bingoset text <colour> `

Set the colour of the text.<br/><br/>`colour` - must be a hex colour code

## bingoset background
 - Usage: `[p]bingoset background <colour> `

Set the colour of the Bingo card background.<br/><br/>`colour` - must be a hex colour code

## bingoset name
 - Usage: `[p]bingoset name <name> `

Set the name of the current bingo card.<br/><br/>`name` - the name you want to use for the current bingo card.

## bingoset tiles
 - Usage: `[p]bingoset tiles <tiles> `

Set the tiles for the servers bingo cards.<br/><br/>`tiles` - Separate each tile with `;`

## bingoset watermark
 - Usage: `[p]bingoset watermark [image_url=None] `

Add a watermark image to the bingo card<br/><br/>`[image_url]` - Must be an image url with `.jpg` or `.png` extension.

## bingoset bgtile
 - Usage: `[p]bingoset bgtile [image_url=None] `

Set the background image (tiled).<br/><br/>This will override the background colour if set as it will attempt<br/>to tile the image over the entire background.<br/><br/>`[image_url]` - Must be an image url with `.jpg` or `.png` extension.

## bingoset settings
 - Usage: `[p]bingoset settings `

Show the current bingo card settings

## bingoset icon
 - Usage: `[p]bingoset icon [image_url=None] `

Add an icon image to the bingo card<br/><br/>`[image_url]` - Must be an image url with `.jpg` or `.png` extension.

## bingoset bingo
 - Usage: `[p]bingoset bingo <bingo> `

Set the "BINGO" of the board.<br/><br/>`bingo` - The word to use for bingo. Must be exactly 5 characters.

# bingo
 - Usage: `[p]bingo [stamp=None] `
 - Checks: `server_only`

Generate a Bingo Card<br/><br/>`stamp` - Select the tile that you would like to stamp. If not<br/>provided will just show your current bingo card.

