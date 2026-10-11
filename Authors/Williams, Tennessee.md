---
type: author
aliases: ["Tennessee Williams"]
born: 1911
died: 1983
language: English
roles: ["dramatist", "screenwriter"]
priority: 
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
