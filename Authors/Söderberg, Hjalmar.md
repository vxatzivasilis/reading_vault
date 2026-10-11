---
type: author
aliases: ["Hjalmar Söderberg"]
born: 1869
died: 1941
language: Swedish
roles: ["dramatist", "journalist", "novelist", "short story writer"]
priority: 5
status: not-started
wikipedia: ""
influenced_by:
  - "[[Jacobsen, Jens Peter]]"
---

## Why read them
Cool Swedish irony and urban melancholy.

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
