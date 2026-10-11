---
type: author
aliases: ["Rainer Maria Rilke"]
born: 
died: 
language: German
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Jacobsen, Jens Peter]]"
works_raw: "The Notebooks of Malte Laurids Brigge"
---

## Why read them
The great German-language lyric poet of inwardness and transformation.

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
