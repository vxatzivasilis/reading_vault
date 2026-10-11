---
type: author
aliases: ["Saul Bellow"]
born: 1915
died: 2005
language: English
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by:
  - "[[Dostoevsky, Fyodor]]"
works_raw: "Humboldt’s Gift"
---

## Why read them
Intellectual energy and urban voice; the American novel of ideas.

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
