---
type: author
aliases: ["Gustave Flaubert"]
born: 1821
died: 1880
language: 
roles: []
priority: 6
status: not-started
wikipedia: "https://en.wikipedia.org/wiki/Gustave_Flaubert"
influenced_by:
  - "[[Balzac, Honoré de]]"
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
