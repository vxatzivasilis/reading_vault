---
type: author
aliases: ["August Strindberg"]
born: 1849
died: 1912
language: Swedish
roles: ["dramatist", "essayist", "novelist", "poet", "painter"]
priority: 2
status: not-started
wikipedia: ""
influenced_by: []
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
