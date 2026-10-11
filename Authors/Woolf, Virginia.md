---
type: author
aliases: ["Virginia Wolf"]
born: 
died: 
language: English
roles: []
priority: 
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "Mrs Dalloway"
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
