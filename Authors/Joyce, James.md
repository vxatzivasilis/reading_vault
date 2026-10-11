---
type: author
aliases: ["James Joyce"]
born: 1882
died: 1941
language: English
roles: ["critic", "novelist", "poet"]
priority: 4
status: not-started
wikipedia: ""
influenced_by:
  - "[[Ibsen, Henrik]]"
  - "[[Flaubert, Gustave]]"
  - "[[Shakespeare, William]]"
  - "[[Όμηρος]]"
works_raw: "Dubliners"
---

## Why read them
The most radical reinvention of the English-language novel.

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
