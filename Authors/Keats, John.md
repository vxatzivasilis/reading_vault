---
type: author
aliases: ["John Keats"]
born: 1795
died: 1821
language: 
roles: []
priority: 6
status: not-started
wikipedia: "https://en.wikipedia.org/wiki/John_Keats"
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
