---
type: author
aliases: ["Philip Roth"]
born: 1836
died: 1904
language: English
roles: []
priority: 
status: not-started
wikipedia: ""
influenced_by: []
works_raw: "American Pastoral"
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
