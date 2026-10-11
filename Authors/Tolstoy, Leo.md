---
type: author
aliases: ["Leo Tolstoy"]
born: 1828
died: 1910
language: Russian
roles: ["writer"]
priority: 2
status: not-started
wikipedia: ""
influenced_by:
  - "[[Dickens, Charles]]"
  - "[[Schopenhauer, Arthur]]"
---

## Why read them
Realism at full scale, plus the moral questions of how to live and die.

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
