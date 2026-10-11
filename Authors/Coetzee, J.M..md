---
type: author
aliases: ["J.M. Coetzee"]
born: 
died: 
language: English
roles: []
priority: 6
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "Disgrace"
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
