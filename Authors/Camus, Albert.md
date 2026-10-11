---
type: author
aliases: ["Albert Camus"]
born: 1913
died: 1960
language: French
roles: ["dramatist", "journalist", "philosopher", "writer"]
priority: 6
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "The Stranger"
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
