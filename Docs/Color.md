# Color Help

View embeds showcasing the supplied color and information about it

# color
 - Usage: `[p]color `
 - Aliases: `colour`

Group command for color commands

## color hex
 - Usage: `[p]color hex <hexa> `

Provides the RGB value and HSL value of a passed hexadecimal value.  Hexadecimal value must in the format of something like `#ffffff` or `0xffffff` to be used.

## color rgb
 - Usage: `[p]color rgb <highest> <r> <g> <b> `

Provides the hexadecimal value and HSL value of the rgb value given.  Each value must have a space between them.  Highest argument must be 1 or 255, indicating the highest value of a single value (r, g, or b).

## color msgshort
 - Usage: `[p]color msgshort <enable> `
 - Restricted to: `ADMIN`

Enable or disable the in-message shortcut.<br/><br/>In-message shortcuts can be used by using the hex, rgb or name after a `#` in the middle of a message, as follows:<br/><br/>`#000000` (hex)<br/>`#1,1,1` (rgb)<br/>`#black` (named)

## color name
 - Usage: `[p]color name <name> `

Provides the hexadecimal value, RGB value and HSL value of a passed color.  For example, pass `red` or `blue` as the name argument.

## color decimal
 - Usage: `[p]color decimal <decimal> `

Provides the RGB value of the decimal value given.

## color hsl
 - Usage: `[p]color hsl <h> <s> <l> `

Provides the hexadecimal value and the RGB value of the hsl value given.  Each value must have a space between them.

