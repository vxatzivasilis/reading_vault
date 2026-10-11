---
type: author
aliases: ["Miguel de Cervantes"]
born: 1547
died: 1616
language: Spanish
roles: ["writer"]
priority: 4
status: not-started
wikipedia: ""
influenced_by: []
---

## Why read them


## Must-read works
```dataview
TABLE year, form, status FROM "Works"
WHERE author = this.file.link
SORT year ASC
```

## Influenced (computed automatically)
```dataview
LIST FROM "Authors"
WHERE contains(influenced_by, this.file.link)
```

## Notes
