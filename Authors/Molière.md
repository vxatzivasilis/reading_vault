---
type: author
aliases: ["Molière"]
born: 1645
died: 1673
language: French
roles: ["dramatist", "poet"]
priority: 3
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "Tartuffe"
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
