# Bookfiler™ Accounting

## Features

* Very fast categorizing expenses
* Multi-user support (clients have a server mode)
* double-entry bookkeeping system with optional abstraction for categorizing expenses

# Formats

| Bank | Format | Description |
|:-- |:-- |:-- |
|Chase|csv|universal format with moderate data. Transaction text info displayed as single description |
|Chase|qbo|best format for most information. separates description into transaction name and memo fields|
|Chase|qfx|same as above|
|Chase|qif|Very short form format. Descriptions are truncated|
|BoA|csv|has an extra address field that simply is parsed from description. Has a reference ID|
|BoA|qfx|xml formatted with basic transaction info and some account meta data|
|BoA|qif|short form with date year represented with 2 digits|
|BoA|qif|short form with date year represented with 4 digits|