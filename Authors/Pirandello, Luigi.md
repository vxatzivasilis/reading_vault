---
type: author
aliases: ["Luigi Pirandello"]
born: 1867
died: 1936
language: Italian
roles: ["dramatist", "novelist", "poet", "short story writer"]
priority: 5
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
