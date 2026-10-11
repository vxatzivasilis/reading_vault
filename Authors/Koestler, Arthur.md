---
type: author
aliases: ["Arthur Koestler"]
born: 1905
died: 1983
language: English
roles: ["journalist", "writer"]
priority: 6
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
