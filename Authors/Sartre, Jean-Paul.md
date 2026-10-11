---
type: author
aliases: ["Jean-Paul Sartre"]
born: 1905
died: 1980
language: French
roles: ["biographer", "critic", "dramatist", "novelist", "philosopher", "screenwriter"]
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Nietzsche, Friedrich]]"
works_raw: "No Exit"
---

## Why read them
Existentialism: freedom, bad faith and responsibility.

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
