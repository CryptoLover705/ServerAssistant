# Conversions Help

Gather information about various crypto currencies,<br/>stocks, and converts to different currencies

# btc
 - Usage: `[p]btc [amount=1.0] [currency=USD] [full=None] `
 - Aliases: `bitcoin and BTC`

converts from BTC to a given currency.<br/><br/>`[ammount=1.0]` The number of coins you want to know the price for.<br/>`[currency=USD]` The optional desired currency price. Defaults to USD.<br/>`[full=True]` is a True/False value whether to display just the converted amount<br/>or the full display for the currency

# eth
 - Usage: `[p]eth [amount=1.0] [currency=USD] [full=None] `
 - Aliases: `ethereum and ETH`

converts from ETH to a given currency.<br/><br/>`[ammount=1.0]` The number of coins you want to know the price for.<br/>`[currency=USD]` The optional desired currency price. Defaults to USD.<br/>`[full=True]` is a True/False value whether to display just the converted amount<br/>or the full display for the currency

# ltc
 - Usage: `[p]ltc [amount=1.0] [currency=USD] [full=None] `
 - Aliases: `litecoin and LTC`

converts from LTC to a given currency.<br/><br/>`[ammount=1.0]` The number of coins you want to know the price for.<br/>`[currency=USD]` The optional desired currency price. Defaults to USD.<br/>`[full=True]` is a True/False value whether to display just the converted amount<br/>or the full display for the currency

# xmr
 - Usage: `[p]xmr [amount=1.0] [currency=USD] [full=None] `
 - Aliases: `monero and XMR`

converts from XMR to a given currency.<br/><br/>`[ammount=1.0]` The number of coins you want to know the price for.<br/>`[currency=USD]` The optional desired currency price. Defaults to USD.<br/>`[full=True]` is a True/False value whether to display just the converted amount<br/>or the full display for the currency

# bch
 - Usage: `[p]bch [amount=1.0] [currency=USD] [full=None] `
 - Aliases: `bitcoin-cash and BCH`

converts from BCH to a given currency.<br/><br/>`[ammount=1.0]` The number of coins you want to know the price for.<br/>`[currency=USD]` The optional desired currency price. Defaults to USD.<br/>`[full=True]` is a True/False value whether to display just the converted amount<br/>or the full display for the currency

# doge
 - Usage: `[p]doge [amount=1.0] [currency=USD] [full=None] `
 - Aliases: `dogecoin and XDG`

converts from XDG to a given currency.<br/><br/>`[ammount=1.0]` The number of coins you want to know the price for.<br/>`[currency=USD]` The optional desired currency price. Defaults to USD.<br/>`[full=True]` is a True/False value whether to display just the converted amount<br/>or the full display for the currency

# multicoin
 - Usage: `[p]multicoin <coins> `

Gets the current USD value for a list of coins<br/><br/>`coins` must be a list of white space separated crypto coins<br/>e.g. `[p]multicoin BTC BCH LTC ETH DASH XRP`

# crypto
 - Usage: `[p]crypto <coin> [amount=1.0] [currency=USD] [full=None] `

Displays the latest information about a specified crypto currency<br/><br/>`<coin>` must be the name or symbol of a crypto coin<br/>`[ammount=1.0]` The number of coins you want to know the price for.<br/>`[currency=USD]` The optional desired currency price. Defaults to USD.<br/>`[full=True]` is a True/False value whether to display just the converted amount<br/>or the full display for the currency

# stock
 - Usage: `[p]stock <ticker> [currency=USD] `
 - Aliases: `ticker`

Gets current ticker symbol price.<br/><br/>`<ticker>` is the ticker symbol you want to look up<br/>`[currency]` is the currency you want to convert to defaults to USD

# cryptoapi
 - Usage: `[p]cryptoapi `
 - Restricted to: `BOT_OWNER`

Instructions for how to setup the stock API

# convertcurrency
 - Usage: `[p]convertcurrency <currency1> <currency2> [amount=1.0] `
 - Aliases: `currency`

Converts a value between 2 different currencies<br/><br/>`<currency1>` The first currency in [ISO 4217 format.](https://en.wikipedia.org/wiki/ISO_4217)<br/>`<currency2>` The second currency in [ISO 4217 format.](https://en.wikipedia.org/wiki/ISO_4217)<br/>`[amount=1.0]` is the ammount you want to convert default is 1.0

