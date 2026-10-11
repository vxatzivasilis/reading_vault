---
type: author
aliases: ["Knut Hamsun"]
born: 1859
died: 1952
language: Greek
roles: ["critic", "poet", "writer"]
priority: 5
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
