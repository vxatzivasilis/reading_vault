---
type: author
aliases: ["Toni Morrison"]
born: 
died: 
language: English
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Woolf, Virginia]]"
works_raw: "Beloved"
---

## Why read them
American history, memory and race rendered as myth.

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
