---
type: author
aliases: ["Honoré de Balzac"]
born: 1799
died: 1850
language: French
roles: ["dramatist", "novelist"]
priority: 4
status: not-started
wikipedia: ""
influenced_by: []
---

## Why read them
The Human Comedy: society dissected as a system of money, ambition and class.

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
