---
type: author
aliases: ["T.S. Eliot"]
born: 
died: 
language: English
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Shakespeare, William]]"
  - "[[Marlowe, Christopher]]"
works_raw: "The Waste Land"
---

## Why read them
Modernist poetry and criticism: fragmentation and tradition.

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
