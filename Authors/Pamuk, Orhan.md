---
type: author
aliases: ["Orhan Pamuk"]
born: 
died: 
language: Turkish
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Dostoevsky, Fyodor]]"
  - "[[Proust, Marcel]]"
  - "[[Mann, Thomas]]"
works_raw: "The White Castle"
---

## Why read them
Istanbul, East and West, memory and collecting, in layered narrative.

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
