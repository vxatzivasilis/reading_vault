---
type: author
aliases: ["Eugène Ionesco"]
born: 1909
died: 1994
language: French
roles: ["dramatist"]
priority: 6
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "The bald Soprano"
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
