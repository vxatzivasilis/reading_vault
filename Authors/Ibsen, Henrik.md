---
type: author
aliases: ["Henrik Ibsen"]
born: 1828
died: 1906
language: Norwegian
roles: ["dramatist"]
priority: 1
status: not-started
wikipedia: ""
influenced_by:
  - "[[Goethe, Johann Wolfgang von]]"
---

## Why read them
Founder of modern realist drama; domestic life turned into moral trial.

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
