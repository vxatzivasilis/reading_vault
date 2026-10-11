---
type: author
aliases: ["Marcel Proust"]
born: 1871
died: 1922
language: French
roles: ["critic", "essayist", "novelist"]
priority: 4
status: not-started
wikipedia: ""
influenced_by:
  - "[[Flaubert, Gustave]]"
  - "[[Balzac, Honoré de]]"
  - "[[Dostoevsky, Fyodor]]"
works_raw: "Swann’s Way"
---

## Why read them
Memory, time and desire in the longest sustained work of introspection.

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
