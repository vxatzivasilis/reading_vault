---
type: author
aliases: ["Samuel Beckett"]
born: 1906
died: 1989
language: English
roles: ["dramatist", "novelist", "poet", "short story writer"]
priority: 6
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "Endgame"
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
