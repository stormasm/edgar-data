### nushell commands

#### nushell xbrl to json

```
open ubnt-20200331_htm.xml | get xbrl | get children.LongTermDebt | get children

open ubnt-20200331_htm.xml | get xbrl | get children | to json | save -r me.json
```
