---
type: author
aliases: ["Virginia Wolf"]
born: 
died: 
language: English
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Proust, Marcel]]"
  - "[[Chekhov, Anton]]"
  - "[[James, Henry]]"
works_raw: "Mrs Dalloway"
---

## Why read them
Stream of consciousness and the form of the modern novel; feminism in essays.

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
