---
type: author
aliases: ["Federico García Lorca"]
born: 
died: 
language: Spanish
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "Blood Wedding"
---

## Why read them
Duende, folklore and tragedy in Spanish poetry and drama.

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
