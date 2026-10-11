---
type: author
aliases: ["Jens Peter Jacobsen"]
born: 1847
died: 1885
language: Danish
roles: ["novelist", "poet", "scientist"]
priority: 3
status: not-started
wikipedia: ""
influenced_by:
  - "[[Flaubert, Gustave]]"
---

## Why read them
Danish prose stylist who shaped Rilke and the Scandinavian modernists.

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
