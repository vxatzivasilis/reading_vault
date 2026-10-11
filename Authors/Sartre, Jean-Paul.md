---
type: author
aliases: ["Jean-Paul Sartre"]
born: 1905
died: 1980
language: French
roles: ["biographer", "critic", "dramatist", "novelist", "philosopher", "screenwriter"]
priority: 
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "No Exit"
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
