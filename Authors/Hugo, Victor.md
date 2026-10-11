---
type: author
aliases: ["Victor Hugo"]
born: 1802
died: 1885
language: French
roles: ["dramatist", "essayist", "poet", "writer"]
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
